# Disc-Bot
Repo for the discord bot.

Steps to clone this repo to your computer:
1. You will need to download git on your computer. https://git-scm.com/downloads
  - Once its downloaded run git bash (just look it up in windows search bar).
  - Type the following command into it ->git config --global user.name "Your desired username"<-
  - Repeat the command without the quotation marks and youre username. It should echo your username.
  - Type the following command into bash as well ->git config --global user.email "email@example.com"<-
  - Once again repeat the command and it should echo your desired email back if done properly.
2. Now you will need to create a new ssh key for github. https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/
  - Type the following command into git bash ->ssh-keygen -t rsa -b 4096 -C "email@example.com"<-
  - It will ask to "Enter a file in which to save the key" just hit Enter.
  - You will then be prompted to enter a passphrase, to where you will enter a desired passphrase for yourself.
  - To ensure that the ssh-agent is working type this command into git bash ->eval $(ssh-agent -s)<-
  - Type the following command into git bash in order to add your ssh key to the agent ->ssh-add ~/.ssh/id_rsa<-
3. Adding your ssh key to your github account. https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/
  - Type the following command into git bash ->clip < ~/.ssh/id_rsa.pub<-
  - Now go to your github account on the website and go to the upper right hand corner and click on the drop down menu with your image.
  - Click settings.
  - Scroll down to where it says New SSH key and click on it (on the left hand side).
  - For the title field type anything you wish.
  - Then paste your ssh key into the Key field which you had previously copied.
  - Add SSH key after that
4. Cloning the repo to your computer https://help.github.com/articles/fork-a-repo/
  - Create a folder on your computer where you would like to clone the repo to (where you will be doing all the work).
  - Open git bash and change your directory to that folder on your computer.
  - Type the following command into the bash ->git clone git@github.com:anexSozio/Disc-Bot.git<-
5. You should now be done and have the files of the repo in that directory/folder.
