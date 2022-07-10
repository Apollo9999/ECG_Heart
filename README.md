# NexTron Heart NFTs


![alt text](https://github.com/drraghavendra/Nextron_ECG/blob/main/zil-heartbeat-nft-main/doc-img/LOGO%20B2.jpg)

# Project Overview
A web dashboard using gamification & blockchain technology to incentivize positive heart health!
- User's “mint” their ECG data to earn an exclusive non-fungible token named Heart NFT.
- If they so choose, this digital token and the encrypted data it represents can be held or “burned” for future discounts on healthcare services or insurance premiums.
![alt image](https://github.com/drraghavendra/Nextron_ECG/blob/main/zil-heartbeat-nft-main/doc-img/nextron1.PNG)

project  objective for this hackathon is to design,develop and deploy a full operative and working web-application that rewards users sharing us their ECG images. What we hope to show is a simulation/demo of our software reading  the signals of an ECG that user shares and "minting" this data into a non-fungible token or NFT. 


![alt image](https://github.com/drraghavendra/Nextron_ECG/blob/main/zil-heartbeat-nft-main/images/patient%20ECG%20details.png)

1)	Keep patient name and timestamp 
2)	Change profile picture to an older woman
1)Doctor recommendations/send results to doctors to receive funds button- smart notes and let the patient know that the doctor did see what was going on (interaction with doctor)- show that information was shared with doctor and they earned X amount in ZIL
2)The current ECG NFT that was taken this run with the payout details (more detailed than just red line as shown above)
3) Below the current ECG  NFT

User mints their ECG data as NFT and sells it to doctors, researchers, or anyone on our NexTron network




As this data contains the heart rate/ECG data of an individual  more specifically, we will capture 640 images for each NFT, acting as a "proof of health" creating an exclusive token/point system that we can either use to ensure adherence of patients for doctors or create a similar "competitive/leaderboard".
![alt image](https://github.com/drraghavendra/Nextron_ECG/blob/main/zil-heartbeat-nft-main/doc-img/nextron2.PNG)


# Project working details 

What we are currently working to deploy is a web-application that rewards users sharing us  their healthy ECG data. What we hope to show is a simulation/demo of our software reading  the signals of an ECG using an USB port and "minting" this data into a non-fungible token or NFT. As this data contains the heart rate/ECG data of an individual (more specifically, we will capture 640 images) each NFT acts as a "proof of health" creating an exclusive token/point system that we can either use to ensure adherence of patients for doctors or create a similar "competitive/leaderboard".

We already have the majority of the code from the hardware (ECG made out of an Arduino) and software (a basic simulation of a collection of ECG images and minting of it on the Zilliqa blockchain).

# Hardware 

The firmware for the arduino computer can be found in the arduino directory of the github project.
The application is a javascript project using current version of node.js. It must be hosted locally because a connection to the USB port is needed.



# Tech Stack
Front-end: ReactJS
Built on the Zilliqa blockchain (Scilla smart contract)
Uses IPFS (nft-stroage) to store and mint user Heart NFTs  

# Instructions to get Started with  React App in Client Folder

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)



## Application Execution after  Frontend React App  done


Before running the application the NFT you must:

1. deploy the NFT contract on
Zilliqa (see the `zrc` directory)

2. create an account on https://nft.storage/service

3. edit the `secrets.js` file (use `secrets.js.example` as a
template). It is necessary to fill-in the account name, the private
key and an apiKey for the https://nft.storage/ storage service.


```
npm start
```
Then the UI can be accessed from a browser on http:localhost:3000 . The application displays an input form.



In the project directory, you can run: `npm start`

## Deploy

`npm install -g serve`
`npm i`
`npm run build`
`serve -s build`

0xB0EA149212Eb707a1E5FC1D2d3fD318a8d94cf05
106124913087373027493541693314242265135141833367690973383314684153082811514881





Powerpoint presentation available here https://github.com/drraghavendra/Nextron_ECG/blob/main/NEXTRON.pptx
