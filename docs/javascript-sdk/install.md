# Install the JavaScript SDK

Using Node and Yeoman, you can create a stand-alone booking widget that includes the JavaScript SDK. This will create a directory with all of the templates, styles and config options you need to extensively edit your booking widget.

## Dependencies
You will need to install the following dependencies before getting started. Once you've installed node and git via their respective sites you can install the rest of the dependencies using the terminal. You will need to install:

- [git](github.com)
- [node.js](https://nodejs.org/en/)
- Yeoman Generator `npm install -g yo` 
- Gulp `npm install -g gulp-cli`
- Bower `npm install -g bower`

> If you're not familiar with the terminal [Codecademy have a really good interactive tutorial](https://www.codecademy.com/ru/courses/learn-the-command-line/lessons/navigation/exercises/your-first-command) that will introduce you to the basics.

## Create your project
Once you have your dependencies installed you can download the BookingBug Yeoman generator via the terminal.

```
npm install -g generator-bookingbug
```

This will make the `yo bookingbug` command available globally on your local development environment. Next navigate to the directory where you want to create the application and type

```
yo bookingbug
```

This will begin creating your booking widget's directory on your local computer. Before it starts, you will need to give the generator your Bookingbug company's information:

- What is the name of your project? - This will create the folder your widget's files will be placed in (letters a-Z and numbers 0-9 only).
- What is your BookingBug company id / API URL? - The `company_id` and `API URL`  can be obtained from the API Settings under BookingBug Advanced Settings (Click the settings Cog in the top right corner, and Advance Settings in the left side column) 
**e.g** 12345 & https://uk.bookingbug.com/.


Once all of the above has been installed, navigate to the new folder that yeoman created (named after your project) and run `gulp` to watch files for changes and to host your application locally on [http://localhost:8000](http://localhost:8000)

> You can see a screen-cast of this entire process here:

<script type="text/javascript" src="https://asciinema.org/a/45879.js" id="asciicast-45879" async></script>
