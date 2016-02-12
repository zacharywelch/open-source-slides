# slides-rails-api

Slides on rails-api. 

Designed with [reveal.js](http://lab.hakim.se/reveal-js/#/).

#### More reading:
- [sample app](https://cagit.careerbuilder.com/zwelch/rails-api): Sample music API using Rails.
- [rails-api-template](https://cagit.careerbuilder.com/zwelch/rails-api-template): A rails application template for APIs.

## Usage

1. Clone the slides-rails-api repository
   ```sh
   $ git clone git@cagit.careerbuilder.com:zwelch/slides-rails-api.git
   ```

2. Open index.html in a browser

### Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the slides-rails-api repository
   ```sh
   $ git clone git@cagit.careerbuilder.com:zwelch/slides-rails-api.git
   ```

5. Navigate to the slides-rails-api folder
   ```sh
   $ cd slides-rails-api
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
