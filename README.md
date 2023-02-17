<div align="center">
  <img src="https://user-images.githubusercontent.com/94204560/218552485-cc3545f5-b588-493a-9331-0c681f66544a.png" width=20% height=20%>
  <h1>Dplace</h1>
 </div>

 
Dplace website is an innovative web application that enables users to share their experiences through photos and locations for others to see and visit. Creating an account on the website opens the door for users to share places and engange with other people, the website gives users the ability to view each location on Google Maps, comment, like, and share posts, Dplace creates a dynamic and interactive community of explorers. Join us on our journey to see the beauty of the world through each other's experiences.

</br>

<div align="center">
  <a href='https://dplace-3d5f4.web.app/api/homepage?utm_source=GitHub&utm_medium=readme&utm_campaign=well_app_readme'>
      <img src='https://img.shields.io/badge/HOMEPAGE-white?style=for-the-badge'>
  </a>
</div>

![home](https://user-images.githubusercontent.com/64949957/159116089-cfc2b4c5-dc7d-4d4b-a0c8-668f89ce5412.png)

<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/64949957/159116105-15b9425c-1fec-4a52-84ba-cf97eef93891.png" alt="mockup" /></td>
    <td><img src="https://user-images.githubusercontent.com/64949957/159116112-1c7dec3e-0f3a-45a8-83d3-6d6b9ee1d5de.png" alt="mockups" /></td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/64949957/159116115-46f15626-372d-4349-8ef4-a04a70600dcc.png" alt="mockup" /></td>
    <td><img src="https://user-images.githubusercontent.com/64949957/159116118-ac3d261b-eb50-4a7b-a8e6-cd1a0f5720de.png" alt="mockups" /></td>
  </tr>
</table>

</br>

# 🚩 Table of Contents

- [Features](#-features)  
- [Tech Stack](#-tech-stack)
- [Usage](#-clone-or-download)
- [Contact](#-contact)

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

# 👨‍💻 Tech Stack

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

</br>

# ✔️ Deployed On

**Frontend:**

![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)

**Backend:**

![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)

 </br>

# 🧑‍💻 Clone or download

```terminal

$ git clone https://github.com/AndersonGrisalesV/Dplace
$ npm # or yarn i

```

## Usage (run fullstack website on your machine)

**Prerequisites:**

<div align="left">
   <a href='https://nodejs.org/en/download/?utm_source=GitHub&utm_medium=readme&utm_campaign=well_app_readme'>
  <img src='https://img.shields.io/badge/Node.js-43853D?style=for-the-badge'>
 </a>
  
  <a href='https://nodejs.org/en/download/package-manager/?utm_source=GitHub&utm_medium=readme&utm_campaign=well_app_readme'>
  <img src='https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge'>
 </a>
  
  <a href='https://www.mongodb.com?utm_source=GitHub&utm_medium=readme&utm_campaign=well_app_readme'>
  <img src='https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge'>
 </a>
  
 </div>
 
 </br>

:ledger: Note: To ensure the client and server communicate with each other, they must run simultaneously in separate terminal sessions.

 </br>

**1. Install dependencies**

```

$ cd (Project folder)

$ npm # or yarn i

 
```

 </br>

**2. Create variables.env for the frontend file and replace values with yours**

```

REACT_APP_GOOGLE_API_KEY=_"google_maps_api_key"
REACT_APP_BACKEND_URL="backend_endpoint" //http://localhost:3000


```

</br>

**3. Create variables.env for the backend file and replace values with yours**

```

CLOUD_NAME="cloduinary_name"
CLOUD_KEY="cloudinary_key"
CLOUD_KEY_SECRET="cloudinary_secret_key"
GOOGLE_MAPS_TOKEN="google_maps_token"
MONGO_USER="db_mongo_user"
MONGO_PASS="db_mongo_pass"
MONGO_DATABASE="db_mongo_database"
DB_PASSWORD="db_mongo_password"
JWT_KEY="jwt_secret_key"


```

 </br>
 

**4. Run project**

```

npm run start

```

</br>

---

</br>

# 🖌️ Contribution

If you have any suggestions or have discovered any bugs, please don't hesitate to open an issue or a pull request I will review it as soon as possible.

</br>

#	📭 Contact 

If you want to contact me, you can reach me through below handle

![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white) 

grisalesvargasanderson@gmail.com

</br>

# 📜 License

This project is licensed under the [MIT licensed](https://github.com/facebook/react/blob/main/LICENSE).

</br>

# ⚠️ Images Copyright Claim

The images used in this project are the property of their respective creators/authors. No claim of ownership is made by the developer or users of this project.

</br>

# 🙋‍♂️ Thanks

Thank you for taking the time to check out this project! I appreciate your interest and hope you find it interesting. If you have any feedback or suggestions, please don't hesitate to let me know.

---




