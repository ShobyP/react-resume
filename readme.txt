Build the project first.

npm install -g firebase-tools
firebase login
firebase init
    public directory will be build.
    Y
    N
{
  "hosting": {
    "site": "ssheikh-fire",
    "public": "public",
   }
}

firebase deploy --only hosting:ssheikh-fire