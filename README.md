
# Web Development 2 Final

# Style Stage

## Built with IDMX 11ty Sass Starter

The set of development scripts in this starter is configured to watch and compile a simple Sass structure using 11ty.

The code is located in the `src` folder and the page is created in the `public` folder.

The `settings.json` in the `.vscode` folder sets the `LiveServer` configuration to serve from the `public` folder and can be used to serve the built page.

The build process includes minifiying and autoprefixing of styles via the `postbuild` script, which runs automatically after a `build`.

## Installation

**`npm install`**

>Run this command once to install the needed node modules.

## Development Scripts

**`npm start`**

> This script runs 11ty with hot reload and served at the url localhost:8080. It will reload whenever there are HTML or Sass changes.

**`npm run build`**

> This script does a production build and includes minified, autoprefixed CSS.

Use this as the "Publish command" if needed by hosting services such as Netlify.
---

### Resources

[HTML Content from Style Stage by Stephanie Eckles](https://stylestage.dev)

[Build Excellent Websites by Andy Bell](https://buildexcellentwebsit.es/)

[Code for Bell's Build Excellent Websites (the source for the Fluid CSS code linked above) ](https://glitch.com/edit/#!/build-excellent-websites)

Background Image by Andrea De Santis on [Unsplash.com](https://unsplash.com/@santesson89)