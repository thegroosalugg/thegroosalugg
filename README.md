# 💫 About Me:
Hi I'm Victor.

### 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/vlog)
[![CodeWars](https://www.codewars.com/users/thegroosalugg/badges/micro)](https://www.codewars.com/users/thegroosalugg)

### 📽️ Check out my projects:

<details>
  <summary>&nbsp;👥&nbsp;<a href="https://friendface-lyart.vercel.app//">Friendface</a></summary>
  <p>
    This is the first REST API I developed after learning Node and Express. It's a small social media example where users can add/remove friends, create posts, reply 
    to others, and chat with added friends. In-app notifications are sent for friend requests, replies, and new messages.
    I built the full stack using MERN, without TanStack, Context, or Redux—only effects and custom hooks. Authentication data is fetched at the top level and prop- 
    drilled throughout. While query/state management libraries simplify development, relying solely on useEffect deepens your understanding of React’s lifecycle. 
    This approach also requires careful handling to prevent unnecessary requests, especially when combined with AnimatePresence exit animations, which can retrigger 
    effects on unmount. Check out web dev tools to view the logs.                                               
  </p>
  <pre><code>
    Render's servers will hibernate after inactivity and may take a couple of minutes to wake up. 
    Images are saved to File System using Multer. They can be uploaded for demo purposes but will be deleted by the server when it sleeps.
  </code></pre>
  <details>
    <summary>Tech Stack</summary>
    <pre><code>
      const techStack = {
        frontend: ['SCSS', 'React', 'TypeScript'],
         backend: ['Node', 'Express'],
       libraries: {
               react: ['React Router', 'Framer-Motion', 'Font Awesome', 'Socket.IO Client'],
                node: ['BSCrypt', 'DotENV', 'Express Validator', 'JSONWebToken', 'Mongoose', 'Multer', 'Socket.IO'],
                  },
        database: 'MongoDB',
      deployment: ['Vercel', 'Render'],
      };
    </code></pre>
  </details>
   <details>
    <summary>About</summary>
    <ul>
      <h3>MERN Stack Social Media Project</h3>
      <li>Server & Client routes both protected</li>
      <li>No Tanstack/Context/Redux - custom hooks and useEffect only</li>
      <li>Receive notifications for chats, friend requests & post replies</li>
      <li>New routes fetch initial data and handle all updates with sockets</li>
      <li>Lots of reusable, modular components which reduce codebase</li>
      <li>Server controllers capable of handling requests from different endpoints</li>
      <li>Responsive for desktop & mobile. Alternate landscape nav layout.</li>
      <li>Clean & logging on server & client. See in web tools for client.</li>
    </ul>
  </details>
</details>

<details>
  <summary>&nbsp;🛒&nbsp;<a href="https://d-bay.onrender.com/">D-Bay</a></summary>
  <p>
    At first glance, this app may seem similar to my previous project, E-Harbour, which is reflected in the name. However, the focus of this project is quite     
    different. In my previous project, I was responsible for the frontend. With this project, I took on the entire backend development myself, bringing a stronger        emphasis on validation, handling edge cases, and route protection. Although I also worked on the frontend, I used EJS to keep the project a cohesive, server-side     application. The backend was written with TypeScript, which is compiled by Render.com and dynamically changes the static paths for production so that same assets     can be re-used by the nested JavaScript App.
  </p>
  <pre><code>
    During development, the password reset emails were configured to fire from my personal GMail to myself. 
    Unfortunately, during production, sending emails to external addresses is limited without a registered business. 
    During production this is skipped and the request redirects you directly to the link you would receive in an email. 
    This ia a demo app, as such you should only input dummy data.
  </code></pre>
  <details>
    <summary>Tech Stack</summary>
    <pre><code>
      const techStack = {
        frontend: ['EJS', 'SCSS'],
         backend: ['Node', 'Express'],
       libraries: ["bcryptjs", "connect-mongo", "dotenv", "express-session", "express-validator", "mongoose", "multer", "nodemailer", "stripe"],
      deployment: 'Render',
      };
    </code></pre>
  </details>
   <details>
    <summary>About</summary>
    <ul>
      <h3>EJS Express Free-ads Project</h3>
      <li>Sessions retain non-sensitive user submitted data on invalidated form submissions</li>
      <li>All routes protected from unauthorised access</li>
      <li>CSRF protection with custom middleware</li>
      <li>Multer configured to store then clean submitted files. This ensures users do not need to re-upload when validation fails</li>
      <li>First line express validator, backed up by final front mongoose validator, both fed back to user</li>
      <li>EJS follows React concept. A single template can handle several views.</li>
      <li>Dynamic GET routes ensure to render correct data based on data received</li>
      <li>STRIPE Demo [use 4242] handles checkout payments</li>
    </ul>
  </details>
</details>

<details>
  <summary>&nbsp;💬&nbsp;<a href="https://geschwindigkeitsbegrenzu-a89a6.web.app">Geschwindigkeitsbegrenzung</a></summary>
  <p>
    While studying for my B2 German language course, an important theme was remembering which preposition pairs with which verb. In order to help me memorise them, I     decided to make a quick time based game. My original plan was to have AI fill my database with sentences, however it did not quite generate the kind of ideas I       had envisioned. Additionally, I saw that I am more likely to remember the question, than the verb-preposition pairings. As such I decided to develop a random         sentence generator. The sentences have similar structures, and due to RNG will not be memorable, forcing you to focus on the verbs instead of the questions. Some     of these sentences are unlikely to be heard in a typical German conversation, but do add a touch of humour and do a good job in remaining gramatically correct. 
  </p>
  <details>
    <summary>Tech Stack</summary>
    <pre><code>
      const techStack = {
        frontend: ['CSS', 'React', 'TypeScript'],
       libraries: ['Framer-Motion', 'React Router', 'Font Awesome'],
      deployment: 'Firebase',
      };
    </code></pre>
  </details>
   <details>
    <summary>About</summary>
    <ul>
      <h3>Time Based React Quiz</h3>
      <li>Difficulty select affects time remaining, score gained, lives & required score to get item</li>
      <li>Score based items allow user to pause timer</li>
      <li>Records high scores, along with difficulty tried</li>
      <li>Wordbook shows in game verbs, DAT/ACC cases, and Eng & Ru translations</li>
      <li>Sentence generator differentiates regular, irregular, reflex, separable & stative verbs</li>
      <li>Runs on desktop, but aimed at mobile. Alternate landscape/portrait layouts</li>
      <li>Clean, well-written custom hook handles all game logic</li>
    </ul>
  </details>
</details>

<details>
  <summary>&nbsp;⚓&nbsp;<a href="https://e-harbour.vercel.app">eHarbour</a></summary>
  <p>
    The original project that I collaborated on can be found here: <a href="https://github.com/Iyayi2/comeGetMe">comeGetMe</a>. I wrote all of the Frontend using         React & TypeScript. After completing the original project, I cloned my own version where I can manage my own DB & deployment. 
  </p>
  <pre><code>
    Render's servers will hibernate after inactivity and may take a couple of minutes to wake up. 
    No requests are sent on the homepage, please navigate to any other route. 
    A page refresh might be needed if the server does not wake up. 
    Images are saved to File System using Multer. They can be uploaded for demo purposes but will be deleted by the server when it sleeps.
  </code></pre>
  <details>
    <summary>Tech Stack</summary>
    <pre><code>
      const techStack = {
        frontend: ['SCSS', 'React', 'TypeScript'],
         backend: ['Node', 'Express'],
       libraries: {
               react: ['React Router', 'React Helmet', 'Framer-Motion', 'Font Awesome'],
                node: ['BSCrypt', 'CORS', 'DotENV', 'Express Validator', 'JSONWebToken', 'Mongoose', 'Multer'],
                  },
        database: 'MongoDB',
      deployment: ['Vercel', 'Render'],
      };
    </code></pre>
  </details>
   <details>
    <summary>About</summary>
    <ul>
      <h3>MERN Stack Free-ads Project</h3>
      <li>2-Man Team Project - I created all Frontend with React & TypeScript</li>
      <li>All elements animate to server responses</li>
      <li>Live Chat functionality</li>
      <li>All client requests handled by a modular and clean custom hook</li>
      <li>Original Backend ran Session authentication. I converted my version to JWT to escape 3rd party cookie limitations</li>
      <li>Great responsiveness on all devices. Used sticky nav but ensured it does not steal the page on high zoom</li>
    </ul>
  </details>
</details>

<details>
  <summary>&nbsp;☄️&nbsp;<a href="https://andromeda-1649b.web.app">Andromeda</a></summary>
  <p>
    My first React Project after completing a course on Udemy.com. Project written in TypeScript and aims to cover your staple web development features such as cart      logic, bookings & account management.
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
    <summary>About</summary>
    <ul>
      <h3>Static React Space Themed Project</h3>
      <li>Covers Cart Logic, Bookings, User Account management</li>
      <li>Different Frontend styles for each Page: ensures each list offers something new</li>
      <li>Data storage managed with Redux & localStorage</li>
      <li>Custom react hook covers form validation, ensures booked dates cannot be re-used etc.</li>
      <li>Showcases some fun animations & interactive Solar System page using Framer Motion</li>
    </ul>
  </details>
</details>

<details>
  <summary>&nbsp;🏰&nbsp;<a href="https://github.com/thegroosalugg/CastleCarnage">CastleCarnage [CLI game]</a></summary>
  <p>
    With the aim to improve my general coding I wrote a CLI game in Ruby to run in the terminal. To run it, you must download the code from GH, ensure you have Ruby      installed, head to root directory and run "ruby interface.rb"
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
    <summary>About</summary>
    <ul>
      <h3>Solo CLI Text based Game</h3>
      <li>Display using ASCII art</li>
      <li>ANSI escape codes add color</li>
      <li>Program runs until user quits. Replay is possible</li>
      <li>Attack random generated monsters, find items in rooms, level up possible, RPG format</li>
      <li>Easy to read & well organised code structure</li>
    </ul>
  </details>
</details>

<details>
  <summary>&nbsp;🪙&nbsp;<a href="https://github.com/thegroosalugg/TreasureKeeper">TreasureKeeper [code only]</a></summary>
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
    <summary>About</summary>
    <ul>
      <h3>2nd Project at Le Wagon</h3>
      <li>Created in a Team of 4</li>
      <li>Used Ruby on Rails for the backend</li>
      <li>I wrote all the frontend using ERB, Bootstrap, & CSS</li>
      <li>Developed in 3 days of coding</li>
    </ul>
  </details>
</details>

<details>
  <summary>&nbsp;🚀&nbsp;<a href="https://github.com/thegroosalugg/MySpaceShip">MySpaceShip [code only]</a></summary>
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
    <summary>About</summary>
    <ul>
      <h3>Initial Project at Le Wagon</h3>
      <li>Created in a Team of 4</li>
      <li>Used Ruby on Rails for the backend</li>
      <li>I wrote all the frontend using ERB, Bootstrap, & CSS</li>
      <li>Developed in 4 days of coding</li>
    </ul>
  </details>
</details>
