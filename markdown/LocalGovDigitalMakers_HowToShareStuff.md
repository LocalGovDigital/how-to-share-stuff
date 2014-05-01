# How to Share Stuff
A basic guide for how to share code and other stuff


## What to do before you share

### Get permission

If you’re employed by an organisation to do something, it’s more than likely they own whatever you produce. This means you need to get their permission before you share their stuff. 

The ease of this can range from asking your boss once, to having to put together a case for doing so, taking this to senior management and if approved getting every share signed-off.


### Be secure

Never share anything containing passwords, keys, private data, or anything similar. If you don’t take this seriously you could be risking a visit from the Information Commissioner's Office and you could be opening systems and third party accounts up for the world to access.


### If in doubt, ask.

If you’re ever unsure about what you can share or how to share it, it’s always better to check first. Information made available online is very difficult, if not impossible, to remove. Data protection officers, data owners and other stakeholders will be able to advise on the most appropriate way options for sharing things. 

If you’re still unsure, you can always ask online to see if anyone else has had a similar experience.

## Where to share

There are plenty of code repository sites for open source projects, but GitHub is the most popular. Code repositories like GitHub allow people to share their work and for others to suggest changes. 

You can sign up as a user and add your organisation, for example here’s [LocalGovDigital on GitHub](https://github.com/LocalGovDigital).

## Licences

Using a licence will clearly define how you want your content to be shared. It’s a good idea to share using a licence so that other know in which ways they can use your code. For example if you don’t want your code to be used commercially, you can choose a licence that specifies this.

There are many to choose from and it needs to take account of the agreement you have with your employer to share your work.

### Software

[http://choosealicense.com/](http://choosealicense.com/)
A useful guide on the basic options for software licenses.

### Content
A good way to [choose a Creative Commons licence is here](http://creativecommons.org/about/license/) or you might like to use [one designed for open government here](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/).


## How to share

### Github

Github is, in crude and simple terms, an online service for storing files. Although originally aimed at developers storing code, Github has been adopted outside the development world as a great method for sharing and collaborating.

You can store your files on Github publicly, for free. You group files into a ‘repository’ for example the LocalGov Digital Github account is [here](https://github.com/LocalGovDigital) and within that we have the [Content Standards repository](https://github.com/LocalGovDigital/content-standards) which contains all the files that make up the Content Standards guidance.

So as you share more and more, your account will contain many repositories, think of them as projects if the terminology feels alien.

The advantages to a service like Github is that the files you store can be quickly copied or ‘forked’ by other users of Github and the changes other users make can be ‘merged’ back into your version, which makes for a great culture of open collaboration.

Getting files onto Github

Sadly, Github doesn’t have an ‘upload’ button. The idea is that you have a version of the repository on your computer and a copy on Github. 

When you make a change to the files in the repository on your computer, you ‘commit’ to those changes and then you ‘push’ those changes from your computer to Github. Each time you ‘commit’ to some changes, you create a new version of the file. It’s a bit like clicking ‘File > Save As..’ except the changes are stored on Github.

One of the easiest methods for getting your files onto Github is using a desktop application.

Github have made desktop applications available, again completely free. You can download them here:

- [Github for Windows](http://windows.github.com/)
- [Github for Mac](http://mac.github.com/)

As most local government organisations use Windows, here are the steps for setting up your first repository and adding some files to it.

#### Setting up Github for Windows

1. If you haven’t already done so, go to [Github](https://github.com/) and sign up for an account
2. Open Github for Windows.
3. Sign in with your Github username and password
4. You’ll be asked to ‘configure git,’ enter your name and email and click ‘Continue’
5. Github for Windows will then look for local repositories, just click ‘Skip’
6. You’ll then be taken to the ‘repositories’ page
7. That’s it! You’re ready to start using Github for Windows.

    ![The Github for windows app showing an empty repository home page](https://s3-eu-west-1.amazonaws.com/localgovdigital/how-to-share-stuff/github-home.png)

    _The local repositories page you’ll see after setting up Github for Windows_

#### Creating a repository

1. From your ‘repositories’ page, click ‘Create’
2. Enter a name for the repository (the name cannot have spaces or ‘special characters’ like @/!$£ etc)
3. Enter a description for the repository, something that makes sense to humans
4. Select where you’d like to store the repository (your files) on your computer. Use the ‘Browse’ button to choose a location.
5. Lastly, click ‘Create’ at the bottom of the screen

    ![The Github for windows app showing the create repository page](https://s3-eu-west-1.amazonaws.com/localgovdigital/how-to-share-stuff/github-create.png)

    _Completing this screen and clicking ‘Create’ will create your repository_

6. That’s it! Your repository has been created. Even though your repository is empty, if you go to http://github.com/your-username-here, you should now see your repository already available on the web.

    ![The Github for Windows home page showing the newly created repository](https://s3-eu-west-1.amazonaws.com/localgovdigital/how-to-share-stuff/github-repository.png) 

    _Once your repository is created, you’ll be returned to the ‘repositories’ page_

#### Adding your files

1. Copy and Paste or Cut and Paste your file(s) into the repository folder on your computer
2. Open Github for Windows
3. Double click on your repository, you’ll be taken to another screen
4. The new screen will show you a list of the files that have changed, new files are treated as changes because technically, they are!
5. We’re going to ‘commit’ the change we’ve made, at this point we’re saying ‘Yes, please save my files in this state so that if something goes horribly wrong, we can go back to this point.’
6. On the left of the screen, there is an ‘Uncommitted changes’ box. This is where we can leave a message about the changes we’ve made

    ![The Github for Windows repository page showing a list of files ready to be committed](https://s3-eu-west-1.amazonaws.com/localgovdigital/how-to-share-stuff/github-add-files.png)

    _The uncommitted changes will show up on the repository page 
ready for you to commit them_

7. Type in a summary of the changes in the ‘Summary’ field, something brief.
8. Type in a description of the changes in the ‘Description field, something that explains what you’ve done. 
9. Once you’ve put message in at least one of the boxes, click ‘Commit to master.’
10. Clicking ‘Commit to master’ takes a snapshot of your files in their current state so that we can go back to it later if we need to
11. Now we need to publish our ‘commit’ to Github so that it’s made public and other people can make use of our files. In Github for Windows this is simply a matter of clicking ‘publish’ in the top right hand corner.

    ![The Github for Windows repository page showing a committed change and an illuminated publish button](https://s3-eu-west-1.amazonaws.com/localgovdigital/how-to-share-stuff/github-publish.png)

    _Clicking the ‘publish’ button will push the changes 
up to Github and make them public._

12. The ‘publish’ icon will change to a ‘sync’ icon once the ‘commit’ has been published.
13. That’s it! Your files are now published to Github.

#### Publishing a change

There will come a time when your published document needs updating, or maybe it’s a work in progress and you want to publish changes as you work. Here we’ll take you through publishing changes an existing repository to Github

1. Any time a file in your repository folder changes, Github for Windows knows about the change. Changes that haven’t been committed and published are referred to as ‘Uncommitted changes.’
2. To see uncommitted changes, open Github for Windows and double click on the repository that you’ve made changes to.
3. Github for Windows will then show you a list of the files that have changed.

    ![The Github for Windows app showing the repository page with changes to files highlighted in red and green](https://s3-eu-west-1.amazonaws.com/localgovdigital/how-to-share-stuff/github-changes.png)

    _Uncommitted changes will show as a list in your repository, changes are highlighted in red and green_

4. Before we can publish this change, we have to commit it.
5. In the ‘Uncommitted changes’ box, type in a summary of the changes in the ‘Summary’ field and a description in the ‘Description’ field.
6. Click ‘Commit to master’ just below the ‘Description’ field.

    ![The Github for Windows app showing the repository page   with changes committed and an illuminated sync button](https://s3-eu-west-1.amazonaws.com/localgovdigital/how-to-share-stuff/github-changes-unsynced.png)

    _Once your changes have been committed, they’ll show up
in 'Unsynced commits' until you sync your repository on Github_

7. To publish this commit to Github, click ‘sync’ in the top right hand corner.
8. That’s it! You’ve published your changes to Github, visit [http://www.github.com/your-username-here](http://www.github.com/your-username-here) to see your repository on Github

### Contributors to this document

* Dan Blundell: LGSS
* Paul MacKay: Nesta
* Phil Rumens: West Berkshire Council