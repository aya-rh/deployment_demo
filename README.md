How to deploy website using GitHub pages. 

Reconfigure repository to allow it. 

To install the dependency:
npm i -D gh-pages

add homepage to package .json:
"homepage": "https://aya-rh.github.io/deployment_demo"

add two commands under scripts:
"predeploy": "npm run build",
"deploy": "gh-pages -d build",

npm run deploy to publish and commit to gh page

a build folder gets made and its gitignored 

can work on it and commit to main repo branch, then when happy commit and push to gh-pages 


add dependency through terminal 
npm i react-router-dom
gets added to dependencies automatically