# Social Club - platform to make friends

## Introduction
Social Club is a dynamic platform designed to facilitate the formation of meaningful connections with individuals seeking to cultivate enjoyable friendships. Our innovative platform not only allows you to effortlessly expand your network of friends but also provides you with efficient tools to manage and organize your friend list. At Social Club, fostering a sense of amusement and camaraderie is at the forefront of our mission. With intuitive interface, you can easily share your thoughts, ideas, and experiences through posts, while encouraging active engagement from your friends. Their valuable insights and comments will enrich your interactions, sparking engaging discussions and fostering a sense of community.
Creating a personalized profile on Social Club offers you the opportunity to curate and showcase your unique personality and interests. Seamlessly tracking your activities and milestones becomes a breeze, ensuring that you can reflect upon and relish the experiences that shape your journey.
<br />

#
## Active Example
* Netlify.com(fronend): https://socialclub1.netlify.app
* Render.com(backend): https://socila-club-server.onrender.com
* Github Code Frontend: https://github.com/Artur-Vanivskyi/Social-prac-client.git
* Github Code Backend: https://github.com/Artur-Vanivskyi/Social-prac-server.git


## Technologies used
_Back end:_
1. Node
1. Express
1. MongoDB

_Font end:_
1. React (hooks, router, icons, dropzone etc...)
1. Material UI
1. Redux
1. Formik

<br />

## Features
### Details about functionality:
> The application offers the following functionality: creating a new user profile, which requires providing a first and last name, location, and occupation. Additionally, users can upload a profile picture using React Dropzone and multer for seamless file handling. The user is also required to provide an email and password during the profile creation process. All the user information is stored in MongoDB, and the backend is built using Node.js.
>  <br />
>  Once logged in, users have various options available to them. They can view their own profile, access their friend list, browse a list of posts, and create their own posts. When viewing a list of posts, users can like or unlike other users' posts, enabling them to interact with the content. The application also allows users to add or remove friends from their list and switch between light and dark modes for personalization. Users can navigate to their profile page exclusively or log out from the platform.
>  <br />
>   While creating a post, users are prompted to provide a description and upload an image, after which they can press a button to create the post. Redux is employed to manage state and ensure clean code organization. Material UI is utilized to create a professional, clean, and user-friendly UI design. The form data is validated using Yup, ensuring that the provided information is accurate and meets the required criteria.
>   <br />
>   Overall, the application offers a comprehensive set of features, leveraging modern technologies and frameworks to deliver an efficient and enjoyable user experience.


### Create Profile

![Create Profile](https://github.com/Artur-Vanivskyi/Social-prac-client/assets/106690298/83a19e57-17bb-48d4-94b2-4e93362aba3f)
<br />

### Login Profile

![Login Profile](https://github.com/Artur-Vanivskyi/Social-prac-client/assets/106690298/83fc4f56-bbd5-472d-8a83-9b7b80ac90a2)
<br />

### Profile page light and dark mode

![Light Mode](https://github.com/Artur-Vanivskyi/Social-prac-client/assets/106690298/7e739768-257a-47b6-986d-24500a206aab)

![Dark Mode](https://github.com/Artur-Vanivskyi/Social-prac-client/assets/106690298/78d6a2e5-a87b-4331-bb35-7c84211c77c6)
<br />

### Make a post
![Make Post](https://github.com/Artur-Vanivskyi/Social-prac-client/assets/106690298/fc49ac1a-6670-4150-aaba-165ea0803673)
<br />


### Installation
1. Fork and clone this repository.
2. Update the `./client/.env`
3. Update the `./server/.env` file with the connection URL's to your MongoDB database instance.
4. Run `npm install` to install project dependencies.
5. Run `npm start` to start your client and server in development mode.

