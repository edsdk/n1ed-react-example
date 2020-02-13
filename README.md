# Sample N1ED usage in React app 

This project is a sample how to create a new React app and integrate N1ED into it.

This will allow you to edit HTML easily with help of TinyMCE 5 and a lot of widgets provided by N1ED.

* N1ED website: [https://n1ed.com](https://n1ed.com)
* N1ED React NPM package: [https://www.npmjs.com/package/@edsdk/n1ed-react](https://www.npmjs.com/package/@edsdk/n1ed-react)
* N1ED React package sources: [https://github.com/edsdk/n1ed-react](https://github.com/edsdk/n1ed-react)

## How to run

Now to run it type in console:     
    
    npm run start
    
Then open into your browser [http://localhost:3000](http://localhost:3000) and check N1ED is started.

In your own project do not forget to set your own N1ED API key. This will link your N1ED to configuration you will visually build in [N1ED Dashboard](https://n1ed.com/dashboard).

## How it was created:

You can do the same when creating your own app.

Console commands:

    npm install -g create-react-app
    create-react-app n1ed-react-example
    cd n1ed-react-example
    npm i --save @edsdk/n1ed-react
   