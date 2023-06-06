# reactNext
react, next.js

step 1: 
npm init -y
y means yes for accepting all default value without poping out the box to let you choose.

step 2:
npm install react react-dom next
then package-lock.json file will have the newest installedversion of react, react-dom, next

step 3:
create new folder pages and create a new file index.js under this folder
write initial code in this index.js

then create a new file next.config.js, write initial code
module.exports is used to config which function or value you want to allow other modules to import and use.

step 4:
in package.json, add following config:  
"scripts": {
  "dev": "next",
  "build": "next build",
  "start": "next start"
}

step 5:
run "npm run dev"
then in browser you can visit http://localhost:3000

tips:
make sure the node version installed the newest version, for example, the node version 12 will get error when you execute "npm run dev"
