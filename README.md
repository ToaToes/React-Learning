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

