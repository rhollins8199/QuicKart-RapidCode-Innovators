![modified](https://img.shields.io/github/last-commit/KWilliams-dev/QuicKart)
![contributors](https://img.shields.io/github/contributors/KWilliams-dev/QuicKart)
![topLanguage](https://img.shields.io/github/languages/top/KWilliams-dev/QuicKart?label=top%20language)
![languageCount](https://img.shields.io/github/languages/count/KWilliams-dev/QuicKart?label=language%20count)

# QuicKart
This is the GitHub repo for the team working on the QuicKart mobile android application. The goal is to enable users to enhance their shopping experience with an app that can give them the fastest route to their items within the store.

The project repository can be found [here](https://github.com/KWilliams-dev/QuicKart).

## Build Instructions
 
<strong>1.</strong> Clone the repository into your local machine.
<strong>2.</strong> Ensure that you have nodejs and npm installed with the following commands: (You should see something like "v16.13.2")
```
node -v
```
```
npm -v
```
- ### <em><strong>Note</strong></em>
&nbsp; &nbsp; &nbsp; If your running a different version of node and run into issues with this project. I'm currently running NodeJS v16.13.2 and npm v8.12.1. Installing those specific versions may help.


<strong>3.</strong> Use the cd command in the terminal of your project directory to get into src and then view. 
Ex:
```
cd src/view
```
<strong>4.</strong> This will take you into where the front end portion of the project lives. At this point run
```
npm install 
```
<strong>5.</strong> After that, you'll need to set up the back end portion of project following similar steps
```
cd src/model
npm install
```
- ### <em><strong>Note</strong></em>
&nbsp; &nbsp; &nbsp; After completing these steps, the project will not be running but you will have node_modules directory built and the dependencies that the
project relies on ready to go.

# Running the project

## Front End

- ### <em><strong>Note</strong></em>
&nbsp; &nbsp; &nbsp; I recommend going over some of the docks on this website https://docs.expo.dev/ and also testing out expo in the browser here https://snack.expo.dev/ to familiarize yourself with the technology. There will be some account creation involved.

To run the front end of the project, make sure you're in the view directory in your terminal and then run the command
```
npm run web
```
You'll see a QR code pop up in your terminal. If your on an iphone, just download the Expo Go app from the app store, and scan it with your camera.
On android, I believe you need to scan the QR code from the expo go app. The Expo Go icon looks like the picture below:

![image](https://user-images.githubusercontent.com/74102531/199377266-36155398-a05e-4406-a16d-ccb360cfcfe3.png)

## Backend

The backend of the project uses MongoDB, GraphQL and Apollo server. Much of the set up is already done, you'll just need to make sure to follow the build
instructions first and run ``` npm install ``` in the src/model directory first.

- Apollo docs: https://www.apollographql.com/docs/apollo-server/getting-started/
- GraphQL docs: https://graphql.org/learn/
- MongoDB docs: https://www.mongodb.com/docs/manual/

You may also want to reference some of the same YouTube tutorials we followed. Our strategy was to build the app from the tutorial first and then use what we
learned to begin building QuickKart.

- YouTube tutorial Part 1 (Backend): https://www.youtube.com/watch?v=hPBVIET5coo&list=RDCMUCYSa_YLoJokZAwHhlwJntIA&index=2
- YouTube tutorial Part 2 (Frontend): https://www.youtube.com/watch?v=GFQDJlVEXRg&list=RDCMUCYSa_YLoJokZAwHhlwJntIA&index=1

## Installation

## Usage

## Communications
The team used JIRA as our project progess tracking tool alongside Discord and Microsft Teams as our primary communication tool and meeting platform.

## Authors
1. Abdullahi Munye :alien: - **Data Modeler**
2. Khamilah Nixon :page_with_curl: - **Documentation Lead**
3. Kyle Williams :fire: - **Code Architect**
4. Alan Oliver 🕴️ - **Team Manager**
5. Joe Nsengiyumva :hatching_chick: - **Testing Lead**
6. Raven Gardner :seedling: - **UX/UI Lead**

## License
