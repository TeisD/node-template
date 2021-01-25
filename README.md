Template for Node.js projects in typescript

## Scripts
`yarn run start` Build and run

`yarn run build` Build

`yarn run debug` Watch for changes with nodemon and start a debugging session that can be attached to

## Typing
If an imported module has no type declarations, the compiler will throw an error `TS7016`.

First try if the types are available `yarn add @types/<module_name> -D`

Alternatively create a file named `<module_name>/index.d.ts` in `/typings` containing `declare module '<module_name>'`