Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree.

Setup Node Environment
Initialize a new project: npm i
run the development server with `npm run dev
eb create
endpoint URL Udagram-env.h4qn6prydx.us-east-1.elasticbeanstalk.com

hint: in the package.json file i used some commands to apply the script in windows below the differences: For windows: "build": "npm run clean && tsc && @powershell copy package.json www/package.json && cd www && mkdir tmp && bestzip Archive.zip build/* && cd .. ", For linux you can run: "build": "npm run clean && tsc && copy package.json www/package.json && mkdir www/tmp/ && cd www && zip -r Archive.zip . && cd ..",
