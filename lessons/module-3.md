# Module 3 - Build UI

1. Create the following `/src/views` files:

  `NotFoundView.tsx`

  ```
  import React, { FunctionComponent } from "react";

  interface IProps {}

  const NotFoundView: FunctionComponent<IProps> = (props) => {
    return (
      <div>
        <h1>Ruta No Encontrada.</h1>
      </div>
    );
  };

  export default NotFoundView;
  ```
  
  `HomeView.tsx`
  
  ```
  import React, { FunctionComponent } from "react";

  interface IProps {}

  const HomeView: FunctionComponent<IProps> = () => {
    return <div>HomeView.tsx</div>;
  };

  export default HomeView;
  ```
  
2. Setup initial navigation on `App.tsx`, replace entire file content with code below:

  ```
  import React, { FunctionComponent } from "react";
  import { BrowserRouter as Router, Switch, Route } from "react-router-dom";

  // imported views
  import HomeView from "./views/HomeView";
  import NotFoundView from "./views/NotFoundView";

  interface IProps {}

  const App: FunctionComponent<IProps> = (props) => {
    return (
      <Router>
        <Switch>
          <Route exact path="/">
            <HomeView />
          </Route>

          <Route path="/">
            <NotFoundView />
          </Route>
        </Switch>
      </Router>
    );
  };

  export default App;
  ```

3. Build UI From Figma Design: https://www.figma.com/file/3XD4nphqmRsM4cZgcKdDfg/React-CV?node-id=0%3A1

5. Commit changes to github


[<<](https://github.com/xtealer/react-101/blob/main/lessons/module-2.md) -- [>>](https://github.com/xtealer/react-101/blob/main/lessons/module-4.md)
