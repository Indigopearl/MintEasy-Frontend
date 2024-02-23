# **MintEasy Frontend Installation Guide (Local Machine - Frontend Only)**

**Important Note:** This guide covers the installation of the **MintEasy-Frontend** project on a **local machine** . It assumes you have no prior experience with React development. Please be aware that this guide focuses solely on local development and **does not** include instructions for deployment to a server.

**Prerequisites:**

* Node.js   v.18.19.0
* npm       v.10.2.3

Download and install Node.js from the official website

```bash
https://nodejs.org/
```

which includes npm by default.

Verify installation by running

```bash
node -v
```

and

```bash
npm -v
```

in your terminal.

* Git

## Project Setup

### Clone the Repository

```bash
git clone https://github.com/your-github-username/mint_easy_frontend.git
```

Replace your-github-username with your actual GitHub username and the repository URL if different.

### Update the Project

```bash
git pull
```

### Install scss

```bash
npm install -g sass
```

### Install Dependencies

Navigate to the project directory you just cloned and run the following command to install all the required dependencies:

```bash
npm install
```

### Start the Development Server

Once the installation is complete, run the following command to start the development server

```bash
npm run dev
```

This will start the server, usually running on `http://localhost:5173/`. Open this URL in your web browser to access the MintEasy frontend application.

Congratulations! You have successfully set up and launched the MintEasy frontend on your local machine.
