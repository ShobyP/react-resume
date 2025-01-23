Build the project first.

npm install -g firebase-tools
firebase login
firebase init (this step is not needed if firebase.json is already configured)

example of firebase.json
{
  "hosting": {
    "site": "resume-ssheikh",
    "public": "build",
   }
}

Currently, just run the following command in windows cmd.
configurtion will build the project and deploy it.
firebase deploy --only hosting:resume-ssheikh