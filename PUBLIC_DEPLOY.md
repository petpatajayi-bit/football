# Make it work worldwide

The app is ready to deploy. Publishing is the step that gives people in different countries a shared HTTPS address.

## Deploy with Render

1. Create a GitHub account at https://github.com/ if you do not already have one.
2. Create a new repository named `true-salvation-military`.
3. Upload every file in this folder, including `Dockerfile`, `render.yaml`, `package.json`, `package-lock.json`, `server.js`, `index.html`, `styles.css`, and `script.js`.
4. Create an account at https://render.com/ and choose **New > Blueprint**.
5. Connect the GitHub repository.
6. Click **Apply** and wait for the deploy to finish.
7. Open the HTTPS URL Render gives you. That is the link you send to people in any country.

The server terminal on your computer does not need to stay open after Render deploys it.

## Before inviting everyone

Open the URL on two phones or computers and test chat, pictures, emoji, and calls. Camera and microphone permissions require the HTTPS Render URL. This app has no access control, so anyone with the URL can use it.

For calls on restrictive mobile or workplace networks, add a TURN server and set its credentials in the WebRTC `iceServers` list in `script.js`. Without TURN, calls usually work on the same network and many normal networks, but not every carrier or firewall.
