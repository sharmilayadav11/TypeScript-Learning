# TypeScript-Learning
TypeScript is basically js but with type support.In js there is no type support. So when you declare some variable we need to declare it in beginning, but this was missing in js. 
So we can say" TypeScript is javascript with syntax for type.

Why TS: 
    Avoid bug in development.;
    Increase development speed;(It might seems time consuming in beginning but later it is fast as it has auto completion.)
    It has alots of additional feature like:properties modifier, enoms, interfaces


We cant run the code in production, we need to convert all the code to javascript and then it run. So at the last it is converted to JS.

Terminal Notes:
    1. npm init (will create package.md)
    2. creat dir src, and file index.ts
    3. in Package json file:
        "scripts": {
    "test": "ts-node src/index.ts"
  },

  4. copy folder tsconfig.json from another folder typescrip wale.
  5. write code in index file.
  6. To run: npm run test
  7. if you use another than index.ts file :suppose file name is test.ts:  then write this to terminal to run that file:
  ts-node src/test.ts
  7. To clear terminal : clear  
  
  
