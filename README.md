# nlp-document-evaluator
_________________________________________________________________________________________________________________________
Web tool for running Natural Language Processing (NLP) website content.
-------------------------------------------------------------------------------------------------------------------------



Project prerequisites:  

* Webserver - Node

* Web application framework for routing - Express

* Build tool - Webpack.

* External script - Service Worker 

* External API - MeaningCloud Sentiment Analysis API 

* Testing - Jest

* Languages - HTML, JS, CSS

* Workbox

## Installation
Install Node and npm.
```
node -v
npm -v
```

1. Move to the project folder
```
cd <project directory>
```
2. Clone the repo
```
git clone <repo>
```
3. Install npm
```
npm install
```
4. Install loaders and plugins
```
# Choose the necessary installation for your development mode
npm i -D @babel/core @babel/preset-env babel-loader
npm i -D style-loader node-sass css-loader sass-loader
npm i -D clean-webpack-plugin
npm i -D html-webpack-plugin
npm i -D mini-css-extract-plugin
npm i -D optimize-css-assets-webpack-plugin terser-webpack-plugin
```
5. Sign up for an API key at [meaningcloud.com](https://www.meaningcloud.com/developer/create-account)

6. Configure environment variables using dotenv package
	1. Install the dotenv package
	```
	npm install dotenv
	```
	2. Create a new `.env` file in the root of your project
	3. Fill the `.env` file with your API key like this:
	```
	API_KEY=**************************
	```
7. Start the project

Command | Action
:------------: | :-------------:
`npm run build-prod` | Build project
`npm start` | Run project

8. Open browser at http://localhost:8081/
