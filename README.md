# theprobot
## Description
A Simple Twitter Bot built using the npm twit Twitter API Client. The bot periodically finds recent tweets with the selected keywords and tweets a reply of your choice.
## Installation
__1. Ensure that Node.js and npm have been installed__

Visit the [official downloads page](https://nodejs.org/en/download/) in case of any issue.

__2. Clone the repo__
```bash
git clone https://github.com/shadxx7/theprobot.git
```
__3. Install Dependencies__
```bash
cd theprobot # Go to the project root directory
npm install
```
 __3. Setting the Keyword and the Reply__

- Navigate into the directory where you have cloned the repository
-  Find index.js and open it
- Inside the file, locate the Reply tweet and keywords comment and change it according to what you require


__4. Run An Instance__
```bash
cd theprobot # Go to the project root directory
npm start
```
__5. Changing the tweet speed__

In the index.js; navigate to the end and change the value in the sleep() function call. [ 1000 = 1 second ]
