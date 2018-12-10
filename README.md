## Description

- A simple shopping cart built with React and Bulma CSS framework.  

- This project was bootstrapped with 
[Create React App](https://github.com/facebook/create-react-app).

- The PSD design has been made by: [thislooksgreat](https://thislooksgreat.net)

## Live preview 
you can test the application from [here](https://shopping-cart.douara.me/)

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## File Structure 
- Html index template: **public/index.html**
- Components reside in **src/components** folder. 
- Data in a form of an array can be found here: **src/data/data.js**, you can add more products as much as you want :) 
- style: the Bulma framework is imported using a CDN in the html template file, and the main style file can be found in **src/style.css**

## Deployment with Docker
You can easily deploy the application using docker, simply upload the content in **production_with_docker** to your server then run 
`docker-compose up -d`
the server will then build the image and run it in container exposed to the port 1892 on your host, you can can change that port from **docker-compose.yml**  file 
## Learn More about this workflow 
You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
