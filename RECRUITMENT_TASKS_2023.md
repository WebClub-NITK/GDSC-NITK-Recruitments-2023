# Tasks

- It is perfectly fine if you have no experience in the field and trying it out for the first time. Please put in sincere efforts and try to learn from whatever you complete!
- Each Task has an ID, tags, mentor, description, tips and useful resources
- You can refer to the resources put up in each task to understand the concepts required to complete the task.
- Feel free to reach out to the mentors for any assistance you need.
- Mention the Task ID attempted in the README of your private GitHub repository.
- Read the instructions, evaluation criteria and submission details [here](./README.md)

### Table of contents

| Task                                                        | Difficulty |
| ----------------------------------------------------------- |------------|
| [Chrome Tabs Organiser](#task-id-chrome-tabs-organiser)     | Medium |
| [VoicePen](#task-id-voicepen)                               | Medium |
| [WebClub Discord ChatBot](#task-id-webclub-discord-chatbot) | Medium |
| [SportsTracker](#task-id-sportstracker)                     | Easy |
| [Leetcode Clone](#task-id-leetcode-clone)                   | Hard |
| [Splitwise Clone](#task-id-splitwise-clone)                 | Hard |
| [GitHub GraphQL API](#task-id-github-profile-using-graphql-api)| Medium |
| [CollabPro](#task-id-collabpro)        | Hard |
| [Space Exploration App](#task-id-space-exploration-app)| Easy |
| [Department Website Revamp](#task-id-department-website-revamp) | Easy |
| [Random Character Generator](#task-id-random-avatar-generator)| Easy |
| [Meme Feed](#task-id-meme-feed)                             | Hard |
| [MediTracker](#task-id-meditracker)                             | Medium |
| [Intelligent AutoZoom Camera](#task-id-intelligent-autozoom-camera) | Medium |

| Inter-SIG Task                               | Associated SIG  | Difficulty |
| ---------------------------------------------|------------- |------------|
| [NFT Minter](#task-id-nft-minter)            | Systems      | Medium |
| [File Manager](#task-id-file-manager)        | Systems      | Hard |


## Task ID: Chrome Tabs Organiser

#### `Chrome Extension`

Mentors: [Mardav Gandhi](https://github.com/marcdhi) ([+91 9033398366](https://wa.me/919033398366)), [Parth Mittal](https://github.com/mittal-parth) ([+91 9411327838](https://wa.me/919411327838))

Difficulty: `Medium`

### Description

Currently, Chrome offers a built-in feature for grouping tabs, allowing users to organize them manually, assign names, and assign colours. However, in this task, you will be creating a Chrome Extension that automates this process, making tab management more efficient.

Follow the steps below to complete this challenge:

1. Create a Chrome Extension that automatically groups tabs from the same website under a single bar. Ensure that the extension recognizes the context by naming the bar after the visited website or page automatically.
2. Implement a feature to assign colours to tabs that match the theme of the respective websites for visual organization.

### Bonus Feature:

Implement context recognition from different websites and then group them together automatically. For example, if the user is browsing `web3` content but from different websites, group all of them under the name of a `web3` tab with a default colour.
**NOTE**: Implementing this feature would result in this task being treated as a `Hard` task.

### Useful resources:

These links might give you a direction

- [Getting Started with Chrome Extensions Development](https://developer.chrome.com/docs/extensions/mv3/getstarted/)
- [Understanding manifest.json](https://www.freecodecamp.org/news/building-chrome-extension/)
- [Chrome Tabs API](https://developer.chrome.com/docs/extensions/reference/tabs/)

### Tips

1. Begin by understanding the basics of Chrome Extensions development. Refer to the Chrome Extension Documentation for a solid foundation.
2. Familiarize yourself with the Tabs API to manipulate and manage tabs programmatically.
3. Explore the concept of Contextual Identity to handle contextual tab grouping effectively.

## Task ID: VoicePen

#### `AI`, `Full Stack Web Development`, `APIs`

Mentors: [Mardav Gandhi](https://github.com/marcdhi) ([+91 9033398366](https://wa.me/919033398366)), [Parth Mittal](https://github.com/mittal-parth) ([+91 9411327838](https://wa.me/919411327838))

Difficulty: `Medium`

### Description

Imagine a scenario where you have lots to speak about. You would end up recording a voice note and sharing it. But what if you could convert this into precise text, that doesn't contain the 'umms' and 'aahs' and gives a crisp summary conveying the most important ideas. Your task is to create an application that takes their voice input, converts it into text, and enhances the text's presentation by summarizing it and structuring it according to their requirements.

Follow the steps below to complete this challenge:

1. Implement easy recording functionality, allowing users to start recording by clicking a button on the screen.
2. On submitting, the application should transcribe spoken words into text, eliminating repeated content, filler words, and restructuring the text for readability.
3. Use Text Summarisation APIs to structure the above generated text into a certain format, using prompt engineering if needed.
4. The final output should be the prettified text.

Note: The focus here is not the UI or the ML model. The UI can be kept relatively simple. The feature set can also be kept minimal by skipping authentication, state saving, etc. The usage of readily available APIs is encouraged and preferred over ML techniques.

### Bonus Feature(s):

1. Create a Chrome extension for recording, enabling users to record from any browser tab.
2. Enable file uploads, where users can upload audio files and text notes for transcription and rewriting.
3. Implement custom styles, allowing users to define writing styles, including a custom style that mimics their own writing style (use API's like GPT-3.5)

**NOTE**: Implementing any of the above features would be sufficient, resulting in this task being treated as a `Hard` task.

### Useful resources:

These links might give you a direction

- [Using React.js to record Audio](https://blog.logrocket.com/how-to-create-video-audio-recorder-react/#audio-recorder-component)
- [Record Audio in Javascript](https://ralzohairi.medium.com/audio-recording-in-javascript-96eed45b75ee)
- [Voice-to-Text API](https://cloud.google.com/speech-to-text)
- [Free Summarisation API to get started with](https://oneai.com/)
- [Hugging Face API](https://huggingface.co/inference-api)
- [Using Axios to make API Calls](https://blog.logrocket.com/how-to-make-http-requests-like-a-pro-with-axios/)
- [Hugging Face Access Tokens](https://huggingface.co/docs/hub/security-tokens)
- [Postman - test and create APIs](https://www.postman.com/)

### Tips

1. Start by exploring existing speech recognition libraries and APIs to handle voice input.
2. Leverage summarization APIs to enhance the text quality without the need for complex machine learning models.
3. Ensure that the final output is clear and maintains the core content and meaning from the original voice input.

## Task ID: WebClub Discord ChatBot

#### `Discord Bot` `APIs` `Full Stack Development`

Mentors: [@Ayush Kumar Singh](https://github.com/Ayush4345) ([+91 9334352548](https://wa.me/919334352548)), [@Abhiraj Mengade](https://github.com/abhiraj-mengade) ([+91 7709439025](https://wa.me/917790439025))

Tag: `Medium`

### Description

Discord is a popular communication platform designed for creating communities. Gamers widely use it, but it's also a versatile tool for various interest groups, businesses, and developers. A Discord bot is a software application that automates tasks within Discord servers. They can be used for moderation, utilities, games, or music playback, enhancing server functionality.

In this task, you are expected to create an interactive Discord bot that displays information about [Web Enthusiasts' Club](https://webclub.nitk.ac.in/). The following things should be covered:
- Informing about Upcoming Events of WEC
- Information on SIGs
- Past Events in each SIG
- Non Technical Events
- Information of Members

 Users should be able to access the information by using commands, just like how it is done in bots like mee6 and arcane. You can explore the discords bot [here](https://top.gg/).

Follow the steps below to complete this challenge:

1. Use a database to store the information about **Web Enthusiasts' Club**.
2. Make a simple interface to insert and update in the database.
3. Create an interactive Discord Bot using APIs provided by Discord to display information related to Web Club

\*\*Note: Use dummy data wherever applicable

### Bonus Feature:

1. Modify the bot to enable natural language interaction, allowing users to ask questions like 'What is the upcoming event?' or 'Who is the convenor of the web club?' instead of using commands.

### Useful resources:

- [Build a Discord Bot With Python](https://betterprogramming.pub/coding-a-discord-bot-with-python-64da9d6cade7)
- [Building your first Discord app](https://discord.com/developers/docs/getting-started)
- [Supabase](https://supabase.com/)
- [Building a CRUD App with Supabase and Express](https://medium.com/@heshramsis/building-a-crud-app-with-supabase-and-express-a-step-by-step-guide-for-junior-developers-81456b850910)
- [Embedchain is a framework to create LLM-powered bots over any dataset](https://github.com/embedchain/embedchain)

### Tips

1. You can use any language/technology/framework of your choice.
2. Any useful additional/interesting feature will have bonus points.
3. Explore using frameworks to make LLM-powered bots over your dataset.


## Task ID: SportsTracker

#### `APIs`, `Web Development`, `App Development`, `UI/UX`


Mentors: [@Fahim Ahmed](https://github.com/ahmedfahim21) ([+91 8861054452](https://wa.me/918861054452)), [@Muthukumar](https://github.com/BenzeneAlcohol) ([+91 8921472523](https://wa.me/8921472523))

Difficulty: `Easy`

### Description

Your task is to build a website or a mobile app that allows users to track their favourite sports teams. This application will use the [SportRadar API](https://developer.sportradar.com/docs/read/Home#getting-started) to collect schedules, results, and other information about the user's favourite sports teams. 

Follow the steps below to complete this challenge:

1. Develop a responsive frontend using any framework of your choice.
2. Use the SportRadar API to fetch data about sports teams, including schedules, match results, team details, etc.
3. Store user data like their favourite teams in browser cookies/local storage(so there is no need to use a database).

In short, the application should allow users to:
   - Search for sports teams using the SportRadar API.
   - Add and remove sports teams from their list of favourites.
   - View detailed information about their favourite teams, including schedules, match results, points table, players, etc

### Useful Resources

- [SportRadar API Documentation](https://developer.sportradar.com/docs/read/Home#getting-started)
- [Working with APIs - Postman](https://learning.postman.com/docs/getting-started/first-steps/sending-the-first-request/)
- [How to store data in browser](https://blog.bitsrc.io/different-ways-to-store-data-in-browser-706a2afb4e58)

### Tips

1. Explore the SportRadar API using the Postman collection provided in the Documentation.
2. Try to make it for a single sport first; you may then try having multiple sports.
3. The focus should be on building a good User Interface. Try to have charts, tables, logos, etc.



## Task ID: Leetcode Clone
#### `Web Development`, `Code Execution`, `Backend Development`, `API Integration`

Mentors:  [@Shubham-Rasal](https://github.com/Shubham-Rasal) ([+91 7349784770](https://wa.me/917349784770)),  [@sujay000](https://github.com/sujay000) ([+91 94219 68047](https://wa.me/919421968047))
Tag: `Hard`

### Description

Create a simple [Leetcode](https://leetcode.com/) clone that allows users to create an account and then solve preset problems in more than one programming language.

### Tasks
1. **Frontend Development**
   - Create a page with a list of questions available to solve.
   - Implement necessary authentication and authorization for users to access individual questions
   - Incorporate any open-source code editor for easy coding

2. **Backend Development**
   - Develop a backend that is responsible for handling user requests
   - Functionality includes authentication and user data storage.
   - The most important feature is to incorporate a code execution engine, which will be responsible for executing the user-submitted code, comparing results, and returning the output.
   - This code execution feature can be built from scratch or can be done by using existing APIs (recommended).

### API Options
You can use the following meme generator API for this project:
- [Piston API](https://piston.readthedocs.io/en/latest/api-v2/): A high performance general purpose code execution engine.
- [Judge0 Code Execution](https://ce.judge0.com/) : Robust, scalable, and [open-source](https://github.com/judge0/judge0) online code execution system.
### Useful Resources
- [Supabase](https://supabase.com/): Supabase is an open-source Firebase alternative.
- [React.js](https://reactjs.org/): Frontend development library.
- [Next.js](https://nextjs.org/): Frontend development framework.
- [Tailwind CSS](https://tailwindcss.com/): Frontend development framework.
- [Bootstrap](https://getbootstrap.com/): Frontend development framework.
- [Express.js](https://expressjs.com/): Backend development framework.
- [Clerk](https://clerk.com/):  Complete user management.
- [API request using Postman](https://learning.postman.com/docs/getting-started/first-steps/sending-the-first-request/) 

### Tips
1. Use Postman API request code gen feature to speed up development
2. Use Baas (Backend as a service like Firebase or Supabase) to offload critical parts of the system
3. Making a rough workflow or system design diagram before starting can be really helpful


## Task ID: Splitwise Clone

#### `Web Development` `App Development`  `Low-Level Design`

Mentors: [@Muthukumar](https://github.com/BenzeneAlcohol) (+91 8921472523), [@Harshit](https://github.com/hgupta12) (+91 8583905686)

Tag: `Hard`

### Description

Your task is to build a Splitwise clone (website or mobile app) for users to split expenses and minimize the number of transactions among themselves. You are required to implement the following features -   

**1. User Authentication:** - Users can securely access the application through user registration and login.

**2. Friend Requests:** - Users can send and accept friend requests.

**3. Group Creation and Expense Management:** - Users can create groups and add expenses to them.

**4. Minimal Transactions:** - Users can minimize the number of transactions within a group.

**5. Payment Status Tracking:** - Keep users informed about payment statuses (paid or unpaid).


### Useful resources:

These links might give you a direction
- [Debt Simplification Algorithm](https://dash.harvard.edu/bitstream/handle/1/38811480/YAO-SENIORTHESIS-2017.pdf?sequence=3)
- [Low-Level Design of Splitwise](https://youtu.be/6UeDb7ORVPI?si=kftUOqWANzHRc_Gd)
- [Algorithm Behind Splitwise](https://medium.com/@mithunmk93/algorithm-behind-splitwises-debt-simplification-feature-8ac485e97688)

### Tips

1. You don't have to implement the backend from scratch (you can use Firebase or any other BaaS).
2. You may keep a minimal User Interface.
3. The algorithm used for reducing the number of transactions doesn't need to be optimal.
4. Bonus for adding expense categories and bill picture upload.  

## Task ID: CollabPro

#### `Sockets`, `Full Stack Web Development`

Mentors: [Tarun S Hegde](https://github.com/tarun-hegde) ([+91 7899719314](https://wa.me/7899719314)), [Pranav Agarwal](https://github.com/pranav2305) ([+91 8867137015](https://wa.me/8867137015))

Difficulty: `Hard`

### Description

Build a real-time collaboration-based productivity application that is creative, innovative, and useful. The application should be able to solve a real-world problem or make people's lives easier. From a shared To-Do List to sophisticated platforms akin to Google Jamboard and Notion, the possibilities for collaborative productivity are vast and exciting.

Follow the steps below to complete this challenge:  

1. Come up with a unique and innovative idea for a real-time collaboration-based productivity application.  
2. Design a user interface and user experience that is both visually appealing and easy to use.  
3. Implement Authentication and Registration.  

### Bonus Feature(s):
1. Implement Role-Based Access Control.         
2. Allow users to give and receive feedback on each other's work in real-time.

### Useful resources:
These links might give you a direction

* [Implementing WebSockets using Node and React](https://blog.logrocket.com/websocket-tutorial-real-time-node-react/#websocket-establishes-handshake-between-server-client)
* [Implementing Authentication using Node](https://www.freecodecamp.org/news/how-to-authenticate-users-and-implement-cors-in-nodejs-applications/)
* [Implementing Role Base Access Control](https://blog.logrocket.com/using-accesscontrol-for-rbac-and-abac-in-node-js/)

### Tips

1. You are free to use any language/technology/framework of your choice.  
2. Focus on creating a visually appealing user interface.  
3. Implementing the bonus features would result in bonus points.     


## Task ID: GitHub Profile using GraphQL API

#### `GitHub API` `GraphQL` `Frontend`

Mentors: [@Vedant Tarale](https://github.com/VedantTarale) (+91 8106713107), [@Anirudh Prabhakaran](https://github.com/anirudhprabhakaran3) (+91 8826767787)

Tag: `Medium`

### Description
 
The task requires you to build a web interface for users to enter a GitHub ID and retrieve the account statistics, which could include the following details:

- **User Deatils** 

- **Most Recent Repos**

- **Commit History** 

- **Heatmaps or Graphs**

The frontend of the application can be developed using any framework of your choice.

**Note:** Your implementation need not be limited to the above statistics. Feel
free to explore the [GitHub GraphQL API](https://docs.github.com/graphql) for more info.

**NOTE:** You are required to strictly use a **GraphQL API** for this task.

### Useful resources:

These links might give you a direction
- [GitHub GraphQL API](https://docs.github.com/graphql)
- [GitHub Guide to using GraphQL](https://docs.github.com/en/graphql/guides/introduction-to-graphql)
- [Learn GraphQL - Official Site](https://graphql.org/learn/)
- [ReactJS Documentation](https://react.dev/learn)
- [TailwindCSS Documentation](https://tailwindcss.com/docs/installation)
### Tips

1. You can use any CSS framework of your liking.
2. UI/UX should be well designed.
3. Bonus for making the application responsive.


## Task ID: Space Exploration App

#### `Front-End Web Development`, `APIs`, `Svelte`

Mentors: [@Anshuman](https://github.com/anshumanNitk) ([+91 9175954118](https://wa.me/919175954118)), [Parth Mittal](https://github.com/mittal-parth) ([+91 9411327838](https://wa.me/919411327838))

Tag: `Easy`

### Description

This project aims to bring the wonders of space exploration closer to individuals by providing an immersive and educational experience through a web application. Your mission is to design and develop a web application using [**Svelte**](https://svelte.dev/) that promises to provide high performance while being developer friendly. The project should emphasise the UI/UX to ensure that users have an entertaining and informative experience.

Follow the steps below to complete this challenge:

1. Create an eye-catching landing page, prioritizing a user-friendly experience with intuitive navigation and engaging visuals.
2. Use any of the APIs mentioned in the resources section to display some information related to space. 
3. Add an optional search bar.
4. Any other features are welcome!

### Useful resources:

These links might give you a direction:

- [NASA APIs](https://api.nasa.gov/)
- [SpaceX APIs](https://docs.spacexdata.com/)
- [List of Space APIs you can use](https://nordicapis.com/11-space-apis-because-space-is-neat/)
- [Getting Started with Svelte](https://svelte.dev/)
- [Svelete in 100 seconds](https://www.youtube.com/watch?v=rv3Yq-B8qp4)

### Tips

1. The primary focus is on the UI.
2. Start by investigating the NASA APOD, NEO, and any other space-related APIs you intend to use. Recognize their endpoints, data formats, and information retrieval techniques.


## Task ID: Department Website Revamp

#### `Web Development` `UI/UX Design` `Figma`

Mentors:  [@Parth Mittal](https://github.com/mittal-parth) (+91 9411327838)
, [@Harshit](https://github.com/hgupta12) (+91 8583905686)

Tag: `Easy`

### Description

Your task is to give your Department's website a fresh makeover. The main focus of this task is on the UI/UX aspect. At least 5 pages must be implemented. You may implement the website in any framework of your choice or submit a Figma mockup.

### Useful resources:

These links might give you a direction
- [NITK Departments](https://www.nitk.ac.in/departments-and-centers)
- [How To Plan A Website Redesign](https://www.altexsoft.com/blog/uxdesign/how-to-plan-a-website-redesign-stages-approaches-principles/)
- [Figma Tutorial](https://www.youtube.com/watch?v=HZuk6Wkx_Eg)

### Tips

1. You will be judged solely on the user interface and journey.
2. Use information from the original website.

## Task ID: Random Avatar Generator

#### `API Development`

Mentors:  [@Parth Mittal](https://github.com/mittal-parth) (+91 9411327838)
, [@Harshit](https://github.com/hgupta12) (+91 8583905686)

Tag: `Easy`

### Description

Your task is to create an API that generates random avatars. The following features are required to complete the task - 
1. The user should be able to generate avatars based on the random string passed to the API endpoint (Example - `https://api.dicebear.com/7.x/adventurer-neutral/svg?seed=webclub`)
2. The user should have the option of choosing between different file formats (svg and png).
3. Create a landing page and getting started guide to help the user.

### Useful resources:

These links might give you a direction
- [DiceBear](https://www.dicebear.com/)
- [Generating Github Like Characters](https://codesandbox.io/s/9mqum)
- [Generating SVG Characters](https://css-irl.info/creating-generative-svg-characters/)
- [How To Manipulate SVGs](https://www.educative.io/answers/how-to-manipulate-svgs-via-css)
- [How To Generate Random Art](https://www.youtube.com/watch?v=meTpMP0J5E8&t=182s)

### Tips

1. You can use any language or framework of your choice.
2. The task will be considered as `Medium` if user authentication and rate limiting are implemented. 
3. Don't directly copy the implementation given in resources.
4. Brownie points for integrating this with the [NFT Minter](#task-id-nft-minter) task.

## Task ID: Meme Feed
#### `Web Development`, `Frontend Development`, `Backend Development`, `API Integration`

Mentors: [@Abhiraj](https://github.com/abhiraj-mengade) (+91 7709439025), [@Vignaraj](https://github.com/Vignaraj-pai) (+91 6366217217)

Tag: `Hard`

### Description
Create a meme feed application. Users should be able to login to the website and, create simple memes, and save them in their personal library, with options to publish their memes, like and follow other creators.

### Tasks
   - Implement a user interface for meme generation using the meme generator API. Users should be able to choose images, add text, and customize their memes.
   - Develop a backend server to handle user requests and interactions with the meme generator API.
   - Integrate an external meme generator API (e.g., Imgflip API) for meme generation.
   - Implement user authentication and authorization features.

   **User Features**
   - Allow users to register and log in to the application.
   - Create a personal meme library where users can save their created memes.
   - Enable users to publish their memes to a shared meme feed.
   - Implement features for editing and deleting memes.

**NOTE:** The task is to implement all the features rather than the UI/UX. The task will be graded as `hard` only if the final system is a social media feed for memes.

**Bonus Features**
- AI integration to images to generate memes from.
- Weekly meme challenges, where users can submit a meme and upvote other memes, with some ponts system as rewards, example: Reddit Karmas.

### API Options
You can use the following meme generator API for this project:
- [Imgflip API](https://imgflip.com/api): Provides popular memes and meme generation capabilities.
- [Meme Generator API](https://memegen.link/api/): Provides popular memes and meme generation capabilities.

### Useful Resources
- [Django](https://www.djangoproject.com/): Backend development framework.
- [React.js](https://reactjs.org/): Frontend development library.
- [Next.js](https://nextjs.org/): Frontend development framework.
- [Tailwind CSS](https://tailwindcss.com/): Frontend development framework.
- [Bootstrap](https://getbootstrap.com/): Frontend development framework.
- [Express.js](https://expressjs.com/): Backend development framework.
- [Vercel](https://vercel.com): Frameworks and Templates.

### Tips
1. Choose any language or technology stack you're comfortable with.
2. Focus on implementing the features than on the UI.
3. Ensure data security by implementing proper authentication and authorization mechanisms.
4. Test the application thoroughly to ensure it works smoothly.
5. Document your code and project structure for future reference.

## Task ID: MediTracker

#### `Mobile App Development`  `Google ML Kit` `Calendar Integration`

Mentors: [@Shashank SM](https://github.com/Shash0501) [+91 9380435605](https://wa.me/9380435605), [@Abhishek Satpathy](https://github.com/AbhishekSatpathy4848) [+91 7619503901](https://wa.me/7619503901)

Tag: `Medium`

### Description

Build a mobile app for users to scan and effectively manage their medical prescriptions.

**1. Text Extraction:** Extract relevant information from the scanned prescription, including:
- Medicine name(s)
- Time when the medicine is to be taken
- Number of times each medicine should be taken

**2. Calendar Integration:** Create calendar events for each prescription, incorporating the extracted information. Ensure that these events are properly scheduled based on the specified times and frequencies. These timely notifications remind the user to take their medication.

**3. User-Friendly Interface:** Design an intuitive, appealing and user-friendly interface.

**4. CRUD Operations:** Enable users to also manually add, edit, and delete medicines and their corresponding details within each prescription.

### Useful resources:
- [Recognize text in images with ML Kit in JAVA/Kotlin](https://developers.google.com/ml-kit/vision/text-recognition/v2/android)
- [ML Kit Text Recognition Flutter Package](https://pub.dev/packages/google_mlkit_text_recognition)
- [Calendar Provider API for JAVA/Kotlin](https://developer.android.com/guide/topics/providers/calendar-provider)
- [Flutter package for calendar integration](https://pub.dev/packages/add_2_calendar)

### Tips

1. You can either build a native mobile application for Android/iOS or a cross-platform application.
2. Any useful additional/interesting feature will have bonus points.
3. You can assume the prescription to be printed (not handwritten) on paper. 
4. **BONUS:** User login can also be incorporated, allowing users to synchronize their prescriptions across multiple devices.
5. **BONUS:** The app can also scan and detect hand-written prescriptions. 

## Task ID: Intelligent AutoZoom Camera

#### `Mobile App Development`, `Google MLKit`

Mentors: [@Shashank SM](https://github.com/Shash0501) [+91 9380435605](https://wa.me/9380435605), [@Abhishek Satpathy](https://github.com/AbhishekSatpathy4848) [+91 7619503901](https://wa.me/7619503901)

Tag: `Medium`

### Description

Build a mobile application designed for animal enthusiasts, photographers, and pet owners. This app leverages machine learning to automatically adjust the zoom level when taking pictures of objects, ensuring that the subject (e.g., a dog) is prominently captured even when it's at a distance.

1. The object can be assumed to be a dog. Whenever a dog is detected in the live camera feed, the camera automatically zooms in appropriately to capture a photo.
2. The user can view all the photos captured from within the app itself.

### Useful resources:

- [Object Detection and Tracking Docs JAVA/Kotlin](https://developers.google.com/ml-kit/vision/object-detection)
- [Flutter Object Detection and Tracking Package](https://pub.dev/packages/google_mlkit_object_detection)

### Tips

1. Minimal UI is sufficient.
2. Pre-trained models can also be used rather than using Google's ML Kit.
3. You can either build a native mobile application for Android/iOS or a cross-platform application.

***

# Inter-SIG Tasks

## Task ID: NFT Minter

#### `Blockchain`, `Web3`, `NFT`, `Ethereum`

Mentors: [Mardav Gandhi](https://github.com/marcdhi) ([+91 9033398366](https://wa.me/919033398366)), [Ayush Kumar](https://github.com/ayush4345) ([+91 9334352548](https://wa.me/919334352548)), [Parth Mittal](https://github.com/mittal-parth) ([+91 9411327838](https://wa.me/919411327838))

Difficulty: `Medium`

### Description

In this task, you will dive into the world of blockchain and NFTs by minting your very own NFT collection. NFTs are unique digital assets that represent ownership or proof of authenticity of a digital item, such as art, collectables, or even virtual real estate, using blockchain technology.

Follow the steps below to complete this challenge:

1. Mint a collection of your favourite television characters. Find images of your favorite television characters and deploy a smart contract that will mint an NFT for each character.
2. Set a maximum limit of 3000 NFTs for your collection.
3. Implement functionality to allow the owner of an NFT to change its image.

### Useful resources:

These links might give you a direction

- [How to create an NFT](https://www.web3.university/tracks/build-your-first-nft/how-to-create-an-nft)
- [Minting an NFT](https://www.web3.university/tracks/build-your-first-nft/how-to-mint-an-nft-using-ethers-js)
- [IPFS](https://ipfs.tech/) Providers :
  1. [Pinata](https://www.pinata.cloud/)
  2. [web3.storage](https://web3.storage/)
- [Integrate Your Smart Contract With a Frontend](https://www.web3.university/tracks/create-a-smart-contract/integrate-your-smart-contract-with-a-frontend)
- [Hardhat](https://hardhat.org/)

### Tips

1. Start by researching how to deploy a smart contract on the Ethereum blockchain.
2. Look into existing NFT standards like `ERC-721` to understand how NFTs work.
3. You are free to use any frontend framework of your choice.

## Task ID: File Manager

#### `Desktop Application`

Mentors: [@Sathvik Hebbar](https://github.com/sathuhebbar) ([+91 6363963887](https://wa.me/916363963887)), [@Fahim Ahmed](https://github.com/ahmedfahim21) ([+91 8861054452](https://wa.me/918861054452))

Tag: `Hard`

### Description:

Desktop applications are software programs that are designed to run on individual computers or devices, such as personal computers and laptops. Unlike web applications, which run in web browsers, desktop applications are installed and executed directly on the user's local machine. They offer various advantages, including improved performance, offline functionality, and access to the full capabilities of the host operating system.

There are several frameworks and technologies used for desktop application development, each with its own strengths and characteristics.
Some of the popular ones are:
- [Electron](https://www.electronjs.org/) (used by editors like VS Code and Atom)
- [Tauri](https://tauri.app/) (Rust-based toolchain for creating desktop apps using common web frameworks )
- [JavaFX](https://openjfx.io/) (cross-platform Java library, successor to Java SWING)
- [Qt](https://www.qt.io/) (the framework behind the KDE suite )
- [GTK](https://www.gtk.org/) (the most common Linux framework, employed by GNOME, MATE, XFCE and almost all non-KDE descendants)


In this task, you need to build a simple file manager that allows users to organize, view, and manipulate files and folders on their computer.

Implement a GUI application with the common features found in file managers:
1. Support for basic file and folder operations such as creating, deleting, copying, and renaming files and folders.
2. Easy access to information about files and folders like size, type, date created, date modified, and permissions (the Properties dialogue box, basically).
3. The quick access pane - the pane which shows your library folders (documents, downloads), attached devices, etc, for easy navigation. 
4. Graceful error handling - appropriate dialogue boxes for, say, a failed operation (due to lack of permissions).

Feel free to implement any other features that you find on your preferred file manager! 

### Useful Resources:

About file systems
- [C filesyscalls](https://www2.cs.uregina.ca/~hamilton/courses/330/notes/unix/filesyscalls.html)
- [Rust fs](https://doc.rust-lang.org/stable/std/fs/index.html)

Some good file manager examples for inspiration:
- [XFCE Thunar](https://docs.xfce.org/xfce/thunar/start)
- [KDE Dolphin](https://apps.kde.org/dolphin/)

Framework Documentations:
- [Tauri](https://tauri.app/)
- [Electron](https://www.electronjs.org/docs/latest)
- [JavaFX](https://docs.oracle.com/javase/8/javafx/api/toc.htm)
- [GTK](https://www.gtk.org/docs/)
- [QT](https://doc.qt.io/)

### Tips:
- Consider using any frameworks or technologies like Electron, Tauri, JavaFX, Qt, GTK or any other that suits your programming skills and preferences.
- Leverage existing libraries and tools that can simplify certain tasks.
- Try to keep minimal UI and focus on the functionality of the application.
