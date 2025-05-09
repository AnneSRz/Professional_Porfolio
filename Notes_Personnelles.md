# Notes Personnels

### Initial Set-Up

Make sure Node.js is installed nad added to system PATH variables 

1. Open the terminal and type  : npm create vite@latest
2. Name the profect
3. Set the project framework to : React
4. Set the project variant to JavaScript
5. Run the project with : 

```
cd project-name
npm install
npm install @fontsource/roboto @fontsource/outfit
npm run dev
```
The npm install commands install the dependencies we need to run the REACT Project
**npm run dev** ; run the project locally it will give us an adress that we can paste in the browser and it shows the react project we (will) create

Then we need to take the 2 fonts that we install and introduce it to the project:
Go to the main.jsx file, then write :

```
import 'fontsource/roboto'
import 'fontsource/outfit'
```

Multiple files that will be created for us, but most of them will not be used. Therefore, we can optionally delete the following files to startwith a clean structure : 
1. vite.svg and react.svg
2. Delete **the content** of App.css 
3. Delete **the content** of index.css, but we keep this structure to start:
```
import './App.css'

function App() {

  return (
    <>
      Hello world!
    </>
  )
}
export default App
```
4. Remove the content of index.css


Then change the tile in **index.html**