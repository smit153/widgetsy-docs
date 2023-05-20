# Quick Start

Follow these steps to quickly integrate and use the 'Widgetsy' library in your React project:

## Imports

Import Widgetsy components into your project. In your desired component file, import the required widgets as shown below:

```bash
import { Clock, Calculator, Calendar } from 'widgetsy';
```

Ensure that you have the appropriate build setup (such as using Babel or webpack) to support importing React components.

## Rendering Components

Use the imported components within your JSX code. For example, you can render the 'Clock' component as follows:

```bash
import React from 'react';
import { Clock } from 'widgetsy';

function App() {
return (
    <div>
        <h1>Welcome to My App!</h1>
        <Clock />
    </div>
  );
}

export default App;
```

You can similarly render the 'Calculator' and 'Calendar' components by including them in your JSX code.

Congratulations! You have successfully integrated the 'Widgetsy' library into your React project. You can now customize and utilize the available components based on your requirements.
