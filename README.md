# Git Together Boilerplate

__Git Together__ is a D3 visualization of a team-based Git workflow that updates in real-time when users emit Git events. Technologies used in this project include:

  - Electron
  - React
  - Socket.io
  - Node / Express
  - Webpack
  - SCSS
  - Mocha / Chai

## Installation

#### Grab code and resolve module dependencies

	git clone https://github.com/team-fourfunfolks/git-together.git
	cd git-together
	npm install

## Developing

First build files and start server
```
npm start
```

Then in new tab, start app
```
npm run electron
```


#### Run server-side environment

	npm run server
	
#### Testing

	npm run test

## File Structure

#### Client Side

React components will be layed out in the __src__ folder from the root directory.

#### Server Side

Express/Socket.io components will be in the __server__ folder from the root directory


## TBD: Deploy
Build sources with webpack
```
npm run build
```

The root 'index.html' file will point to the 'build' folder. Those files will need to be shipped out.


## Important

Need electron-packager to deploy properly. Refer to 'build' script : https://github.com/sindresorhus/electron-boilerplate/blob/master/boilerplate/package.json
