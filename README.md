# custom-shopping-mall-service-api

## 1. Install API Blueprint Tools
To view API Blueprint locally, you will use aglio.

**Install Node.js**   

aglio is a Node.js-based tool, so you need to have Node.js installed. If you don't have Node.js installed, you can download it from the Node.js official website.

**Install Aglio**   

aglio is a tool for converting API Blueprint documents to HTML. Install it using npm:
```
npm install -g aglio
```
## 2. View Locally
Use `aglio` to serve the API Blueprint document locally.
```
aglio -i api.apib --server
```
By default, this command will start a server at localhost:3000. To use a different port, run:
```
aglio -i api.apib -s -p 4000
```
## 3. Convert to HTML
To convert the API Blueprint document to an HTML file, use the following command:
```
aglio -i api.apib -o api.html
```
This command will generate an api.html file.
