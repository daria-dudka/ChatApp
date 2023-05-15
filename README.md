#  Chat App using React Native Expo and Firebase

React Native App built using Expo, Firebase and React Native Gifted Chat

https://user-images.githubusercontent.com/66278954/236198340-ff7d57c6-9ab5-452f-a187-c875bd4eb073.mp4

## How to clone

Clone the repo
```
git clone https://github.com/daria-dudka/ChatApp.git
```

cd into the just created project and install dependencies with npm
```
cd ChatApp && npm i
```

Add your firebase backend config in the `firebase.js` file
```
const firebaseConfig = {
  apiKey: Constants.manifest.extra.apiKey,
  authDomain: Constants.manifest.extra.authDomain,
  projectId: Constants.manifest.extra.projectId,
  storageBucket: Constants.manifest.extra.storageBucket,
  messagingSenderId: Constants.manifest.extra.messagingSenderId,
  appId: Constants.manifest.extra.appId,
  databaseURL: Constants.manifest.extra.databaseURL
};

```

Run the project
```
expo start
```
