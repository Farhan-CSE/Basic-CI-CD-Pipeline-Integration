This is a Basic CI/CD pipeline integration of Jenkins with GitHub webhook for Deploying projects on servers using Bash Script.

Understand the Architecture:

✔ Code is tested in Test environemnt by QA and approved for release to production environment
✔ Code is committed to github project from developer teams end.
✔ Github webhook initiate Jenkins Job to activate.
✔ Jenkins will Pull the code from github.
✔ Jenkins will build and run the code via Bash script 
✔ User will be able to access the application through browser.

![CICD Architecture](https://github.com/Farhan-CSE/Basic-CI-CD-Pipeline-Integration/assets/70094377/d085e622-ead2-4fe4-bda8-b9066689d612)


Lets get started :

✔ Create a repository of your project in your github and clone that repo in your local machine.
✔ Developer makes changes to the project file in the cloned repo and pushes the code in you github.
✔ The updated code will be available in your github 
✔ Github webhooks sents a trigger to Jenkins which passes through server firewall and then triggers a Jenkins job if valid. Reference : how to use gihub webhooks ()
✔ All credentials are encoded in script.
✔ Jenkins initiates auto project build and deployment via Bash Script.
✔ If the Jenkins job fails to execute build, an Email notification is sent to the developer team with error logs.
