# Actor Model

## Introduction

Presentation of Software Engineering performed during [Hack Your Career events](www.facebook.com/Hack.your.Career)

## Setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (1.0.0 or later)

1. Clone the reveal.js repository
   ```sh
   $ git clone https://github.com/lszymik/softwareeng
   ```

1. Navigate to the actormodel folder
   ```sh
   $ cd softwareeng
   ```

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port 8001`.

