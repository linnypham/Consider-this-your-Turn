# Consider-this-your-Turn
Verify that Git is Installed 

1. Verify that git is installed in the environment: 

"git --version"

This should display a message like the one shown below: 

> git version 2.17.1

2. If git is not installed, you can install git by using the following command: 

"sudo apt install git"

---------------------------------------------------------------------------------------------------------

To Clone (Download) a Repository: 

1. Obtain (copy) the repository's HTTPS or SSH URL. The HTTPS URL will look like the example shown below: 

"https://github.com/account-name/repository-name.git"

2. In the environment's terminal, change the current working directory to the location you want to clone 
your files to. For example, if you want to clone your files into the 'music' directory type the following 
command: 

"cd music"

Be mindful that you do not accidently overwrite any of the resources provided in the lab. If you do, 
you can safely perform a lab reset. 

3. To clone the repository type the following command: 

"git clone https://github.com/account-name/repository-name.git"

This will prompt you for your username and password. When you type your password, the terminal will not 
display it, but you are still entering characters until you hit "Enter" ("Return"). 

----------------------------------------------------------------------------------------------------------

To Commit and Push Your Files to a Repository:

1. First, add any new files to the local repository: 

"git add . "

2. Commit your changes to your local repository with an appropriate message (-m): 

"git commit -m 'Created the index.html file'"

3. Push your changes from the local repository to your remote repository: 

"git push origin branch-name"

The 'branch-name' will be "master" unless you create new branches. 

-----------------------------------------------------------------------------------------------------------

Useful Command Line Interface Commands: 

1. List directories: 

"ls"

2. Change the working directory: 

"cd destination-folder"

3. Move files:

"mv file1 ./destination-foler/"
