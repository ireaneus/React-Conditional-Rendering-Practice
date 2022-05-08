# React-Conditional-Rendering-Practice
Cool setup a login / Register screen
```js
import React from "react";
import Form from "./Form";

var userIsRegistered = true;

function App() {
  return (
    <div className="container">
      <Form isRegistered={userIsRegistered} />
    </div>
  );
}

export default App;

########################
# form.js

Created with CodeSandbox
