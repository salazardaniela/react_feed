# React Feed

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.
# ToDo
- [X] Research Server side rendering `(1h)`
- [ ] Research loading [Ryan Gyggs site](https://www.ryangiggs.cc/) `(1h)`
- [ ] Implement Server side rendering `(XX)`
- [ ] Implement loading `(XX)`
- [X] Create React App `(2h)`
- [ ] Based on [this website](https://studiochapeaux.com/)
    - Three main Categories are: cat, dog and pig
    - The page wont have background color
    - [ ] There are three differente URLs `(2h)`
    - [ ] If the user try a not supported URL a 4o4 should be displayed `(3h)`
    - [ ] The phrases will be static content from a Json File by category `(4h)`
    - [ ] The root page will load a random phrase from any of the available categories `(3h)`
    - [ ] Each URLs will filter based in the category name `(2h)`
    - [ ] The site should have a animated Menu icon as the website example and show the options with the hover `(4h)`
    - [ ] The content will be an animated phrase as the example `(6h)`
    - [ ] The content will support all viewports and the text needs to be centered, vertically and horizontally and the text never will be cut off `(4h)`
    - [ ] The color palette will be randomly loaded based in a list predefined, minimun 3 [use this](https://colorhunt.co/) as inspiration `(XX)`:
        - One color for Text
        - One for text hover
        - One for menu
        - One for menu hover
    - [ ] Create a menu at the bottom of the site to write the copyright and the github user name link `(3h)`

# Future Stage
- Translate the content based in IP
- The background of the page will be the lightest color of the selected palette

## Server side Rendering:

To discuss server-side rendering, it's essential to understand how React functions. React builds responsive applications using the Single Page Application (SPA) model.

An SPA is a website or web application that dynamically updates the current web page with new data from the web server. This is where server-side rendering plays a crucial role in making the app more agile and dynamic.

Server-side rendering (SSR) refers to an application's ability to convert HTML files on the server into fully rendered HTML pages for the client. When a web browser requests information from the server, the server promptly responds by sending a fully rendered page to the client. In this process, the website's JavaScript is executed on the server, allowing a fully rendered page to be delivered to the client. Subsequently, the client's JavaScript bundle activates, enabling the Single Page Application framework to function effectively.
