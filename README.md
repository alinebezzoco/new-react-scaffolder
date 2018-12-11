# new-react-scaffolder 

Scaffolding tool for [React](https://facebook.github.io/react/). 
Updated to 16 React version.

This is a forked project by [99xt](https://github.com/99xt) and the original project is [here](https://github.com/99xt/react-scaffolder). 
I updated the dependency to new React version and I made some changes.  

## About the plugin
react-scaffolder is a command line interface which brings smooth developer experience (DX) for React devs. react-scaffolder provides a better way to generate react projects with [react-boilerplate](https://github.com/99xt/react-boilerplate). With this tool it's possible to continue generating boilerplate code with heavy customizations once a project is initiated. 

## What's new 
* You don't need to use the `.reactclirc` to generate a new component in an existing project; 
* Use package.json to run the project; 
* React updated to 16 version; 
* Component generate (parent or child) updated to the new React version; 

## Quick start 
For install the dependency, please follow this steps: 

* Clone this project; 
* Open project folder `cd new-react-scaffolder` and run this command: 

```
$ npm pack
```

* When you finish generating the package, run this command: 

```
sudo npm install -g react-scaffolder-0.3.3.tgz
```

## How to use

Quickest way to get up and running with react-scaffolder

- Initiate a project - ```$ react init awesome-project && cd awesome-project```
- Install dependencies - ```$ npm install```
- Run the build - ```$ npm run build && npm start```
- Instantly create React components - ```$ react g component feed footer``` 
* If you want to create a component in a specific folder add your PATH file in the command. 
* Example: ``` react g component src/components footer```
- Check with interactive view - ```$ react v -c``` 

## Usage

### react init [name] [git repository URL]
*alias: i*

#### name

Project name.

#### Git repository URL (optional)

Git repository URL that you need to use as the template.

#### Options

* `-l`
Add eslint configuration.

---------------------------------------

### react generate component [module] [component]
*alias: g*

#### module

Module name where the react component should be placed within. (Subdirectory within components directory)

#### component

React component name.

---------------------------------------

### react generate test [module] [component]
*alias: g*

Create React component.

#### module

Module name where the test file should be placed within. (Subdirectory within tests directory)

#### component

Test file name.

---------------------------------------

### react view -c -t
*alias: v*

View react components and test files.

#### Options

* `-c`
View React components file directory.

* `-t`
View tests file directory.

---------------------------------------

## Features

- Initiate React projects
- Create React components
- Create test files
- Interactive view of the component structure

## References

- [What is scaffolding ?](https://en.wikipedia.org/wiki/Scaffold_(programming))
- [What is a CLI ?](https://www.techopedia.com/definition/3337/command-line-interface-cli)
- [Why good UX in CLIs matters](https://trevorsullivan.net/2016/07/11/designing-command-line-tools/)
- Projects which facilitate similar objectives
  - [Yeoman](http://yeoman.io/)

## License

MIT © [99XT](https://github.com/99xt)
