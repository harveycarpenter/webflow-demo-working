# demoApp

This is the most minimal version I could get of a Webflow extension demonstrating webflow.createDOM().

You should be able to select an element on the canvas, click the button, and see no errors logged in the console.

It doesn't actually insert anything.

## Developing

```
$ npm run dev
```

The above command does a few things:
* Installs dependencies
* Spins up a process that serves your extension files from under `public/`

The command outputs the URL under which your extension is being served. Use this as the “Development URL” for your app in the Webflow Designer’s Apps panel. You can then launch the extension from the same place.