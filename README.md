# Simple boilerplate 

A simple blank website template to quick-start simple sites. 
Includes Browsersync to automatically reload browser window
on detected changes to html/css/js. 

## Installation 

1. Clone the repo `git clone https://github.com/rad-hombre/simple-boilerplate [dest]`

2. Run `npm install` inside cloned directory 

3. <del>Run `npm run start` to start serving files</del>

[run-script-os](https://www.npmjs.com/package/run-script-os)– the script used to detect user's Operating System– is currently not working as of npm v7.x (or [yarn2](https://github.com/charlesguse/run-script-os/issues/36) it would seem). 

Until fixed, run `npm run start:nix` or `npm run start:win32` to start
browsersync on \*nix OS or Windows environments, respectively.  
