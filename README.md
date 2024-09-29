# React

## React to start with (on Mac)

### Homebrew file management:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
permission needed (Sudo)
```
brew intsall Node
```

### Node package management:

Note: 

"npm install -g create-react-app" no longer supported
"https://dev.to/ag2byte/create-react-app-is-officially-dead-h7o"

"-g" -> perform globally

```
npm cache clean --force
```
https://stackoverflow.com/questions/51607362/please-run-npm-cache-clean

To clean old packs:
```
npm uninstall -g create-react-app
```

### Vite for creating React app

Download Vite for createing react apps
```
npm create vite@latest
```

Select frameworks -> React
Select language -> Typescript/Javascript

Then run:
```
cd [Filename]
npm install
npm run dev
```

## React to start with (on WIN)

## Solution encountering problems

Note: show hidden files for mac: https://support.carbonite.com/articles/Personal-Pro-Mac-Displaying-Hidden-Library-Folder

Sudo causing problems: Permission denied for altering js files
https://stackoverflow.com/questions/51967335/npm-install-permission-denied-macos


To check the location of the package:
```
npm config get prefix
```

Delete Node Modules OR Reinstall Node if still not working
Then direct to the project path, Check the permissions of your project directory:
```
ls -l /path_to_project
```
Ensure that user has the appropriate permissions. change the ownership:
```
sudo chown -R $(whoami) /path_to_project
```


## Reinstall

```
brew uninstall node
```
check versions
```
node -v
npm -v
```
clean up any unused dependencies or old versions of packages with:
```
brew cleanup
```









