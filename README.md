# My notes from 

cloned git repo 
git clone <mygitrepourl>

docker-compose build

docker-compose up

  
 Answer to question 14:
  
  Generally, it's bad practice to commit a file to the master branch. It's best to create a new branch and merge it because
  - it's easy to revert
  - features are clear
  - it's good for working in teams
  - i can prevent it by modifying branch protection rules to "Require pull request reviews before merging"


  Answer to  Question 12
  I had issues pushing new commits to my remote repo because I changed computers and mac key chain token configuration needs the old Oauth key which I didn't have. I have some dependent scripts that access my github that'll break if I recreate the token. As a workaround, I put the image in this README.md. If you click on the Preview tab on the top left of this window, it'll display nicely, along with my signature. 
  
<img width="1546" alt="image" src="https://user-images.githubusercontent.com/43153580/202317188-88ce251a-e1c9-4e16-9882-ac2d1c0511c5.png">


The two files 3.key and 4.key are in this remote repository. 
  
  Overall impressions:
  This has been a great exercise that had me channel my frontend and git/github skills that I do not use daily. Forking your repo and changing the base repo to enable pull and merge request had me take a step back to rerun logic flow. 
  The other part was deciding where to run the app as the thought on EC2 instance, minikube and finally docker came into the decision tree. It was good experience learning and debugging. 
  It always feels good when it's done and I look forward to hearing back soon. 
  
  Thanks again,
  Will. 



