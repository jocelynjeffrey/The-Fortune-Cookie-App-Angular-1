# File structure and build process
In this lesson you'll implement the build process for the Fortune Cookie app with NPM and Gulp.  

The following tasks will be supported:

* Local web server
* Auto reload the browser when file assets are saved
* Optimize assets

#### Initialize NPM
Intialize NPM by running the `npm init` command at the following directory: `Lesson1/begin`
````
npm Init
````
Allow all the defaults by pressing `enter` to generate the a `package.js` file at `Lesson1/begin`

```json
{
  "name": "begin",
  "version": "0.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
}
```
#### Gulp dependencies
