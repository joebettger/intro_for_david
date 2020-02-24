# Intro for David H

## Welcome! This is Markdown

Hey David, this is a file called `README.md` that you can find in almost any widely used piece of software on the planet. By convention, if you name a file `README.md`, especially if it is at the root of a project, it will show up in any version control piece of software. You use a `README.md` to take notes for yourself and to communicate things to other developers. 

In general, a `README.md` doc uses a syntax called `markdown` which is very easy to learn the basics of, and you rarely need anything more than the basics. Here's a [cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## Next Steps

_Before we move onto to learning a few things, there's some logistics to work out_

* Create a Github account and email/text it to me
* Make sure Git is installed on your computer (I got this started the other day)
  * You will probably need to do a bit of configuring it on your pc. See [guide](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
    * 
    ```
      $ git config --global user.name "John Doe"
      $ git config --global user.email johndoe@example.com
    ```
    * I suggest using Windows Powershell, not the default terminal tool.
* Pull down this repo 
  * See Clone or Download button on the home page for this repo
  * Click `Use HTTPS` and copy that URL. I'll show you how to get SSH setup sometime you're in town
  * In your powershell, create a new folder we'll use called `dev`
    * `mkdir dev`
  * Navigate into `dev`
    * `cd dev`
  * Clone down this repo
    * `git clone https://github.com/joebettger/intro_for_david.git`
    * Go through prompts if you get them
  * Navigate into intro for david
    * `cd intro_for_david`
* Change the `README.md` file with your first commit
  * For simplicity, start with adding some text under David's First Commit heading like HELLO WORLD
* Save the README.md file `ctrl + s`
* Back in powershell,
  * Add the new file -> `git add .`
  * Commit the new file -> `git commit -m 'my first commit (DH)`
  * Push the updates -> `git push`
* Make sure your changes worked!
  * Refresh the page in your web browser and make sure the new text is there


That's the basics of using **GIT**. We'll explore this tool a bit more before we get into any coding so that we can grab each other's code. While this may not seem that interesting, this is possibly **THE SINGLE MOST USEFUL THING YOU COULD KNOW COMING OUT OF SCHOOL AND INTO A REAL JOB WITH SOFTWARE**. 

## David's First Commit Goes Below!




