<a id="readme-top"></a>

<h1 align="center">StoreIt | Your personal cloud, reimagined! 📥</h1> 

<div align="center">

<img src="/public/assets/images/StorageDashboard.png" alt="Picture of QuickGist an open-source summarizer that converts lengthy articles into clear and concise insights.">

<p align="center">StoreIt is a modern storage and file-sharing platform, inspired by Google Drive that takes the hassle out of managing files with style. Built using Next.js 15 featuring beautifully customized shadcn/ui components while being supercharged with Appwrite Node SDK, it lets you upload, organize, and share your files with ease. 
<br/>
<br/>
Whether you are a solo user or a team, StoreIt keeps your files just a click away ready to go wherever you need them. Allowing you to dive in and take control of your digital storage like never before! 
<br />

<a href="www.storeit.amberforrester.io">StoreIt Live Link</a>



<br />
<a href="https://github.com/AmberForrester/store_it">Source Code</a>
.
<a href="https://github.com/AmberForrester/store_it/issues/new?assignees=&labels=bug&projects=&template=bug-report-%F0%9F%90%9E.md&title=">Report Bug</a>
.
<a href="https://github.com/AmberForrester/store_it/issues/new?assignees=&labels=enhancement&projects=&template=feature-request-%F0%9F%9A%80.md&title=">Request Feature</a>
</p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#project-structure">Project Structure</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#steps-to-install">Steps to Install</a></li>
    <li><a href="#how-to-run-the-application">How to Run the Application</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>
<br />



## Features
- **Secure User Authentication with Appwrite:** Enable easy signup, login, and logout functions powered by Appwrite’s robust authentication system for a safe user experience.
- **Effortless File Uploads:** Upload various file types—documents, images, videos, and audio—seamlessly, ensuring all your important data is securely stored.
- **Comprehensive File Management:** Automatically saves summaries in your local storage, allowing you to access and manage your reading history effortlessly. 
- **Simple File Sharing:** Share uploaded files effortlessly, fostering collaboration and granting others easy access to vital content.
- **Insightful Dashboard Overview:** Get a quick overview of your storage with a dynamic dashboard displaying total and consumed storage, recent uploads, and a categorized file summary.
- **Advanced Global Search:** Find files and shared content across the platform swiftly with an enhanced global search feature for quick access.
- **Flexible Sorting Options:** Organize files by date, name, or size, ensuring smooth and efficient file management tailored to your needs.
- **Modern, Responsive Design:** Enjoy a clean, minimalist UI that prioritizes usability, offering a seamless experience across all devices.

<p align="right">(<a href="#readme-top">top of page</a>)</p>



## Project Structure

<img src="/public/assets/images/ProjectStructure.png" alt="Picture of the project structure in Visual Studio Code">

<p align="right">(<a href="#readme-top">top of page</a>)</p>



## Installation

### Prerequisite Tech Stacks
- [NEXT.js 15](https://nextjs.org/)
- [React 19](https://react.dev/)
- [Shadcn/ui](https://ui.shadcn.com/)
- [Node.js](https://nodejs.org/en)
- [Tailwind CSS](https://tailwindcss.com/)
- [Appwrite](https://appwrite.io/) - Create an account to receive your Appwrite credentials, and create a new project.



### Steps to Install

Set up the project locally on your machine by following these steps. 
Keep in mind, they are specific to using Windows.

1. **Clone the Repository:**
  ```bash
  git clone https://github.com/AmberForrester/store_it
  ```

2. **Navigate to the project directory:**
  ```bash
  cd store_it
  ```

3. **Install Required Dependencies:** 

Run the following command to install the project dependencies using npm:
  ```bash
  npm install
  ```

4. **Set Up Environment Variables:**

Create a new file named `.env.local` in the root of your project directory and add the following:
   ```bash
  NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
  NEXT_PUBLIC_APPWRITE_PROJECT=""
  NEXT_PUBLIC_APPWRITE_DATABASE=""
  NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
  NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
  NEXT_PUBLIC_APPWRITE_BUCKET=""
  NEXT_APPWRITE_KEY=""
   ```

Use the key provided after creating your account and new project with [Appwrite](https://appwrite.io/). 

5. **Add `.env.local` to `.gitignore`**

> [!CAUTION]
> To ensure your sensitive information does not get committed to version control:
  - Open (or create) the `.gitignore` file in the root directory.
  - Add the following line to the file:
   ```
   .env.local
   ```

This step will prevent the `.env.local` file from being tracked by Git and keep your sensitive credentials secure. 



### How to Run the Application

1. Open your terminal in the project directory and run the following command: 
   ```bash
   npm run dev
   ```

2. Paste `http://localhost:3000` in your browser to view the project.

<p align="right">(<a href="#readme-top">top of page</a>)</p>



# Home Page 
<img src="/public/assets/images/StoreItHome.png" alt="StoreIt home page">

# OTP Verification
<img src="/public/assets/images/OTPVerification.png" alt="OTP Verfication page">

# Storage Dashboard
<img src="/public/assets/images/StorageDashboard.png" alt="Storage Dashboard">

<p align="right">(<a href="#readme-top">top of page</a>)</p>



### Contributing

I have learned that contributions are the heart of what makes the open source community such an amazing place! We are constantly able to learn, grow, inspire eachother, and create incredible things. Any contributions you make are **greatly appreciated**, we are so lucky to be here together.

If you have a suggestion that would make this project better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please, don't forget to give the project a :star:! 

I appreciate you!

<p align="right">(<a href="#readme-top">top of page</a>)</p>



### License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">top of page</a>)</p>



### Acknowledgments

Please take some time to check out the links below! I found value in each and every one of them while creating this project, so my hope is that you will to!

* [Google Drive Clone with Next.js 15](https://youtu.be/lie0cr3wESQ?si=2ec5nZEWd7a7sYll) - Special thank you to _JavaScript Mastery_ for the tutorial!
* [Best README Template](https://github.com/othneildrew/Best-README-Template)
* [Basic Syntax: Markdown Guide](https://www.markdownguide.org/basic-syntax/#reference-style-links)
* [Formatting Syntax: GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#animal-bug)

<p align="center">Source links below will assist you with OTP Log In, Next.js Server Action, and Log Out</p>

OTP Log In: 
- https://appwrite.io/docs/products/auth/email-otp/ 
- https://appwrite.io/docs/tutorials/astro-ssr-auth/step-6/
- https://appwrite.io/docs/tutorials/sveltekit-csr-auth/step-6/ 

Next.js Server Action - sign in the user using OTP:
- https://appwrite.io/docs/tutorials/nextjs-ssr-auth/step-5/ 
- https://appwrite.io/docs/tutorials/nextjs-ssr-auth/step-7/ 
- https://appwrite.io/docs/tutorials/nextjs-ssr-auth/step-6/ 
- https://appwrite.io/docs/tutorials/nuxt-ssr-auth/step-6/ 
- https://appwrite.io/docs/tutorials/nuxt-ssr-auth/step-5/ 

Log Out:
- https://appwrite.io/docs/tutorials/astro-ssr-auth/step-6/ 
- https://appwrite.io/docs/tutorials/nuxt-ssr-auth/step-6/ 
- https://appwrite.io/docs/tutorials/nextjs-ssr-auth/step-6/ 

<p align="right">(<a href="#readme-top">top of page</a>)</p>