How to deploy website using GitHub pages. 

Reconfigure repository to allow it. 

To install the dependency:
npm i -D gh-pages

add homepage to package .json:
"homepage": "https://aya-rh.github.io/deployment_demo"

add two commands under scripts:
"predeploy": "npm run build",
"deploy": "gh-pages -d build",

npm run deploy to publish

a build folder gets made and its gitignored 

