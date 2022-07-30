# BitKit

![bitkit](https://user-images.githubusercontent.com/81036521/181904178-f05cdacb-d5a2-4c8a-a714-3af5438a517f.JPG)


#
## Introduction.

This is a Full Stack Application using Next.js, Node.js, sanity the app is called BitKit and it is a simple short video sharing social media platform that allows users to post photo, video, gif and etc and also allows user to like, comment, search and user can see who have posted the posts this project have many more different feature.
#
## Installation and Setup.

 ```bash
For instalation of packages run: npm i or npm install
# and
To run the project run: npm run dev
# and
to run sanity-backend run:
1. open terminal in sanity-backend folder
2. to open in sanity-backend folder run: cd sanity-backend
3.to run sanity run: sanity start
# and 
change the .env.developement credenditials of:
NEXT_PUBLIC_SANITY_TOKEN, (You will get sanity token from your projects sanity dashboard In API in Tokens)
NEXT_PUBLIC_GOOGLE_API_TOKEN, (You will get this from googles cloud yours projects CLIIENT ID)
# and
changes:
change your project id in utils > client.ts: projectId: '<YOUR_PROJECTID>', (You will get this from yours projects sanity dashboard).

CORS ORIGINS : changes CORS origin in your sanity dashboars in API in CORS origins and also in the google console.google.cloud your apps CORS

FOR CLIENT ID of google login: create your goole credentials in console.google.cloud create your OAuth client and copy thee google client id and paste it in env.developement in NEXT_PUBLIC_GOOGLE_API_TOKEN.
```

I am a learner so my readme is a bit messy
please change the credencials of mine to yours i may change the setup of my dashboar and it may lead an error in your project
Thank You
#
