# OneMoreTextEditor

Imagine a text editor that’s always at your fingertips, no matter where you are or whether you have an internet connection. This browser-based text editor is designed as a single-page application, seamlessly blending the speed and accessibility of a web app with the reliability of offline functionality. Built to meet Progressive Web App (PWA) standards, this editor ensures that your work is not just quick and easy to access but also safely stored through multiple data persistence strategies. With this app, you can focus on your writing, knowing that your work is always safe and ready * WHEN you need it.


## User Story

AS A developer <br>
I WANT to create notes or code snippets with or without an internet connection<br>
SO THAT I can reliably retrieve them for later use


## Acceptance Criteria

GIVEN a text editor web application<br>
* WHEN I open my application in my editor<br>
THEN I should see a client server folder structure
* WHEN I run `npm run start` from the root directory<br>
THEN I find that my application should start up the backend and serve the client
* WHEN I run the text editor application from my terminal<br>
THEN I find that my JavaScript files have been bundled using webpack
* WHEN I run my webpack plugins<br>
THEN I find that I have a generated HTML file, service worker, and a manifest file
* WHEN I use next-gen JavaScript in my application<br>
THEN I find that the text editor still functions in the browser without errors
* WHEN I open the text editor<br>
THEN I find that IndexedDB has immediately created a database storage
* WHEN I enter content and subsequently click off of the DOM window<br>
THEN I find that the content in the text editor has been saved with IndexedDB
* WHEN I reopen the text editor after closing it<br>
THEN I find that the content in the text editor has been retrieved from our IndexedDB
* WHEN I click on the Install button<br>
THEN I download my web application as an icon on my desktop
* WHEN I load my web application<br>
THEN I should have a registered service worker using workbox
* WHEN I register a service worker<br>
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
* WHEN I deploy to Render<br>
THEN I should have proper build scripts for a webpack application

## Go to my project
  
You can take a look at the app [here](https://onemoretexteditor.onrender.com)

Or visit my repository [here](https://github.com/VanZittle/OneMoreTextEditor)

## Visual reference of project
The following image demonstrates the app's appearance:
  
![gif reference](./assets/image-reference.gif)

## License
![GitHub](https://img.shields.io/github/license/VanZittle/OneMoreTextEditor?style=for-the-badge)<br> Go to license [here](https://github.com/VanZittle/OneMoreTextEditor/blob/main/LICENSE)
  
Markdown generated with **[README Creator](https://github.com/VanZittle/module9-challenge-ReadmeGenerator)**
