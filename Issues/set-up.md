## Setting up your development environment
You're almost ready to start coding, but first you have to set up your computer so  you can test your program while you code

### Download git and connect to your GitHub account
- If you don't already have git on your computer you can download it [here](https://git-scm.com/downloads)
- Connect to GitHub on
   - [Windows](https://www.pluralsight.com/guides/using-git-and-github-on-windows)
   - [Mac](https://kbroman.org/github_tutorial/pages/first_time.html)
   - [Linux](https://www.howtoforge.com/tutorial/install-git-and-github-on-ubuntu/#-configuring-github)
### Adding the Project to your Local Machine
You need to add this repository to your computer to make changes and edit it in the development environment. Go ahead and [clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) this repository on your computer. Make sure you're in a directory that you'll remember/ is easy to access. If you're not sure, your Desktop is a good go-to.
![cloning-repo](https://user-images.githubusercontent.com/45152371/86035053-800f5700-b9f0-11ea-9b7a-e2201286067b.GIF)


Open your **Command line**
In command line:
```sh
>cd desktop
>git clone <copied link here>
```
example:
```sh
cd desktop
git clone https://github.com/hightechu/project-template.git
```

### Download Node.js
You won't be able to run the app just yet. You'll need to download [Node.js](https://nodejs.org/en/) onto your computer. Once this is done downloading, navigate into your project directory and run `npm install` in command line. When that is finished installing, enter`npm start` in your command line and the react app will launch at http://localhost:3000 in your browser.
```sh
>npm install
>cd <project-name>
>npm start
```
You'll be using `npm start` a lot while developing your app so try and remember it, or write it down somewhere.
### How to Use the Developer Tools In Your Browser
In your bowser at http://localhost:3000, right click and select "inspect", this will open up Developer Tools in your browser. Once open, navigate to "Console" this is where the details of any errors and `console.log('print statements')` will appear.
![inspect](https://user-images.githubusercontent.com/45152371/86036091-30318f80-b9f2-11ea-8aa3-e38ed8c19b87.gif)
### Check Out the Files in Your Project
Last thing for this issue is to explore some of the files in this directory. This might be kind of confusing, but don't worry, you'll mostly only be working in src/App.js and src/Components/ImageSequence.js. If you want to learn more about the other files, checkout this [Code Academy tutorial](https://www.codecademy.com/articles/react-setup-i) or the [create-react-app repository](https://github.com/facebook/create-react-app). 
 
