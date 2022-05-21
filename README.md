#### TypeScript - https://www.typescriptlang.org

**`npm install typescript --save-dev`** - naistalovat lokalne typescript   
**`npm install -g typescript`** - naistaluje typescript globalne (velmi nepouzivat)
**`npx tsc`** - spustit lokalnu verziu tsc  
**`npx tsc --init`** - inicializuje typescriptovy projekt (aka vytvori tsconfig.json)  
**`npx tsc -w`** - spusti tsc do watch modu, takze pri zmene sa zmeny prejavia okamzite (command line style)
**`npx tsc --showConfig`** - zobrazi akutalny tsconfig.json

#### tsconfig.json - https://aka.ms/tsconfig.json
uzitocne nastavenie
```
{
  "compilerOptions": {
    "target": "es6",          /* Set the JavaScript language version for emitted JavaScript and include compatible library declarations. */
    "module": "commonjs",     /* Specify what module code is generated. */
    "strict": true,           /* Enable all strict type-checking options. */
    "rootDir": "src",         /* Specify the root folder within your source files. */
    "outDir": "out",          /* Specify an output folder for all emitted files. */
    
    /* this are as defaultt already set so no need explicitly set*/
    "sourceMap": true,        /* Create source map files for emitted JavaScript files. */
    "noEmitOnError": true,    /* Disable emitting files from a compilation. */
    "noImplicitAny": true,    /* Enable error reporting for expressions and declarations with an implied `any` type.. */
    "strictNullChecks": true  /* When type checking, take into account `null` and `undefined`. */
  }
}
```

#### Visual Code
vsetky chybu si viem pozriet v zalozke View/Open view/Problems
