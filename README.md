Here is the userChrome.css that I use with Firefox to match my I3wm theme. I also modified its structure because I don't support tabs above the touchbar.

![image](https://draconis.me/images/2019/10/firefoxcss.gif)

Not being a developer, I associated pieces of code that I found:

* on different internet sources for the colors.

* on the reddit group [r/firefoxcss](https://www.reddit.com/r/FirefoxCSS/comments/bg4oqd/responsive_one_liner/) for the hidden bar part.

### To use this file on Windows:

1. [Download](https://framagit.org/draconis/firefoxcss/-/archive/master/firefoxcss-master.zip) the userChrome.css file
2. Go to the folder *C:\Users\"username"\AppData\Roaming\Mozilla\Firefox\Profiles\"profile_mozilla".default*
3. Create the folder *chrome* if it does not exist
4. Copy the file *userChrome.css*
5. Open Firefox and type about:config in the address bar
6. Look for the line *toolkit.legacyUserProfileCustomizations.stylesheets* and change its value to *true*
7. Restart Firefox and enjoy

### To use this file on Linux:

1. [Download](https://framagit.org/draconis/firefoxcss/-/archive/master/firefoxcss-master.zip) the userChrome.css file
2. Go to the *~/.mozilla/firefox/"profile_mozilla".default/* folder
3. Create the *chrome* folder if it does not exist
4. Copy the *userChrome.css* file
5. Open Firefox and type about:config in the address bar
6. Look for the *toolkit.legacyUserProfileCustomizations.stylesheets* line and change its value to *true*
7. Restart Firefox and enjoy
