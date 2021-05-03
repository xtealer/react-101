# Module 3

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
  --
  
  `HomeView.tsx`
  
  ```
  import React, { FunctionComponent } from "react";

  interface IProps {}

  const HomeView: FunctionComponent<IProps> = () => {
    return <div>HomeView.tsx</div>;
  };

  export default HomeView;
  ```
  

Build React UI: https://www.figma.com/file/3XD4nphqmRsM4cZgcKdDfg/React-CV?node-id=0%3A1


[<<](https://github.com/xtealer/react-101/blob/main/lessons/module-2.md) -- [>>](https://github.com/xtealer/react-101/blob/main/lessons/module-4.md)
