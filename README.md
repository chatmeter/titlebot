# Title Bot
## General goal

Create a web form that allows a user to type in a url to any website and have it then output the Title and favicon of that website on the same page. For example, if I typed in CNN.COM into the text input of the web page, it would spit out something like the following:

>![CNN Favicon](https://www.cnn.com/favicon.ie9.ico "CNN Favicon") | CNN - Breaking News, Latest News and Videos

The application should consist of a javscript/html/css front end, and a backend API that fetches the page title.
The web page should display a historical list of all urls entered by the user, along with their titles.

You may use your preferred language for developing. Our preferred languages at chatmeter are scala and javascript.

This task should take you somewhere around 4 hours. Make a git repository available online and send us the link. Make sure that the application can be run by us with minimal set up. You will present the application during your next interview.

## Requirements
### Technical requirements
- Use React for the front end
- The backend should be RESTful

### Visual requirements
- Make the page look good, it doesn't have to be fancy but it should have some styling. Existing libraries are fine like Bootstrap or Material UI are great.

### Documentation
- Make the code readable, this will serve as the basis for your technical interview.
- Use the README file to document how to setup and run your project. This is also a great place to drop any notes about decisions made or problems encountered.

## Changes for different levels of applicants
### For junior level applicants
- You can use the language and framework of your choice for frontend and backend
- If you run into CORS issues with favicons, the URL rather than an actual image is acceptable to display

### For mid-level or senior applicants
- We'd really like to see a Scala or Java backend for the application
- Dockerize the application
- Some sort of persistant storage of the previous requests, either client side or server side
- Basic unit testing

## Bonus points
- Add a feature to project - could be an expansion in anyway that you think makes sense
