# 🤖 BOTPRESS INBOX ✉️

This inbox dashboard can be used for managing conversations and users of your Botpress bot. It uses the official API (in Beta still) and TypeScript client.

## ✳️ Features

-   List conversations
-   List messages of a conversation
-   List users of a conversation
-   Show details of conversation (tags and created/updated dates)
-   Send a new message to conversation
-   Delete conversation

## 💬 How to use

0. ☑️ Prerequisites: you need to have [Node.js](https://nodejs.org/en/download) installed and access to a command line app (Terminal/Power Shell/Command Prompt)
1. ⬇️ Download this project folder and extract it
2. 🖥️ Right click on the folder and open it on the , the active path should look like below (unless you moved it)
   ![image](https://github.com/devguilhermy/botpress-inbox/assets/55157846/96f528dc-34e4-4b9c-8a21-44b038061db3)
3. ⚙️ Copy this command - `npm install && npm run start` - then paste in the Terminal and press Enter to run the app
4. 📝 You are going to see a screen asking for your token and for the bot URL (these are saved only locally on your PC)
5. 🧑‍💻 Go to Botpress Dashboard, click on your avatar, and go to Personal Access Tokens
6. 🗝️ Create a new token called 'inbox-dashboard' for example, and paste it in the app
7. 🔗 Still in the dashboard, click on the desired bot on the list and then copy and paste the URL in the app
8. ✅ You're done!

## ✨ EXTRA INFO

-   🤖 In order to send messages as the bot, the bot must have sent an automated message before (from Botpress Studio)
-   🌐 You can use this project on your localhost only (it works perfectly), or you could host it for free on a platform like Vercel/Netlify, in which case you would need to restrict access with native authentication from the platform (easier), or using JWT/Cookies.

## 👀 How it looks like

![image](https://github.com/devguilhermy/botpress-inbox/assets/55157846/7978adfe-ad28-41be-8573-3930023e9607)

## ✅ To do

-   [ ] Export single and multiple conversations
-   [ ] Select multiple conversations to delete
-   [ ] Create conversation
-   [ ] Sort conversations by last message
-   [ ] Show user name in the conversation list
-   [ ] Delete user
-   [ ] Responsive style for mobile
-   [ ] Authentication
-   [x] Better styling
-   [x] Load conversations and messages on scroll
-   [x] Get the bot id as user automatically
-   [x] Prompt the user for token and ids instead of using .env

## ⚙️ Libraries

This project makes use of the following libraries:

-   React.js v18.2 - app structure
-   Vite.js v3.1 - app build
-   Botpress Client v0.1.1 - requests to the botpress API
-   Date-fns v2.30 - date formatting
-   TypeScript v4.8 - typings and interfaces
-   TailwindCSS v3.1 - styling
-   React Router Dom v6.11 - routing
-   CryptoJS - encrypting keys

## 👥 Contribution

We welcome contributions from the community, so feel free to create issues and open pull requests. As an open-source project, we value your help and feedback in making this project better.
Happy contributing and bot-building! ☺️

## 📃 License

This project is licensed under the MIT License. You are free to use, modify, and distribute it as per the terms of the license. You can also fork the project and customize it to suit your specific use case, whether you choose to keep it open source or not.

## ⚠️ Disclaimer

This project is an independent effort and is not affiliated with Botpress in any way. It utilizes the public API provided by the platform to list and manage conversations. Any misuse of this application is solely the responsibility of the user. The creators and contributors of this project disclaim any liability for any damages or issues arising from the use or misuse of this project.
