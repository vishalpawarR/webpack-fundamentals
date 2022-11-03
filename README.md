# webpack-fundamentals
 
clone:
 git clone https://github.com/TheLarkInn/webpack-workshop-2018.git
  
change directory
- git checkout feature/01-fem-first-script
  
  install
- npm install
  

  add scripts in package.json:
  "webpack": "webpack"

in terminal to check
  npm run webpack
  
  add script
"dev": "npm run webpack -- --mode development"
   
   run command
  npm run dev
  
add script
  "prod": "npm run webpack -- --mode production"
  
  change branch
  git checkout feature/03-fem-debug-script --force

  add script
  "debugthis": "node --inspect --inspect-brk ./src/index.js"
  
  run: npm run debugthis

  run this in chrome browser: brave://inspect or chrome://inspect

Then click on the dedicated dev tools for node



  