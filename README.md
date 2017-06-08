# Getting Started

Super simple Angular App with with server side rendering (Universal)

## Get the Code
```
git clone https://github.com/csilva2810/angular-toh-universal.git toh
cd toh
npm i
```

### Just in Time (JiT) Compilation

Runs the TypeScript compiler and launches the app

```
npm start
```

### Ahead of Time (AoT) Compilation

Runs the Angular AoT compiler, rollup, uglify for an optimized bundle with Webpack, then launches the app

```
npm run build:aot
npm run serve:aot
```

### Server Side Rendering (AoT) Compilation

Runs the Angular Universal on Server Side with nodejs (Express) and returns Compiled HTML from server

```
npm run build:uni
npm run serve:uni
```
