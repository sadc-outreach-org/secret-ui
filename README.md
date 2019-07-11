# secret-ui

## Dev environment setup
0) navigate in your terminal to the directory that will hold the project directory
1)run the following command in a terminal to clone this repository: `git clone https://github.com/sadc-outreach-org/secret-ui.git`
2) `cd secret-ui` to change directory into repository
3) install Node Package Manager (npm) and Node JS from [the NodeJS website](https://nodejs.org/en/)
4) in the terminal, install the VueJS command line interface with the following command: `npm install -g @vue/cli` (the -g flag ensures that Vue is installed globally instead of just locally)
5) run `npm install` to install project dependencies
6) run `npm run serve` to compile project and serve locally.
7) localhost website address will be displayed in terminal window. website will run and hot-reload code changes as long as `npm run serve` is running. use `ctrl+c` to shutdown server.
8) run `npm run build` to compile and minify the project for web deployment. resulting files are in src/dist.
9) run `npm run lint` to lint the project and find syntax errors. run `npm run lint --fix` to automatically fix issues. ESLint configuration file is located in the `packages.json` file



### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
