# Git-to-GitLab
Git From Eclipse To GitLab


Cloning your project to a **Git repository** is a nice way to manage and have History from your project.i don't wan't to tell about git and git repos because there are Enough Docs telling about. So let's go to Main Course  :)) 

----------
1 - Sign up Into GitLab
-------------
**GitLab** is one of *Git Repositories* that haev one feature that you will like is that you can Create Personal project there **for free** :D 
if you go to [GitLab](www.gitlab.com) you will see page like this :
![1](https://github.com/sinadarvi/Git-to-gitLab/blob/master/1.png)
you just have to click <kbd>Sign up</kbd> button and then sign in with your **Github** Account and then you will see a page like that.

2 - Make Empty Project in GitLab 
-------------
just like below pic, click on  :
![2](https://github.com/sinadarvi/Git-to-gitLab/blob/master/2.png)
after that , you will see page like below image and complete it with Appropriate Answer.
![3](https://github.com/sinadarvi/Git-to-gitLab/blob/master/3.png)
So far, it was so easy. Lets go to Eclipse.

3 - Clone GIT Repository
-------------
here we assume that we have an Existing Project.
Go to Window --> Show View --> Other
Click on Git --> Git Repositories  
Now in the Git window, click on <kbd>Clone a Git repository</kbd>.
![4](https://github.com/sinadarvi/Git-to-gitLab/blob/master/4.png)
after that you should copy `Git repository` from GitLab and then fill this just like that. (you should set HTTPS Username and Password in Gitlab and pass them to here)
![5](https://github.com/sinadarvi/Git-to-gitLab/blob/master/5.png)
Type your username and password
Choose "Store in Secure Store"
Click Next, and then Next again 
there you just set **Directory** for destination 
after that you click on <kbd>Finish</kbd>

so far we have repo with no head.

4 - Check-in code to Gitlab
-------------
you just right click on the name of your project and then `team` and then `share project` as like as this :
![6](https://github.com/sinadarvi/Git-to-gitLab/blob/master/6.png)
select **git** and click next. In next page you should give your repo (what we prepare so far) and choose that.
![1](https://github.com/sinadarvi/Git-to-gitLab/blob/master/7.png)

after that we see the  "NO-HEAD" indication next to our project folder in Eclipse directory view. It can simply mean that, until you make your first **add** and first **commit**, you have no **branch** (not even a master one), hence no HEAD referencing any branch.

so for solve that we just right click on name of project and then **team** and choose **commit** like this:
![8](https://github.com/sinadarvi/Git-to-gitLab/blob/master/8.png)
and then commit a massage and click on <kbd>Commit</kbd>
after that you can see "NO-HEAD" changed to "Master".
again right click on project and then choose **team** and then click on **Push Branch 'master'**
![9](https://github.com/sinadarvi/Git-to-gitLab/blob/master/9.png)
and that's it.you pushed your project on gitLab :))
![10](https://github.com/sinadarvi/Git-to-gitLab/blob/master/10.png)

Come and [visit](http://www.r2t.ir/) our site :) Have Good Day ;)
