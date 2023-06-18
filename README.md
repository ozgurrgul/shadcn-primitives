# Shadcn primitives


## Installation

Install the package via following command.

```
npm i shadcn-primitives
```

or 

```
yarn add shadcn-primitives
```

Load CSS from node_modules as well:

```
import "shadcn-primitives/dist/style.css";
```

## Example usage

``` tsx
import { Button } from "shadcn-primitives";
import "shadcn-primitives/dist/style.css";

export const Test = () => (
  <div>
    <Button>Button</Button>
  </div>
);

```

## Font style

Alternatively, you can set the `font-family` to `Inter` and have a slick font. Put this in your main css file:

``` css
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');

:root {
  --font-sans: 'Inter', sans-serif;
}

```

## Theme customize

You can override style with following CSS variables defined by shadcn:

``` css
:root {
    --background: 0 0% 100%;
    --foreground: 222.2 47.4% 11.2%;
 
    --muted: 210 40% 96.1%;
    --muted-foreground: 215.4 16.3% 46.9%;
 
    --popover: 0 0% 100%;
    --popover-foreground: 222.2 47.4% 11.2%;
 
    --card: 0 0% 100%;
    --card-foreground: 222.2 47.4% 11.2%;
 
    --border: 214.3 31.8% 91.4%;
    --input: 214.3 31.8% 91.4%;
 
    --primary: 222.2 47.4% 11.2%;
    --primary-foreground: 210 40% 98%;
 
    --secondary: 210 40% 96.1%;
    --secondary-foreground: 222.2 47.4% 11.2%;
 
    --accent: 210 40% 96.1%;
    --accent-foreground: 222.2 47.4% 11.2%;
 
    --destructive: 0 100% 50%;
    --destructive-foreground: 210 40% 98%;
 
    --ring: 215 20.2% 65.1%;
 
    --radius: 0.5rem;
  }
 
  .dark {
    --background: 224 71% 4%;
    --foreground: 213 31% 91%;
 
    --muted: 223 47% 11%;
    --muted-foreground: 215.4 16.3% 56.9%;
 
    --popover: 224 71% 4%;
    --popover-foreground: 215 20.2% 65.1%;
 
    --card: 224 71% 4%;
    --card-foreground: 213 31% 91%;
 
    --border: 216 34% 17%;
    --input: 216 34% 17%;
 
    --primary: 210 40% 98%;
    --primary-foreground: 222.2 47.4% 1.2%;
 
    --secondary: 222.2 47.4% 11.2%;
    --secondary-foreground: 210 40% 98%;
 
    --accent: 216 34% 17%;
    --accent-foreground: 210 40% 98%;
 
    --destructive: 0 63% 31%;
    --destructive-foreground: 210 40% 98%;
 
    --ring: 216 34% 17%;
 
    --radius: 0.5rem;
  }
  ```

  Have fun!

- Shadcn: https://ui.shadcn.com/
- Tailwind: https://tailwindcss.com/

