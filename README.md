# S.L.A.T.E.-Text-Editor

## Description
This text editor is a progressive web applicaton that runs in the browser.  Written on a Node.js runtime environment, it utilizes an Express framework, IndexedDB storage, workbox service workers, and webpack to allow create a single-page application that can run even if certain options are not supported by the user's browser.


## Instructions
This app is browser-based, and a deployed link can be found at https://slate-text-editor.herokuapp.com/.

On the back-end, all that needs to be installed is Express and a package called 'ibd', which serves as a lightweight wrapper around the IndexedDB API.

PLEASE NOTE that debugging is currently underway, as an error between versions of different packages became apparent during development.  In order to view the functionality of this app, please go through the following steps: 
    1. Open up your browser's DevTools on the page
    2. Navigate to the application tab and delete all storage
    3. Refresh the browser
    4. Add text of your choosing
    5. Navigate back to the application tab and open IndexDB
    6. Click the button to refresh database

## Contact Me
Sam Larson
- samlarson94@gmail.com
- https://github.com/samlarson94