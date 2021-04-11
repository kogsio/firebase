# firebase
Code for Firebase serverless services - web app.

## Complete before using code
1. Go to firebase, https://firebase.google.com/
1. Sign in
1. Go to console
1. Create new project
1. Select "project settings" add web app
1. Copy JS configuration, you will need it in your code
1. Enable service (e.g. authentication)

## Replace firebaseConfig in code with your project's info
``` 
    var firebaseConfig = {
        apiKey:            "apple",
        authDomain:        "pear",
        projectId:         "grape",
        storageBucket:     "guava",
        messagingSenderId: "kiwi",
        appId:             "peach"
    };
```