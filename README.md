<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Smitmodi21/MovieFlix">
    <img src="assets/movie-libr.png" alt="Logo" width="80" height="80">
  </a>
  <!-- TABLE OF CONTENTS -->

  <h3 align="center">Movie Library</h3>
  <details>
  <summary>Demo credentials</summary>
  <code>
    user3@test.com 
    </code>
    <br/>
    <code>
    user3
  </code>
</details>
  <p align="center">
    A beautiful movie library application that allows users to explore and discover epic movies and create watchlists!
    <br />
    <br />
    <a href="https://frozen-stream-46804.herokuapp.com/">View Demo</a>
    ·
    <a href="https://github.com/Smitmodi21/MovieFlix/issues">Report Bug</a>
    ·
    <a href="https://github.com/Smitmodi21/MovieFlix/issues">Request Feature</a>
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

![Movie Library Screen Shot](https://user-images.githubusercontent.com/60734815/192861846-bf9637c3-6161-4b45-86fa-d20ea5dc63cf.png)


A MERN movie library application with a focus on user friendly UI and many functionalities.

Some of the features are:
* This project uses OMDB API to retrieve movie details. Lots of information available for every movie out there including plot details, actors, IMDb rating and much more.
* Secure authentication using JWT. I use my own API to store user details. New users can register too!
* Add movies to watchlist which you plan to watch in the future. Watchlist movie data gets stored in MongoDB and consumed using my own RESTful API.
* Users can create custom movie playlists. A playlist can either be public or private. Public playlist link is available on the playlist page once signed in. Public playlists can be viewed by anyone without any authentication!

Some more screenshots:
![Movie Library-Login Screen Shot](https://user-images.githubusercontent.com/60734815/192862974-e01163c9-0a1e-43aa-b704-f64c9ad294d0.png)

![Movie Library-Details Screen Shot](https://user-images.githubusercontent.com/60734815/192863113-2dc36cf2-c4a9-4f3b-ab1e-7f87c6746661.png)


<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

* [React.js](https://reactjs.org/)
* [Node.js](https://nodejs.dev/)
* [Express.js](https://expressjs.com/)
* [MongoDB](https://www.mongodb.com/)
* [Tailwind](https://tailwindcss.com/)

<p align="right">(<a href="#top">back to top</a>)</p>

### Installation
**Steps to Setup:**

1. Have node JS installed.
2. In the project root directory, run `npm install`
3. Next run `npm run client-install`
4. Change the MongoDB URL and secret key in `Movie-Libr\config\db.json`

**Steps to Run:**

1. In the project root directory, run `npm run dev`

