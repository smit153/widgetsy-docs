# Usage Examples

Here are a few usage examples that demonstrate how to utilize the components provided by the 'Widgetsy' library:

## Clock Widget

Render a clock widget with a custom background gradient:

```bash
import React from 'react';
import { Clock } from 'widgetsy';

function App() {
  return (
    <div>
      <h1>Welcome to My App!</h1>
      <Clock
        backgroundColor={[
          { color: '#003973', stop: 0 },
          { color: '#a6a679', stop: 100 },
        ]}
        rotation={45}
        primaryFont="#FFFFFF"
        primaryColor="#000000"
      />
    </div>
  );
}

export default App;
```

This example showcases how to set a background gradient, rotation, and primary font and color for the clock widget.

## Calculator Widget

Include a calculator widget with a specific primary color and font color:

```bash
import React from 'react';
import { Calculator } from 'widgetsy';

function App() {
  return (
    <div>
      <h1>Welcome to My App!</h1>
      <Calculator
        backgroundColor={[
          { color: '#003973', stop: 0 },
          { color: '#a6a679', stop: 100 },
        ]}
        rotation={0}
        primaryFont="#00FF00"
        primaryColor="#FF0000"
      />
    </div>
  );
}
```

This example showcases how to set a background gradient, rotation,and primary font and color for the calculator widget.

## Calendar Widget

Render a calendar widget with a pre-built theme:

```bash
import React from 'react';
import { Calendar } from 'widgetsy';

function App() {
  return (
    <div>
      <h1>Welcome to My App!</h1>
      <Calendar
        theme={2}
        primaryFont="#000000"
        primaryColor="#FFFFFF"
      />
    </div>
  );
}
```

This example showcases how to set aTheme primary font, and primary color for the calendar widget.
