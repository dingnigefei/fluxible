# Quick Start

 ```bash
npm install -g yo generator-fluxible
 ```

To use the generator, create a directory and cd into it. Then run `yo fluxible` which will create a working Fluxible application. To start the application, run `npm run dev`. View it in a browser at http://localhost:3000.

```bash
mkdir example && cd example
yo fluxible
npm run dev
```

`open http://localhost:30001`

This will generate a simple application that demonstrates the basics of using Fluxible: routing, store dehydration from server, and client rehydrating.

From here, we recommend learning about [stores](api/Stores.md), [actions](api/Actions.md), and React integration with your [components](api/Components.md).
