# SFLE Knowledgebase

This project is in collaboration with the ASU School of Sustainability and Leuphana University in Lueneburg, Germany. 

## Running the Project

**Prerequisites**

These services must be installed:
- [Git](https://git-scm.com/downloads)
- [Heroku](https://devcenter.heroku.com/articles/heroku-cli)
- [Node.js](https://nodejs.org/en/download/)
- [NPM](https://www.npmjs.com/get-npm)
- [MongoDB](http://www.mongodb.org/)

**Get Started**

Clone or fork this repository to your local machine:
```
$ git clone https://github.com/panza8484/capstone-slfe-knowledgebase.git
```
Install the depencies with the following commands:
```
$ npm install
$ npm run client-install
```

**Development Mode**

For testing on `localhost`, create a file named `.env` in the root directory and set the database credentials as below:
```
MONGODB_URI=[mongodbURI]
```
1. `$ npm run dev` || `MONGODB_URI=[mongodbURI] npm run server`
2. Browsersync can be accessed through `localhost:5000`

**Production Mode**
1. `git add .`
2. `git commit -am "new commit"`
3. `git push heroku master`

## License

The contents of this repository are covered under the [MIT License](https://github.com/panza8484/capstone-slfe-knowledgebase/blob/master/LICENSE).
