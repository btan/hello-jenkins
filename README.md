# hello-jenkins
adapted from : http://code.tutsplus.com/tutorials/setting-up-continuous-integration-continuous-deployment-with-jenkins--cms-21511

Step 1:
Setup a github account & create a repository name (hello-jenkins)
Step 2:
In Local machine, clone the new repository:
git clone git@github.com:btan/hello-jenkins.git
cd hello-jenkins
Step 3:
Build Node.js app:
-create a package.json
Install app dependenciies:
npm install
-write app Code, app.js
Run the app:
node app.js
Step 4:
Navigate to browser: http://localhost:5000

Step 5:
Create a test 
-Add test/test.js
Run a test:
"node_modules/.ban/mocha" "test/test.js"

Push a working copy to the repository:
git add .
git commit -m "Add node app"
git push origin master

