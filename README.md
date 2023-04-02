# ERD Diagrams

# Post

|     Object      |      Relation      |
| :-------------: | :----------------: |
|      \_id       |       String       |
|     userId      |     String Ref     |
|    firstName    |       String       |
|    lastName     |       String       |
|    location     |       String       |
|   description   |       String       |
| userPicturePath |     String Ref     |
|   picturePath   |     String Ref     |
|      likes      | Object<String Ref> |
|    comments     |   Array<String>    |

# User

|    Object     |   Relation    |
| :-----------: | :-----------: |
|     \_id      |    String     |
|   firstName   |    String     |
|   lastName    |    String     |
|    friends    | Array<Object> |
|     email     |    String     |
|   password    |    String     |
|  picturePath  |  String Ref   |
|   location    |    String     |
|  occupation   |    String     |
| viewedProfile |    Number     |
|  impressions  |    Number     |

# Friend (Sub Doc)

|   Object    |  Relation  |
| :---------: | :--------: |
|    \_id     |   String   |
|  firstName  |   String   |
|  lastName   |   String   |
| picturePath | String Ref |
| occupation  |   String   |
|  location   |   String   |

### I wanted to really challenge myself with this and test a lot of my knowledge with MERN on this project. Although it was a very long process, and lots of documentation, I think I am happy with where this project has gone. This is a complete, fullstack, responsive social media application using MERN.

### This app consists of a register page, with complete validation. Along with functionality to upload a user image for a user profile. You can register and then use that to sign in and enter your home page! On the home page there is a very clean looking website with a number of different widgets, the users information, capability to make posts, and the feed of the current user. From here, you can also like and dislike posts, you can view the comments as well! You can also add a friend to your friends list, and remove them if you want to.

### You can go to your friends or just random others pages and view their friends, their posts, and their likes! The coolest part though to me, is that you can also change the screen from light to dark mode!!

### If you are curious about the technologies I am using, I will be using the MERN stack of course, which is MongoDB, Express.js, React, and Node. For the frontend I used React as my framework, react-router for navigation, Formik and yup for form validation, Redux toolkit for state management, Redux persist for storage in local storage, and React dropzone for image uploads. For the backend, I used Node.js for my runtime, Express.js for my backend framework, Mongoose for managing my mongo database, JSON web token for authentication, and lastly, multer for file upload.
