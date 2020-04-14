# pluralsight-js-dev-env
This is a generic JavaScript development environment that I built from scratch. This isn't tied to any specific JS framework.
I built this while learning from Pluralsight course by Cory House : https://app.pluralsight.com/library/courses/javascript-development-environment/table-of-contents

I took this course as part of my Node.js path on PluralSight

As part of this course I have learnt about the following things and checked in code relating to it in this repository

1. The use of EditorConfig, which helps maintain consistent coding styles for multiple developers and how to set it up.
2. Package managers(npm) and how to install and manage packages in npm.
3. Configuring and setting up Web Servers(Express).
4. Automating tasks using npm scripts,Pre/Post hooks and setting up concurrent tasks.
5. Transpilers and setting up Transpilers(Babel).
6. Bundlers and setting up Bundlers(Webpack). Debugging bundled code usinf Sourcemaps.
7. Linting and configuring ESLint to watch files to analyze problems and Lint via automation build.
8. Setting up libraries for testing(Mocha),Assertiopn Libraries(chai) and DOM testing using JSDom.
9. Setting up Continuous Integration using TraviCI.
10. Centralising HTTP requests using Fetch and polyfilling. Creating a mock API and generating mock data using json-schema-faker and use json-server to serv and manipulate Mock data.
11. Creating Production Build using Bundle Splitting and Cache Busting and finally setting up TrackJS for Error Logging
12. Cloud Hosting your API using Heroku and hosting your UI using surge

## Get Started

1. **Install [Node 6 or newer](https://nodejs.org)**. Need to run multiple versions of Node? Use [nvm](https://github.com/creationix/nvm) or [nvm-windows](https://github.com/coreybutler/nvm-windows)
2. **Clone this repository.** - `https://github.com/chaitanya-suvarna/pluralsight-js-dev-env.git` or [download the zip](https://github.com/chaitanya-suvarna/pluralsight-js-dev-env/archive/master.zip)
3. **Make sure you're in the directory you just created.** - `cd pluralsight-js-dev-env`
4. **Install Node Packages.** - `npm install`
5. **Run the app.** - `npm start -s`
   This will run the automated build process, start up a webserver, and open the application in your default browser. When doing development with this kit, this command will continue watching files all your files. Every time you hit save the code is rebuilt, linting runs, and tests run automatically. Note: The -s flag is optional. It enables silent mode which suppresses unnecessary messages during the build.
