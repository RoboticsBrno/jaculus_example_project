# Example npm project for use with Jaculus
This is an npm project configure with some stuff in order to build JS for Jaculus runtime.

* TypeScript
* Babel (transpile new features)
* Webpack (pack into a single file without imports)

## How to use
You need NodeJS runtime and npm installed on your machine.

* After pulling this repo, run `npm install` to install dependencies.
* `npm run build` to build the packed js file in `dist/main.js`
* `npm run upload` to build and upload the file to ESP32
