# Getting Started


**Important**: It should go without saying that anytime you are asked to create an account you should ALWAYS:
* Make sure to use a professional username/handle. We recommend the username incorporates your name. 
* Be sure to add an appropriate avatar to your profile. 

## In your Notebook

Be sure to write down any passwords you create for any of these accounts on a special page of your notenook. (This way you can keep track of your Admin password for MySQL, which I guarantee you will otherwise forget.)
## Week 1


### Terminal

#### Option 1
* Command (or Cmd) ⌘ - Space bar to open the Spotlight search field. 
* Type "Terminal". 
* Press Enter.

#### Option 2 

* Open Finder
* Navigate to /Applications/Utilities/
* Double click on Terminal.app


### git

Using Terminal, issue the following command:
```
git --version
```

This should return the a line similar to:  
```
git version 2.21.1 (Apple Git-122.3)
```

You may need run the following in order to install git along with other various command line tools.
```
xcode-select --install
```


### Change default shell to bash

Using Terminal, issue the following command: 

```
chsh -s /bin/bash
```


### Brew

* Visit [https://brew.sh/](https://brew.sh/).
* Follow the directions under "Intall Homebrew".


### Anaconda

* Visit [Anaconda's](https://www.anaconda.com/distribution/) download page.
* Download the pkg file for Python 3.7 version.
* Install the package. Be sure to follow intructions for Mac OS version "Catalina".


### PyCharm

* Visit [JetBrains'](https://www.jetbrains.com/pycharm/) download page for PyCharm.
* Download the dmg for the Professional version for Mac.
* Use the downloaded dmg to install the application.


### DataGrip

* Visit [JetBrains'](https://www.jetbrains.com/datagrip/) download page for DataGrip.
* Download the dmg.
* Use the downloaded dmg to install the application.


### Postgres App

* Visit [Postgresapp's](https://postgresapp.com/downloads.html) download page.
* Download the dmg for the latest release.
* Use the downloaded dmg to install the application.

### MySQL

* Find a clean way to install MySQL as wella s Postgres.

### Slack

* Visit [Slack's](https://slack.com/downloads/mac) download page.
* Download the dmg for the latest release.
* Use the downloaded dmg to install the application.
* Sign in to the zcw workspace.


### gmail

* Visit [gmail.com](https://www.google.com/gmail/about/) and create an account.


### github

* Visit [github.com](https://github.com/) and signup for an account.  


## Week 2

Let's do all of these on Day One, rather than try to remember to keep assigning this repo. So, finish all these now.

### ggrep

Using terminal, type:
```
grep --version 
```

You should recieve a response similar to:
```
grep (BSD grep) 2.5.1-FreeBSD
```

We want to be able to use PCRE for this week's labs so we will be using GNU grep istead of the already installed BSD grep. 
```
brew install grep
```

Validate install was successful: 
```
ggrep --version
```
Should yield a result similar to:

```
ggrep (GNU grep) 3.4
...
```


## Week 3

### Postman

* Visit [Postman's](https://www.postman.com/downloads/) download page.
* Download the latest version (zip).
* Drag and drop the application to the /Applications folder.

### AWS CLI

* Visit [Installing the AWS CLI version 2 on macOS](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-mac.html)
* Follow the guide to install and confirm installation.


## Week 4 

* Visit Docker's [Get Started With Docker](https://www.docker.com/get-started) page.
* Register for an account.
* Download and install the docker for desktop app.
* Sign in to the docker for desktop app using your docker account.
