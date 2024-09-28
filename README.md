# 💫 About Me:
Hi I'm Victor.

### 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/vlog)
[![CodeWars](https://www.codewars.com/users/thegroosalugg/badges/micro)](https://www.codewars.com/users/thegroosalugg)

### 📽️ Check out my projects:

<details>
  <summary>&nbsp;<a href="https://e-harbour.vercel.app">eHarbour</a></summary>
  <p>
    The original project that I collaborated on can be found here. <a href="https://github.com/Iyayi2/comeGetMe">comeGetMe</a>. I was responsible for writing the entire frontend for this app with React and 
    Typescript. Upon completing this project, I wanted to deploy my own personal copy where I could make my own independent changes and have control of the DB and deployment. Any further improvements that I made 
    to the frontend in my personal copy, I also implemented in the original.
  </p>
  <pre><code>
    Render's servers will hibernate after inactivity and may take a couple of minutes to wake up. 
    No requests are sent on the homepage, please navigate to any other route. 
    A page refresh might be needed if the server does not wake up. 
    Any images uploaded will be erased once the server sleeps.
  </code></pre>
  <details>
    <summary>Tech Stack</summary>
    <pre><code>
      const techStack = {
        frontend: ['SCSS', 'React', 'TypeScript'],
         backend: ['Node', 'Express'],
       libraries: {
               react: ['React Router', 'React Helmet', 'Framer-Motion', 'Font Awesome'],
                node: ['BSCrypt', 'CORS', 'DotENV', 'Express Validator', 'JSONWebToken', 'Mongoose', 'Multer', 'Socket.IO'],
                  },
        database: 'MongoDB',
      deployment: ['Vercel', 'Render'],
      };
    </code></pre>
  </details>
   <details>
    <summary>What I learned</summary>
    <p>
      This project was a valuable learning experience, allowing me to further hone my React skills within a full-stack environment using MongoDB and Node/Express. I gained a better understanding of the backend's       role in web development and how it interacts with the frontend. I was able to modify backend controllers to control data flow and reduce fetch requests, keeping both sides cleaner. Though I considered            using Tanstack for data fetching, I opted to rely on React’s custom hooks, designing versatile ones that handle various data types and state updates without page reloads. The original project used                session-based authentication, which caused issues on some browsers due to third-party cookie restrictions. To improve user experience, I replaced session-based authentication with JSON Web Token (JWT)            authentication in my personal version, which required significant changes to both the frontend and backend. This challenge was highly rewarding, and I was pleased with the result.
    </p>
  </details>
</details>

<details>
  <summary>&nbsp;<a href="https://andromeda-1649b.web.app">Andromeda</a></summary>
  <p>
   This was my first solo project after completing Maximilian Schwarzmüller's React course, serving as a playground to practice my React skills. While I had basic knowledge of CSS, this project allowed me to        improve by learning through writing, without taking any additional CSS courses. The inspiration came from my Le Wagon MySpaceShip project, as I wanted to reuse the spaceship images. The goal was to implement     popular web development features such as store cart logic, a booking system with full date validation, account management, modals, custom hooks, and a landing page featuring animations—a hobby of mine. I         created an interactive solar system with PNGs and more advanced animations. This is a static project using Redux and localStorage to simulate a backend. Item data is randomly generated on app launch and saved    to storage, so it differs if launched on different browsers or if site data is cleared.
  </p>
  <details>
    <summary>Tech Stack</summary>
    <pre><code>
      const techStack = {
        frontend: ['SCSS', 'React', 'TypeScript'],
       libraries: ['React Router', 'Redux', 'Framer-Motion', 'React Helmet', 'React Datepicker', 'Faker', 'Font Awesome'],
      deployment: 'Firebase',
      };
    </code></pre>
  </details>
   <details>
    <summary>What I learned</summary>
    <p>
     Building this project helped me further develop my React and CSS skills, applying what I had learned over the past several months. I created more complex animations, custom hooks, gained a better                 understanding of Redux, and explored different routing methods while making the site responsive. I challenged myself not to reuse code across routes, experimenting with each new one. For example, I used the      same component for the spaceship grid and footer, while the user page employed modals and Redux to update list data simultaneously. The validation logic is managed by a complex custom hook that keeps the         components clean. The store page, which was one of the last pages, used unique CSS grid tricks to showcase items in a fresh way.
    </p>
  </details>
</details>

<details>
  <summary>&nbsp;<a href="https://react-universe.web.app">ReactUniverse</a></summary>
  <p>
    This was a mini React project I deployed while learning React, as part of Maximilian Schwarzmüller's React course. I recently explored Framer Motion and used this project as a playground to practice it,          while also applying some of the React concepts taught in the course. The section included images of interesting locations on Earth, and I expanded on this by creating a small solar system using CSS.
  </p>
  <details>
    <summary>Tech Stack</summary>
    <pre><code>
      const techStack = {
        frontend: ['CSS', 'React', 'JavaScript'],
         library: 'Framer-Motion',
      deployment: 'Firebase',
      };
    </code></pre>
  </details>
   <details>
    <summary>What I learned</summary>
    <p>
      This project was an entry-level playground for experimenting with Framer Motion, alongside React concepts like Render Props and Compound Components. Although I structured the codebase similarly to React          Router, the app remained a true single-page application (SPA) without any actual routing.
    </p>
  </details>
</details>

<details>
  <summary>&nbsp;<a href="https://github.com/thegroosalugg/CastleCarnage">CastleCarnage</a></summary>
  <p>
    This Ruby-based text-only CLI game was one of those projects where I started coding and just kept going. I enjoyed building a playful, humorous experience with a heavy emphasis on ASCII art and emojis, all 
    displayed in color in the terminal.
  </p>
  <details>
    <summary>Tech Stack</summary>
    <pre><code>
      const techStack = {
           language: 'ruby',
        environment: 'terminal',
          execution: 'ruby interface.rb',
      };
    </code></pre>
  </details>
   <details>
    <summary>What I learned</summary>
    <p>
      I started with hard-coded elements to see quick results, but the real learning came through refactoring. Turning repetitive blocks into reusable generators 
      taught me the value of clean, efficient code. I also developed my own method for improving readability, aligning similar code elements—such as operators and 
      constants—in columns to make the structure more intuitive at a glance. Despite being a simple terminal game, I creatively used ASCII art, emojis, and text 
      characters to bring the game to life.
    </p>
  </details>
</details>

<details>
  <summary>&nbsp;<a href="https://github.com/thegroosalugg/TreasureKeeper">TreasureKeeper</a></summary>
  <p>
    I'm sharing a couple of my earlier Le Wagon projects that were initially deployed by a contributor. While I won’t be revisiting or 
    redeploying them, they were valuable learning experiences. Here are the GitHub links for a quick overview.
  </p>
  <details>
    <summary>Tech Stack</summary>
    <pre><code>
      const techStack = {
        frontend: ['SCSS', 'Bootstrap'],
         backend: 'Ruby on Rails',
        database: 'PostgreSQL',
      deployment: 'Heroku',
      };
    </code></pre>
  </details>
   <details>
    <summary>What I learned</summary>
    <p>
      I focused on mobile-first development, refining my frontend skills with SCSS and Bootstrap. This project helped me understand the nuances of designing for 
      mobile while still working within a tight 4-day timeline.
    </p>
  </details>
</details>

<details>
  <summary>&nbsp;<a href="https://github.com/thegroosalugg/MySpaceShip">MySpaceShip</a></summary>
  <p>
    I'm sharing a couple of my earlier Le Wagon projects that were initially deployed by a contributor. While I won’t be revisiting or 
    redeploying them, they were valuable learning experiences. Here are the GitHub links for a quick overview.
  </p>
  <details>
    <summary>Tech Stack</summary>
    <pre><code>
      const techStack = {
        frontend: ['SCSS', 'Bootstrap'],
         backend: 'Ruby on Rails',
        database: 'PostgreSQL',
      deployment: 'Heroku',
      };
    </code></pre>
  </details>
   <details>
    <summary>What I learned</summary>
    <p>
      This was my first project as part of a team of four at Le Wagon. We had a tight deadline of about four days for coding. I was 
      responsible for the frontend, primarily using Bootstrap along with ERB and JavaScript for dynamic elements. The project was a fun 
      platform where users could rent and post their own spaceships. The backend allowed account creation, viewing and renting ships, 
      and posting listings. This experience helped me learn by doing, enabling me to write large amounts of code quickly under pressure 
      while integrating creative ideas and feedback from my teammates.
    </p>
  </details>
</details>
