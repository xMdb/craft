# craft - Design mockup

craft (or craftlang) is a website for a fake programming language that I came up with. It doesn't exist. However, [craftlang](https://github.com/craftlang/craftlangc) does exist.

## Design

I designed this in Figma, and built it using TailwindCSS.
         <div style="display: flex">
         <img
            src="https://user-images.githubusercontent.com/46137770/133070659-49747cbd-a40d-4b14-99c9-919bf80166f6.jpg"
            alt="Main Header"
            width="450"
            height="300"
         />
         <img
            src="https://user-images.githubusercontent.com/46137770/133070663-af162ffc-8b36-40b2-9893-092dbfe48a28.jpg"
            alt="Why Section"
            width="450"
            height="300"
         />
         <img
            src="https://user-images.githubusercontent.com/46137770/133070668-23d60444-4b66-4a80-af96-b9edcb22f9e7.jpg"
            alt="Install Section"
            width="450"
            height="300"
         />
         </div>

## Build

To build this in a development environment, use `npm run dev`. This adds a lot unneeded of CSS to the output file ([learn more here](https://tailwindcss.com/docs/optimizing-for-production)).

To build for production, use `npm run build`. This tree-shakes the unneeded CSS to make it much smaller.

## View

You can view the website [here](https://craft-mockup.netlify.app/).
