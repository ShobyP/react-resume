Build the project first.

npm install -g firebase-tools
firebase login
firebase init (this step is not needed if firebase.json is already configured)

example of firebase.json
{
  "hosting": {
    "site": "ssheikh-fire",
    "public": "build",
   }
}

firebase deploy --only hosting:ssheikh-fire