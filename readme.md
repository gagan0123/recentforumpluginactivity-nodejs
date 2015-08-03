# recentforumpluginactivity Node.js #

Display the topics of your plugin on WordPress dot org forum in order of activity. 

## Install ##

Install [Node.js](http://nodejs.org/).

See the config.js file for the port number and other settings.

```bash
# clone the repository
git clone https://github.com/gagan0123/recentforumpluginactivity-nodejs.git

# cd into the recentforumpluginactivity-nodejs directory
cd recentforumpluginactivity-nodejs

# Install modules
npm install

# start the app
node app
```

Visit [http://localhost:5000/](http://localhost:5000/) in your browser and submit your profile.

## Config ##

In the config.js file you can set:
* The port number.
* How many profile pages to scrape.
* To open the default browser when you start the app (`node app`).