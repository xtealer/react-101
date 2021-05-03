# Module 2

- Create React project running on integrated terminal with `yarn create react-app app --template typescript`

- Add some ui and navigation libraries running on integrated terminal with `yarn add antd sass react-router-dom @ant-design/icons && yarn add --dev @types/react-router-dom`

- Create `/src/styles/index.sass` file. Import on `index.tsx` with `import './styles/index.sass'`

- Add import `@import 'antd/dist/antd.css'` on top of `index.sass`

- Create the following sass files stylesheets, import them on `index.sass`: `components`, `ids`, `utils`, `themes`, `tags`

- Set initial style rules by file:

  - `tags.sass`

    ```
    body, html
    	height: 100%
    ```
  
  - `tags.sass`

    ```
    #root
    	height: 100%
    ```
    
  These rules will allow us to work safely with percentages from parent container, instead of `vh`
  
  - Remove clean contents of App.tsx, leave only this code:

   ```
   import React from "react";
   
   interface IProps {}

   const App: FunctionComponent<IProps> = (props) => {
     return (
       <div>app.tsx</div>
     );
   };

   export default App;
   ```
   
   - Verify that `index.tsx` only contains utilized imports, should look something like this:

   ```
   import "./styles/index.sass";

   import React from "react";
   import ReactDOM from "react-dom";
   import App from "./App";
   import reportWebVitals from "./reportWebVitals";

   ReactDOM.render(
     <React.StrictMode>
       <App />
     </React.StrictMode>,
     document.getElementById("root")
   );

   // If you want to start measuring performance in your app, pass a function
   // to log results (for example: reportWebVitals(console.log))
   // or send to an analytics endpoint. Learn more: https://bit.ly/CRA-vitals
   reportWebVitals();
   ```

- Commit and upload changes to github


[<<](https://github.com/xtealer/react-101/blob/main/lessons/module-1.md) -- [>>](https://github.com/xtealer/react-101/blob/main/lessons/module-3.md)
