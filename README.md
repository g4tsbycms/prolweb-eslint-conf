# prolweb-eslint-conf

## libs included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Configs

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @prolweb/eslint-conf
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@prolweb/eslint-conf/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @prolweb/eslint-conf
```
Inside `.eslintrc.json`
```
{
  "extends": "@prolweb/eslint-conf/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @prolweb/eslint-conf
```
Inside `.eslintrc.json`
```
{
  "extends": "@prolweb/eslint-conf/node"
}
```
credit: diego3g
