# Git-Explained
This Is Basic guide So That Everyone can Learn How to Use Git Hub And Git Bash Because Git is need of future and everyone need to know How To use it. I Try My Best To Explain Git In this File 
<img src="https://www.howtogeek.com/wp-content/uploads/csit/2021/09/4d72a7db.png?width=1198&trim=1,1&bg-color=000&pad=1,1"/>
<h2>First Need to install Git Bash</h2>
You Can go there and install git according to ur system requirements <b> https://git-scm.com/downloads</b> <br>
After Git Being Download And install Go to Search Bar And Search For git bash
After You Open Git Bash It should Look Something Like This .<br><br> 
<img src="https://cdn.discordapp.com/attachments/943043933695541271/978652422094356540/unknown.png"/> <br><br>
Don't be Scared If You are new to coding Git bash is <a href="https://www.techtarget.com/searchwindowsserver/definition/command-line-interface-CLI">CLI </a> interface and GitHub is a <a href="https://www.gartner.com/en/information-technology/glossary/gui-graphical-user-interface#:~:text=A%20graphics%2Dbased%20operating%20system,Apple%20Macintosh%20in%20the%201980s.">GUI</a> interace <br>
<h3>So Lets First Clear the Difference between Git Bash and Git Hub </h3>..some Are Listed below for more info You can Visit <a href="https://www.geeksforgeeks.org/difference-between-git-and-github/">GFG WEBSITE</a>
<img src="https://cdn.discordapp.com/attachments/943043933695541271/978654292812660736/unknown.png">

<h2>First Go to GitHub And Create a New Account </h2>
Click The Link TO Directly Go to Signup Page <a href="https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home">Sign Up To gitHub</a> I Hope you All You have  created a Account Lets Move to Git Bash Now... 
<h3> SO Let's Get Started</h3>
<h4>First We Need to Config Our Account on gitBash So When We came back Again Our Bash knows that its us who is using the git bash and doing updations . 
  go to git bash and write <br>
  <br>
  
  ```diff
  git config --global user.name "name"
  git config --global user.email "email"
```
  Note : User Name And Email Should Be Same as on github <br>
  To See Current username and email Use the command given Below.
  ```diff
  git config user.name 
  git config user.email 
```
  
  <h2>
    After Configure the name and email We can start by making local repositry on git bash 
  </h2>
  
    git init             //This command is used to initialize the local repository 
  After we use this command in our bash there will be folder named <b>.git </b> in our local computer states that repositry is initialized properly 

  ``` 
  touch filename.extension     //touch is command used to create files like touch.txt
  We can create files like this or from our window and then we need to add this the bash 
  ```
  Now After creating fikes we need to add files to our local repositry 
  
  Always use ```git status ``` command to check the status about the files .
  <img src="https://cdn.discordapp.com/attachments/943043933695541271/978697902782308372/unknown.png"/>
  <br><br>
  <h3>Now the files are in untracked region we need to add them to track region to do that we have to use the command .</h3>
  
  ``` 
  git add filename    //add single file
  git add . //Add multiple files together 
  git add -A //Add multiple Files together 
  ```
  Do the Git status again and it will show that file added to tracked region 
  <img src="https://cdn.discordapp.com/attachments/943043933695541271/978699043062566952/unknown.png"/>
  <br><br>
  After We Added file We need to commit all the changes done by us to do that we use 
  
  ```
  git commit -m "write a message"
  ```
  And then again git status for the clear detail about the file status.
  <img src="https://cdn.discordapp.com/attachments/943043933695541271/978700129043374141/unknown.png">
  <br><br>
  <h2> Now our content/files is Successfully being added and commited to our local repositry Now We need to push them to our global /github repository</h2>
  <h3> now go to github and make a new repositry and make it public  </h3>
  <img src="https://cdn.discordapp.com/attachments/943043933695541271/978701906857836554/unknown.png"/>
  <h3>Scroll Down And click on create repository </h3>
  <H2>After A new repositry the github should look something like this </h2>
  <img src = "https://cdn.discordapp.com/attachments/943043933695541271/978703258409398302/unknown.png"/>
  
  <h2>Now We Need to Link Our Github Repository to our Local Repository </h2>
    This is called as adding remote to our local repository
  
    git remote add origin "the link of repository given in github" 
```
```
 <img src="https://cdn.discordapp.com/attachments/943043933695541271/978704774671241296/unknown.png"/>
    
<h2>Now The Link Between GitHub And Git Bash Is Setup now we need to push the files from our local repository to our global aka github repository</h2>
  
  ```
  git push origin master 
  ```
 <img src="https://cdn.discordapp.com/attachments/943043933695541271/978707871925698680/unknown.png">
