# AppStarter for Windows
Batch script for running Ionic, Laravel, NodeJs and Python apps that are in your local GitHub folder

![Initial Screen](/app.png)

###Prerequisites
```
Windows NT, XP, 7, 8, 8.1 or 10
```

### Steps in Starting an App
1. Change the XAMPP and GitHub paths to match yours
``` Bat

SET "XAMPP_Dir=C:\xampp"
SET "GitHub_Dir=C:\Users\User\Documents\Github\"

```
2. Provide the name of the Project Folder
3. Input I, L, N or P to choose the type of app (Ionic[I], Laravel[L], NodeJs[N], Python[P])
4. If the app is an NodeJs or Python app, input the starter file (Init file). i.e hello.py, run.py, server.js, run.js, app.js or WHATEVER STARTER FILE YOU HAVE!
5. THAT'S IT FOLKS! YOUR APP WILL NOW BEGIN UNLESS YOU MADE A TYPO!

### Built With

* [Windows Batch](https://www.microsoft.com/resources/documentation/windows/xp/all/proddocs/en-us/batch.mspx?mfr=true) - Windows script for simplifying routine or repetitive tasks
* [VS code](https://code.visualstudio.com/) - A free and open-source code editor with awesome features


### To-do
- [ ] Setup screen - for setting the GitHub and XAMPP directory paths
- [ ] Configurators - for NodeJs (npm, gulp etc.) and Python (pip etc.) Apps
- [ ] Shell script - for the Mac and Linux devs that walk among us. I haven't forgoten you
- [ ] I may even just re-write it in C#, build a .exe that registers itself as an environmental variable globally accessible on your terminal via a single command plus arguments

### Acknowledgments

* Hat tip to anyone who's code was used in any way
* All my pips at StackOverflow
* etc.

### Team
[![David Ngugi](https://secure.gravatar.com/avatar/39b9caa95fab4b9c5ccb9cd7a041d21c)](http://davidngugi.com)
