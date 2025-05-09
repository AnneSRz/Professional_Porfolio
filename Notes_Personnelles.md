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
import @fontsource/roboto 
import @fontsource/outfit
```

There is multiple files that will be created for us, but we wont use most of them. So we can delete : 
1. Delete vite.svg
2. Delete assets porfolio
3. Delete most of **the content** of App.css but we keep this structure :
```

```
4. Delete **the content** of index.css