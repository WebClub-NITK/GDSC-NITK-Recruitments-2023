# Tasks

* It is perfectly fine if you have no experience in the field and trying it out for the first time. Please put in sincere efforts and try to learn from whatever you complete!
* Each Task has a ID, tags, mentor, description, tips and useful resources
* You can refer to the resources put up in each task to understand the concepts required to complete the task.
* Feel free to reach out to the mentors for any assistance you need.
* Mention the Task ID attempted in the README of your private GitHub repository.
* Read the instructions, evaluation criteria and submission details [here](./README.md)

### Table of contents
| Task      |
| ----------- |
| [NFT Minter](#task-id-nft-minter)        |
| [Chrome Tabs Organiser](#task-id-chrome-tabs-organiser)        |
| [VoicePen](#task-id-voicepen)        |
| [Task B](#task-b)        |


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

* [How to create an NFT](https://www.web3.university/tracks/build-your-first-nft/how-to-create-an-nft)
* [Minting an NFT](https://www.web3.university/tracks/build-your-first-nft/how-to-mint-an-nft-using-ethers-js)
* [IPFS](https://ipfs.tech/) Providers :
    1. [Pinata](https://www.pinata.cloud/)
    2. [web3.storage](https://web3.storage/)
* [Integrate Your Smart Contract With a Frontend](https://www.web3.university/tracks/create-a-smart-contract/integrate-your-smart-contract-with-a-frontend)
* [Hardhat](https://hardhat.org/)

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

* [Getting Started with Chrome Extensions Development](https://developer.chrome.com/docs/extensions/mv3/getstarted/)
* [Understanding manifest.json](https://www.freecodecamp.org/news/building-chrome-extension/)
* [Chrome Tabs API](https://developer.chrome.com/docs/extensions/reference/tabs/)


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

* [Using React.js to record Audio](https://blog.logrocket.com/how-to-create-video-audio-recorder-react/#audio-recorder-component)
* [Record Audio in Javascript](https://ralzohairi.medium.com/audio-recording-in-javascript-96eed45b75ee)
* [Voice-to-Text API](https://cloud.google.com/speech-to-text)
* [Free Summarisation API to get started with](https://oneai.com/)
* [Hugging Face API](https://huggingface.co/inference-api)
* [Using Axios to make API Calls](https://blog.logrocket.com/how-to-make-http-requests-like-a-pro-with-axios/)
* [Hugging Face Access Tokens](https://huggingface.co/docs/hub/security-tokens)
* [Postman - test and create APIs](https://www.postman.com/)


### Tips
1. Start by exploring existing speech recognition libraries and APIs to handle voice input.
2. Leverage summarization APIs to enhance the text quality without the need for complex machine learning models.
3. Ensure that the final output is not only clear but also maintains the core content and meaning from the original voice input.

## Task ID: Meme Feed
#### `Web Development`, `Frontend Development`, `Backend Development`, `API Integration`

Mentors: [@Abhiraj](https://github.com/abhiraj-mengade) (+91 7709439025), [@Vignaraj](https://github.com/Vignaraj-pai) (+91 6366217217)

Tag: `Hard`

### Description
Create a meme feed application. Users should be able to login to the website and create simple memes and save them in their personal library, with options to publish their memes, like and follow other creators.

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

**Bonus Features**
- AI integration to images to generate memes from.
- Weekly meme challenges, where users can submit a meme for and vote for the best memes. The memes with most upvotes win.

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
2. Focus on creating an intuitive and visually appealing user interface.
3. Ensure data security by implementing proper authentication and authorization mechanisms.
4. Test the application thoroughly to ensure it works smoothly.
5. Document your code and project structure for future reference.
