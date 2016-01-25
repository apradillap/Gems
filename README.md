# Gems (https://github.com/apradillap/gems)

A tutorial about gems in "Object Orientation and Ruby". [Check out the live demo](https://gems-tutorial.herokuapp.com).

Gems enables you look at the awesome packaging system that Ruby provides for distributing programs and libraries. This presentation will show you examples of what it can do.


#### More reading:
- [Installation](#installation): Step-by-step instructions for getting gems running on your computer.
- [Changelog](https://github.com/apradillap/gems/releases): Up-to-date version history.


## Installation

The **basic setup** is for authoring presentations only. The **full setup** gives you access to all gem features and plugins such as speaker notes as well as the development tasks needed to make changes to the source.


### Basic setup

The core of gems is very easy to install. You'll simply need to download a copy of this repository and open the index.html file directly in your browser.

1. Download the latest version of gems from <https://github.com/apradillap/gems/releases>

2. Unzip and replace the example contents in index.html with your own

3. Open index.html in a browser to view it


### Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the reveal.js repository
   ```sh
   $ git clone https://github.com/apradillap/gems.git
   ```

5. Navigate to the gems folder
   ```sh
   $ cd gems
   ```

6. Install dependencies
   ```sh
   $ npm install
   ```

7. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

8. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.


### Folder Structure
- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)
- **images/** All images


## License

MIT licensed

Copyright (C) 2016 Adrián Pradilla, http://www.adrianpradilla.com
