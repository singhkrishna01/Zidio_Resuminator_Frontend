## Live Demo ->
![Resuminator](https://i.ibb.co/N19g2cM/Screenshot-2024-06-17-174042.png)
<hr>

## Run the Project
Now that you have setup the repository correctly, the next thing we will focus on is how to configure your frontend for it to be up and running and ready to receive requests from the backend server.

#### 1 - Install all the dependencies on your local system using the command given below.
<blockquote> npm install </blockquote>

#### 2 - We now need to configure the local environment variables which are required for external services Resuminator uses (like Firebase)
For that in your root folder create a new file named .env.local and copy the configuration below to it. Replace the required values with your own account configurations.
```
NEXT_PUBLIC_API_BASE_URL="http://localhost:PORT"

NEXT_PUBLIC_API_KEY='YOUR_FIREBASE_API_KEY'
NEXT_PUBLIC_AUTH_DOMAIN='YOUR_FIREBASE_AUTH_DOMAIN'
NEXT_PUBLIC_PROJECT_ID='YOUR_FIREBASE_PROJECT_ID'
NEXT_PUBLIC_STORAGE_BUCKET='YOUR_FIREBASE_STORAGE_BUCKET_ADDRESS'
NEXT_PUBLIC_MESSAGING_SENDER_ID='YOUR_FIREBASE_MESSAGING_SENDER_ID'
NEXT_PUBLIC_FIREBASE_ID='YOUR_FIREBASE_APP_ID'
```

#### 3 - Finally once you have your .env.local configurations file in place, you can start the frontend using the following command.
<blockquote>npm run dev</blockquote>
