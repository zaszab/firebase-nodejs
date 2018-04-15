# Node.js apps on Firebase Hosting Crash Course

Example Node.js application based on Firecast video: https://www.youtube.com/watch?v=LOeioOKUKI8

# Getting started

Initialize your skeleton
```
mkdir firebase-app
cd firebase-app
firebase init hosting
firebase init functions
cd functions
npm i express --save
cd ..
code .
```

After modification you can test it on http://localhost:5000 by running this in console:
```
firebase serve --only functions,hosting
```

For deploy type:
```
firebase deploy
```

And you can check it on \
https://YOURPROJECTNAME.firebaseapp.com