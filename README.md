<div align="center">
  <img src="https://user-images.githubusercontent.com/94204560/218552485-cc3545f5-b588-493a-9331-0c681f66544a.png" width=15% height=15%>
  <h1>Dplace</h1>
 </div>

 
Dplace website is an innovative web application that enables users to share their experiences through photos and locations for others to see and visit. Creating an account on the website opens the door for users to share places, and engange with other people, the website gives users the ability to view each location on Google Maps, comment, like, and share posts, Dplace creates a dynamic and interactive community of explorers. Join us on our journey to see the beauty of the world through each other's experiences."

</br>

<div align="center">
 <a href='https://dplace-3d5f4.web.app/api/homepage?utm_source=GitHub&utm_medium=readme&utm_campaign=well_app_readme'>
  <img src='https://img.shields.io/badge/HOMEPAGE-white?style=for-the-badge'>
 </a>
   </div>

</br>

# 🚀 Features

- Login/SignUp User Account
- Login SingIn With Email
- Update Profile Name/Email/Password/ProfilePicture
- Delete Own User
- Add New Posts
- Update Post Title/Description/Address/Image/PostDate
- Like/Unlike Posts
- Share Posts on Different Social Media platforms
- Search Posts by Title
- Delete Own Posts
- Add New Comments on Posts
- Update Comment Text/CommentDate 
- Delete Own Commments
- Map integration: Places shared by users are displayed on Google maps for easy navigation and visualization
- User profiles: Users can view their profile and all the posts they have shared and liked
- Cloudinary integration: Photos uploaded by users are stored using the Cloudinary platform

</br>

# 👨‍💻  Tech Stack

**Frontend:**

![reactjs](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)&nbsp;
![react-router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)&nbsp;
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![mui](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white)&nbsp;

**Backend:**

![nodejs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)&nbsp;
![expressjs](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)&nbsp;
![mongodb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)&nbsp;
![jwt](	https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)&nbsp;


**Cloud Storage:**

![Cloudinary](https://img.shields.io/badge/Cloudinary-blue?style=for-the-badge)


# :heavy_check_mark: Deployed On

**Frontend:**

![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)

**Backend:**

![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)

 </br>

---

# :warning: Images Copyright Claim

The images used in this project are the property of their respective creators/authors. No claim of ownership is made by the developer or users of this project.

---

</br>

# :technologist: clone or download
```terminal
$ git clone https://github.com/AndersonGrisalesV/Dplace
$ npm # or yarn i
```

## Usage (run fullstack website on your machine)

**Prerequisites:**

<div align="left">
 <a href='https://www.mongodb.com?utm_source=GitHub&utm_medium=readme&utm_campaign=well_app_readme'>
  <img src='https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge'>
 </a>
  
  <a href='https://nodejs.org/en/download/package-manager/?utm_source=GitHub&utm_medium=readme&utm_campaign=well_app_readme'>
  <img src='https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge'>
 </a>
  
  
  <a href='https://nodejs.org/en/download/?utm_source=GitHub&utm_medium=readme&utm_campaign=well_app_readme'>
  <img src='https://img.shields.io/badge/Node.js-43853D?style=for-the-badge'>
 </a>
  
  
 </div>
 
 ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)

notice, you need client and server runs concurrently in different terminal session, in order to make them talk to each other

1. Install dependencies

```
npm i && cd client && npm i && cd ..
```

2. Create variables.env file and replace values with yours

```
NODE_ENV=development
DATABASE="Mongodb Connection String"
JWT_KEY="secretkey"
EMAILUSER="example@gmail.com"
EMAILPASS="example"
HOST="your ip eg. http://192.168.0.14:5000"
ENABLE_SEND_EMAIL="true or false" // false if you don't want to set it up
TEST_DATABASE="testing db"
```

3. Go into `client/src/_services/socketService.js` and replace

```
window.location.hostname
```

with your local IP address on port 5000 eg.

```
192.168.0.14:5000
```

4. Run project

```
npm run dev
```


# Getting Started with Create React App 

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
