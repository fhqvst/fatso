# Fatso
When contemplating the fact that the web development industry last year mostly resulted in a [massive abundance of static site generators](http://www.staticgen.com/), I figured I just had to make another one.

Note that this tool is still in pre-pre-alpha stage, and should not be used by anyone.

## You don't need a task runner
The [Taft](https://github.com/fitnr/taft) parser together with some bundling scripts in `package.json` makes up the core of the poodle. This means *no task runners*, *no extraneous tooling*, and most of all: *full configurability*. Don't like browserify? Simply edit the `styles` script to use webpack instead. Feeling more eccentric than the rest of us? Simply exchange Sass for Stylus. Even the directory structure is flexible, and it's all just a matter of some tiny changes in the `package.json` file. Oh, did I mention deployment to GitHub Pages directly from your terminal?

## This all sounds amazing, where do I buy one?
1. Clone this directory `$ git clone https://github.com/fhqvst/fatso`
2. Install depencencies `$ cd fatso && npm install`
3. IMPORTANT! Open up package.json and set `$ghPagesUrl` as necessary
4. Install the generator `$ npm run blog:init`
5. Write cool story about dogs 🐑
6. Publish it `$ npm run blog:publish`
