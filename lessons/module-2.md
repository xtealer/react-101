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

- Commit and upload changes to github


[<<](https://github.com/xtealer/react-101/blob/main/lessons/module-1.md) -- [>>](https://github.com/xtealer/react-101/blob/main/lessons/module-3.md)
