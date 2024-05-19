## Requirements

- make sure nodejs and npm (normally included with nodejs) are installed
- install @types/node globally `npm i -g -D @types/node`


## Get Started

### with Git installed

- run `git clone https://github.com/KaninchenSpeed/empty_typescript_project.git` to clone the project (add a `.` to the end to clone into existing directory)
- rename the directory to your project name
- run `npm i` in the project directory to install all dependencies


### without git

- click on the gray code button (next to the green button) on the top right of the page
- click on download zip
- extract the zip where you want the project to be
- rename the directory to your project name
- run `npm i` in the project directory to install all dependencies

### Notes

The source code files are in the src directory.

Put config in the directory called `config` as it is ignored by the auto restart.

#### Scripts
- run `npm run dev` to start your application in dev mode (with auto restart on file save)
- run `npm run build` to compile your project to plain js (found in the dist directory)
- run `npm run start` to run node on the compiled js files

#### License
This template is licensed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
