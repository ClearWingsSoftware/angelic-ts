# angelic-ts
Angelic TypeScript is a highly customizable library for use with React and Next projects in order to achieve dynamic, versatile, and efficient css styling. While designed to be as user-friendly as possible, the library assumes a familiarity with React and TypeScript arrow functions in order to fully utilize.

## Setup

## Adding and Changing Simple Styles
After importing your ```AngelicStyler``` to whichever file you want to edit it in, you can use methods of the object to interact with it and start giving styles to your page. By default, you can use HTML id's, classes, and element types in order to specify where the styles with apply to, just as if you were writing CSS. Later on, we will discuss how to create custom categories. We will also discuss the benefits of modularizing your component's returns, but for the moment we will consider the following simple component:
```typescript
import MyComponentStyler from "./stylers/my-component-styler";
import React from "react";

const MyComponent:React.FC<{}> = (props:{}) => {
  return (

  )
}
```

## Adding and Removing Pre-made Relations

## Adding and Changing Simple Custom Relations

## Creating Style Templates and Application-Wide Defaults

## Creating Categories of Elements

## Creating Advanced and Many-Element Relations
