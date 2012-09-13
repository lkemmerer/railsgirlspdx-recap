### Command Prompt
The command prompt is a text-only program that allows you to interact with your operating system.  We use it to go to different places (directories) on your hard drive, to start our Rails [web server](http://skillcrush.com/2012/07/03/web-server-2/), and to run other commands.  Since this group was almost all Windows users, the commands and instructions in this section are for Windows.

**In order to open your command prompt**

1. Go to the Start Menu.

2. Search for _Command Prompt with Ruby on Rails_ and select it.

3. This opens up the command prompt and usually puts you in the `C:\Sites` folder on your hard drive.

**There are a few commands that we used regularly during our meetup**

 * `dir` lists all the folders and files in the current directory you are in.
   It's equivalent to opening up your Windows Explorer and seeing all the icons/pictures for the folders and documents you have -- only it's all text.
 * `cd` will change your current directory (folder).
   For example, to go from `C:\Sites` to `C:\Sites\new_app` (if that were your Rails app), you would type `cd new_app`.  To go back to `C:\Sites` you would type `cd ..` -- the `..` means go up one directory.

**Try this**: let's navigate to the blogs app that we created and look at what files and directories are in the app. (at the end of each line below, press enter!)
```````````````
cd C:\Sites\blogs
dir
```````````````
You should see a few directories and files like the ones below -- often, if you see a `.` in the name, it means it is a file (though that's not always true!)
```````````````
app
config
config.ru <-- file
db
doc
Gemfile <-- also a file !
Gemfile.lock
lib
log
public
Rakefile <-- file !
README.rdoc <-- file that most apps have that often explains to other programmers what the app does
script
test
tmp
vendor
```````````````

We'll cover Rails-specific commands for the command prompt later on, once we go over creating a Rails app.
