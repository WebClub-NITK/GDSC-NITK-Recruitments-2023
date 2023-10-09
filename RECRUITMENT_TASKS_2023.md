# Tasks

- It is perfectly fine if you have no experience in the field and trying it out for the first time. Please put in sincere efforts and try to learn from whatever you complete!
- Each Task has a ID, tags, mentor, description, tips and useful resources
- You can refer to the resources put up in each task to understand the concepts required to complete the task.
- Feel free to reach out to the mentors for any assistance you need.
- Mention the Task ID attempted in the README of your private GitHub repository.
- Read the instructions, evaluation criteria and submission details [here](./README.md)

### Table of contents

| Task                                                        |
| ----------------------------------------------------------- |
| [NFT Minter](#task-id-nft-minter)                           |
| [Chrome Tabs Organiser](#task-id-chrome-tabs-organiser)     |
| [VoicePen](#task-id-voicepen)                               |
| [WebClub Discord ChatBot](#task-id-webclub-discord-chatbot) |
| [SportsTracker](#task-id-sportstracker)                     |
| [Leetcode Clone](#task-id-leetcode-clone)                   |
| [Splitwise Clone](#task-id-splitwise-clone)                 |


## Task ID: NFT Minter

#### `Blockchain`, `Web3`, `NFT`, `Ethereum`

Mentors: [Mardav Gandhi](https://github.com/marcdhi) ([+91 9033398366](https://wa.me/919033398366)), [Ayush Kumar](https://github.com/ayush4345) ([+91 9334352548](https://wa.me/919334352548)), [Parth Mittal](https://github.com/mittal-parth) ([+91 9411327838](https://wa.me/919411327838)),

Difficulty: `Medium`

### Description

In this task, you will dive into the world of blockchain and NFTs by minting your very own NFT collection. NFTs are unique digital assets that represent ownership or proof of authenticity of a digital item, such as art, collectibles, or even virtual real estate, using blockchain technology.

Follow the steps below to complete this challenge:

1. Mint a collection of your favorite television characters. Find images of your favorite television characters, and deploy a smart contract that will mint an NFT for each character.
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

## Task ID: Chrome Tabs Organiser

#### `Chrome Extension`

Mentors: [Mardav Gandhi](https://github.com/marcdhi) ([+91 9033398366](https://wa.me/919033398366)), [Parth Mittal](https://github.com/mittal-parth) ([+91 9411327838](https://wa.me/919411327838))

Difficulty: `Medium-Hard`

### Description

Currently, Chrome offers a built-in feature for grouping tabs, allowing users to manually organize them, assign names, and assign colors. However, in this task, you will be creating a Chrome Extension that automates this process, making tab management more efficient.

Follow the steps below to complete this challenge:

1. Create a Chrome Extension that automatically groups tabs from the same website under a single bar. Ensure that the extension recognizes the context by naming the bar after the visited website or page automatically.
2. Implement a feature to assign colors to tabs that match the theme of the respective websites for visual organization.

### Bonus Feature:

Implement context recognition from different websites and then group them together automatically. For example, if the user is browsing `web3` content but from different websites, group all of them under the name of a `web3` tab with a default color.
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

Difficulty: `Medium-Hard`

### Description

Imagine a scenario where you have lots to speak about. You would end up recording a voice note and sharing it. But what if you could convert this into precise text, that doesn't contain the 'umms' and 'aahs' and gives a crisp summary conveying the most important ideas. Your task is to create an application that takes their voice input, converts it into text, and enhances the text's presentation by summarizing it and structuring it according to their requirements.

Follow the steps below to complete this challenge:

1. Implement easy recording functionality, allowing users to start recording by clicking a button on the screen.
2. On submitting, the application should transcribe spoken words into text, eliminating repeated content, filler words, and restructuring the text for readability.
3. Use Text Summarisation API's to structure the above generated text into certain format, using prompt engineering if needed.
4. The final output should be the prettified text.

Note: The focus here is not the UI or the ML model. The UI can be kept relatively simple. The feature set can also be kept minimal by skipping authentication, state saving, etc. The usage of readily available APIs is encouraged and preferred over ML techniques.

### Bonus Feature(s):

1. Create a Chrome extension for recording, enabling users to record from any browser tab.
2. Enable file uploads, where users can upload audio files and text notes for transcription and rewriting.
3. Implement custom styles, allowing users to define writing styles, including a custom style that mimics their own writing style (use API's like GPT-3.5)

**NOTE**: Implementing any one the above features would be sufficient, and would result in this task being treated as a `Hard` task.

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
3. Ensure that the final output is not only clear but also maintains the core content and meaning from the original voice input.

## Task ID: WebClub Discord ChatBot

#### `Discord Bot` `APIs` `Full Stack Development`

Mentors: [@Ayush Kumar Singh](https://github.com/Ayush4345) ([+91 9334352548](https://wa.me/919334352548)), [@Abhiraj Mengade](https://github.com/abhiraj-mengade) ([+91 7709439025](https://wa.me/917790439025))

Tag: `Medium`

### Description

Discord is a popular communication platform designed for creating communities. Gamers widely use it, but it's also a versatile tool for various interest groups, businesses, and developers. A Discord bot is a software application that automates tasks within Discord servers. They can be used for moderation, utilities, games, or music playback, enhancing server functionality.

In this task, you are expected to create an interactive Discord bot that displays information about [Web Enthusiasts' Club](https://webclub.nitk.ac.in/) like following things should be covered :
- Informing about Upcoming Events of WEC
- Information on SIGs
- Past Events in each SIGs
- Non Technical Events
- Information on Members

 Users should be able to access the information by using commands, just like how it is done in bots like mee6 and arcane. You can explore the discords bot [here](https://top.gg/).

Follow the steps below to complete this challenge:

1. Use a database to store the information about **Web Enthusiasts' Club**.
2. Make a simple interface to insert and update in the database.
3. Create an interactive Discord Bot using APIs provided by Discord to display information related to Web Club

\*\*Note: Use dummy data wherever applicable

### Bonus Feature:

1. Modify the bot to enable natural language interaction, allowing users to ask questions like 'What is the upcoming event?' or 'Who is the convenor of the web club?' instead of using commands.

### Useful resources:

- [Build a Discord Bot With Python
  ](https://betterprogramming.pub/coding-a-discord-bot-with-python-64da9d6cade7)
- [Building your first Discord app
  ](https://discord.com/developers/docs/getting-started)
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

Your task is to build a web application that allows users to track their favorite sports teams. The application will use the [SportRadar API](https://developer.sportradar.com/docs/read/Home#getting-started) to collect schedules, results, and other information about the user's favourite sports teams. 

Follow the steps below to complete this challenge:

1. Develop a responsive frontend using any framework of your choice.
2. Use the SportRadar API to fetch data about sports teams, including schedules, match results, team details, etc.
3. Store user data like their favorite teams in browser cookies/local storage(so,no need to use database).

In short, the application should allow users to:
   - Search for sports teams using the SportRadar API.
   - Add and remove sports teams from their list of favorites.
   - View detailed information about their favorite teams, including schedules, match results, points table, players, etc

### Useful Resources

- [SportRadar API Documentation](https://developer.sportradar.com/docs/read/Home#getting-started)
- [Working with APIs - Postman](https://learning.postman.com/docs/getting-started/first-steps/sending-the-first-request/)
- [How to store data in browser](https://blog.bitsrc.io/different-ways-to-store-data-in-browser-706a2afb4e58)

### Tips

1. Explore the SportRadar API using the Postman collection provided in the Documentation.
2. Try to make it for a single sport first, you may then try having multiple sports.
3. Focus should be on building a good User Interface. Try to have charts, tables, logos, etc.



## Task ID: Leetcode Clone
#### `Web Development`, `Code Execution`, `Backend Development`, `API Integration`

Mentors:  [@Shubham-Rasal](https://github.com/Shubham-Rasal) (+91 7349784770),  [@sujay000](https://github.com/sujay000) (+91 94219 68047)

Tag: `Hard`?

### Description

Create a simple leetcode clone that allows to users to create account and then solve preset problems in more than one programming language

### Tasks
1. **Frontend Development**
   - Create a page with a list of questions available to solve.
   - Implement necessary authentication and authorization for users to access individual questions
   - Incorporate any open-source code editor for easy coding

2. **Backend Development**
   - Develop a backend that is responsible for handling user requests
   - Functionality includes authentication and user data storage.
   - The most important feature is to incorporate a code execution engine which will be responsible for executing the user-submitted code, comparing results, and returning the output.
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
2. Use Baas (Backend as a service like firebase or supabase) to offload critical parts of the system
3. Making a rough workflow or system design diagram before starting can be really helpful


## Task ID: Splitwise Clone

#### `Web Development` `App Development`  `Low Level Design`

Mentors: [@Muthukumar](https://github.com/BenzeneAlcohol) (+91 8921472523), [@Harshit](https://github.com/hgupta12) (+91 8583905686)

Tag: `Hard`

### Description

Your task is to build a Splitwise clone (website or mobile app) for users to split expenses and minimize the number of transactions among themselves. You are required to implement the following features -   

**1. User Authentication:** - Users can securely access the application through user registration and login.

**2. Friend Requests:** - Users can send and accept friend requests.

**3. Group Creation and Expense Management:** - Users can create groups and add expenses to them.

**4. Minimal Transactions:** - Users can minimize number of transactions within a group.

**5. Payment Status Tracking:** - Keep users informed about payment statuses (paid or unpaid).


### Useful resources:

These links might give you a direction
- [Debt Simplification Algorithm](https://dash.harvard.edu/bitstream/handle/1/38811480/YAO-SENIORTHESIS-2017.pdf?sequence=3)
- [Low Level Design of Splitwise](https://youtu.be/6UeDb7ORVPI?si=kftUOqWANzHRc_Gd)
- [Algorithm Behind Splitwise](https://medium.com/@mithunmk93/algorithm-behind-splitwises-debt-simplification-feature-8ac485e97688)

### Tips

1. You dont have to implement the backend from scratch (you can use Firebase or any other BaaS).
2. You may keep a minimal User Interface.
3. The algorithm used for reducing number of transactions doesn't need to be optimal.
4. Bonus for adding expense categories and bill picture upload.

