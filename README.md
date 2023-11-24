## What is this?

This is the first npm package from M.Habib based on ESM

## Installation:

Run `npm i sm-say-hello`

## Use:

```js

// importing inside node project.

import { sayHi } from 'sm-say-hello'

console.log(sayHi());


// importing inside browser

<!DOCTYPE html>
<html lang="en">
<head>

    <script type="module">

        import { sayHi } from './node_modules/sm-say-hello/module.js'
        
        console.log(sayHi("sdfasdf"));

    </script>

</head>
<body>
    
</body>
</html>
```

## Parameters:

The sm-say-hello accepts one parameter called `msg`.

By default, `Hi There! from sm-say-hello npm package`
