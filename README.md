# VS Code Firebase-React snippets

This extension for Visual Studio Code adds snippets for Firebase for JavaScript and TypeScript.

![demo](images/demo.gif)

## Features

This extension provides a collection of easy-to-use firebase snippets for react js and frameworks that uses react and helps developer keep their sanity.

### JavaScript/TypeScript Firebase Snippets

#### Firebase Import Snippets

| Snippet                              | Purpose                                                          |
| ------------------------------------ | ---------------------------------------------------------------- |
| `fbi-app`                            | general purpose firebase app import                              |
| `fbi-auth`                           | general purpose firebase auth import                             |
| `fbi-firestore`                      | general purpose firebase firestore import                        |
| `fbi-storage`                        | general purpose firebase storage import                          |
| `fbi-initApp`                        | imports initializeApp module from firebase/app                   |
| `fbi-getApp(s)`                      | imports getApp and getApps modules from firebase/app             |
| `fbi-delApp`                         | imports deleteApp module from firebase/app                       |
| `fbi-googleProvider`                 | imports googleAuthProvider from firebase/auth                    |
| `fbi-facebookProvider`               | imports facebookAuthProvider from firebase/auth                  |
| `fbi-twitterProvider`                | imports twitterAuthProvider from firebase/auth                   |
| `fbi-githubProvider`                 | imports githubAuthProvider from firebase/auth                    |
| `fbi-phoneProvider`                  | imports phoneAuthProvider from firebase/auth                     |
| `fbi-createUserWithEmailAndPassword` | imports createUserWithEmailAndPassword module from firebase/auth |
| `fbi-signInWithEmailAndPassword`     | imports signInWithEmailAndPassword module from firebase/auth     |
| `fbi-signInWithPopup`                | imports signInWithPopup module from firebase/auth                |
| `fbi-signOut`                        | imports signOut module from firebase/auth                        |
| `fbi-onAuthStateChanged`             | imports onAuthStateChanged module from firebase/auth             |
| `fbi-doc`                            | imports doc module from firebase/firestore                       |

#### Firebase Create Snippets

| Snippet                  | Purpose                                                                 |
| ------------------------ | ----------------------------------------------------------------------- |
| `fbc-initApp`            | provides a boilerplate code to initialize firebase app for your project |
| `fbc-regUserEP`          | provides a function to register users using email and password          |
| `fbc-emailPasswordLogin` | provides a function to login users using email and password             |
| `fbc-googleLogin`        | provides a function to sign in users using google                       |
| `fbc-onAuthStateChanged` | provides a hook to monitor if the user is logged in or not              |
| `fbc-logoutUser`         | provides a function to logout signed in user                            |

## Versions

### 1.0.0

Initial release of Firebase-React Snippets. Not all features from firebase are provided as snippets yet. Only the most common features are implemented for now.

---
