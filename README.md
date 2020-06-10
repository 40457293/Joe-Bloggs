# Joe Bloggs

**Joe Bloggs** is a blogging site that utilises HTML, CSS, JavaScript, as well as Node.JS & pug on the server-side. It was created using Notepad++, Sublime Text 3, WebStorm, Microsoft Edge, Google Chrome, and MongoDB Compass.


## Installation

Joe Bloggs requires **MongoDB** to be installed. This can be downloaded from [here](https://www.mongodb.com/dr/fastdl.mongodb.org/win32/mongodb-win32-x86_64-2012plus-4.2.7-signed.msi/download) (not included locally due to large file size).

In addition, several **Node.JS modules** must be installed: 

1. First, [download and install Node.JS](https://nodejs.org/en/download/) . 
2. Extract `40457293.zip` into a directory of your choice (in this example, `C:/Users/40457293/CourseworkBlog`).
3. Browse to this directory using your operating system's command prompt (using the `cd` command) (ex: `cd C:/Users/40457293/CourseworkBlog`).
4. Run `npm install` to install the project's dependencies. 
> **Note:** This guide assumes that you are using a modern browser and operating system with support for the features included in this project; it may not function as intended on archaic systems.

## Usage

From the directory containing `app.js`, `write.js`, and `package.json`, run `npm start app.js`. Then, using an internet browser of your choice, navigate to `localhost:3001` (although `localhost:3000` should work too). This will provide access to the blog site.

## Troubleshooting

- If an error occurs when trying to submit posts to the blog, it is likely that MongoDB is not installed or not installed correctly. Please install from [this link](https://www.mongodb.com/dr/fastdl.mongodb.org/win32/mongodb-win32-x86_64-2012plus-4.2.7-signed.msi/download) (Windows). 

- If an error occurs when running `npm start app.js`, it is likely that you did not install the dependencies. Run `npm install` first, from the same directory, then try again.

- An error indicating that port 3000 is already in use means that the app is either already running, or another application is using the port. A tutorial such as [this one]([https://stackoverflow.com/questions/39632667/how-do-i-kill-the-process-currently-using-a-port-on-localhost-in-windows](https://stackoverflow.com/questions/39632667/how-do-i-kill-the-process-currently-using-a-port-on-localhost-in-windows)) can be used to kill this process.

- Other errors may be caused by running commands in the wrong directory; `npm start app.js` and `npm install` should be run from the same directory as `app.js` and `package.json`.
