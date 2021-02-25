# Section 1 - Basic Software Programming

## :arrow_forward: S1D0 - Setting Up
Lead: @Blumi102 (Michelle Blumenstein)

Steps to create the node projects which we'll use as template:

1. git init
1. npm init -y (main: app.ts)
1. npm install -D typescript
1. npm install -D ts-node
1. npm install -D @types/node
1. npm install -S express
1. npm install -D @types/express
1. mkdir src
1. touch src/app.ts
1. tsc --init
1. tsconfig.json add: "exclude": ["node_modules", "./build"]
1. npm install -D nodemon
1. npm install -D eslint
1. ./node_modules/.bin/eslint --init  
   1. (TODO: give configuration)
1. add rule "no-console": false
1. touch .eslintignore
1. auto-format (Visual Studio Code specific)
   1. donlowad eslint extension 
   1. check that it is enabled in the bottom right corner
   1. mkdir .vscode
   1. touch .vscode/settings.json
   1. modi
1. add script "start": "tsc && node app.ts"

