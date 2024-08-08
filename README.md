# QuickStart

`pnpm install`  
`pnpm dev`

# Error Reproduction

- Start the SolidStart dev server and goto `http://localhost:3000`.
- Disable Javascript and reload.
- The button color is now red because the CSS selector `&:is(button)` is getting encoded as `&amp;:is(button)` on server side. Client side works fine.
