# Copy and Pay CSS for Peach Payment

Payment UI for Peach Payment needs improvement. This is now to change the UI.

From this:

<img width="490" alt="Screenshot 2023-12-26 at 23 12 56" src="https://github.com/eznix86/peach-payment-copy-and-pay-css/assets/26553194/323b128c-5ac4-4613-8f73-9df0673e359a">

To this:

<img width="513" alt="Screenshot 2023-12-26 at 23 13 28" src="https://github.com/eznix86/peach-payment-copy-and-pay-css/assets/26553194/c320f8a7-cdd7-4a16-b484-598fd38b1567">

First of all, configure the style so it is plain. 

```javascript
var wpwlOptions = {style: "plain"}
```

Then, Copy and Paste this into your CSS area!

```css
/* Reset styles */

*,
*::before,
*::after {
  box-sizing: border-box;
}

* {
  margin: 0;
  padding: 0;
}

body {
  line-height: 1.5;
  -webkit-font-smoothing: antialiased;
  font-family: "Inter var", system-ui, sans-serif; 
  -webkit-text-size-adjust: 100%;
  tab-size: 4;
  font-variation-settings: normal;
  font-family: "Inter var", ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
}

/* Base styles */

img,
picture,
video,
canvas,
svg {
  display: block;
  max-width: 100%;
}

input,
button,
textarea,
select {
  font: inherit;
}

p,
h1,
h2,
h3,
h4,
h5,
h6 {
  overflow-wrap: break-word;
}

#root,
#__next {
  isolation: isolate;
}

/* Custom styles */

:root {
   --tw-bg-opacity: 1;
   --tw-ring-offset-width: 0px;
   --tw-ring-offset-color: #fff;
   --tw-ring-opacity: 1;
   --tw-text-opacity: 1;
   --tw-shadow-color: rgb(0 0 0 / .05);
   --tw-shadow: 0 1px 2px 0 rgb(0 0 0 / 0.05);
   --tw-shadow-colored: 0 1px 2px 0 var(--tw-shadow-color);
   --tw-ring-offset-shadow: var(--tw-ring-inset) 0 0 0 var(--tw-ring-offset-width) var(--tw-ring-offset-color);
   --tw-ring-shadow: var(--tw-ring-inset) 0 0 0 calc(1px + var(--tw-ring-offset-width)) var(--tw-ring-color);
   --tw-ring-inset: inset;
   --tw-ring-color: rgb(209 213 219 / var(--tw-ring-opacity));
}

.wpwl-label {
    box-sizing: border-box;
    border-width: 0px;
    border-style: solid;
    border-color: rgb(229, 231, 235);
    display: block;
    font-size: 0.875rem;
    font-weight: 600;
    line-height: 1.5rem;
    color: rgb(17 24 39 / var(--tw-text-opacity));
}

.wpwl-control {
    font-variation-settings: normal;
    box-sizing: border-box;
    border-style: solid;    
    font-family: inherit;
    font-weight: inherit;
    margin: 0px;
    appearance: none;
    background-color: rgb(255, 255, 255);
    border-color: rgb(107, 114, 128);
    font-size: 1rem;
    line-height: 1.5rem;
    display: block;
    width: 100%;
    border-radius: 0.375rem;
    border-width: 0px;
    padding-left: 0.875rem;
    padding-right: 0.875rem;
    padding-top: 0.5rem;
    padding-bottom: 0.5rem;
    color: rgb(17 24 39 / var(--tw-text-opacity));
    box-shadow: var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow, 0 0 #0000);
}

button {
    user-select: none;
    font-size: .8125rem;
    line-height: 1.25rem;
    color: rgb(15 23 42 / var(--tw-text-opacity));
    box-sizing: border-box;
    border-width: 0;
    border-style: solid;
    border-color: #e5e7eb;
    pointer-events: auto;
    border-radius: .375rem;
    padding-left: 1rem;
    padding-right: 1rem;
    padding-top: .5rem;
    padding-bottom: .5rem;
    text-align: center;
    font-weight: 500;
    box-shadow: var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow, 0 0 #0000);
}

.wpwl-control-brand {
   display: none;
 }

```
