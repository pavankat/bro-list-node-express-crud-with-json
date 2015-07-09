# App Summary
Make a list of bros and not bros via a Express App that does create, read, update and delete using a JSON file. 

# Tech Stack
Node.js, Express.js, HTML, CSS, Flatfile (json file storage), Handebars (templating engine)

# Purpose
This app is an intro into mongoDB for beginners. I will use this in my MEAN Stack Web Developer class at Barnard.

# NPM Packages Used
* We use handlebars for the view engine.
	npm package: express-handlebars
		https://www.npmjs.com/package/express-handlebars

* We'll use forms to create, edit and delete - but to do so - we'll use method-override to be able to make put and delete requests.
	npm package: https://www.npmjs.com/package/method-override

* To be able to store and retrieve data from a json file, we'll use the flatfile package. 
	npm package: https://www.npmjs.com/package/flatfile
