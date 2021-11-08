# @nrosenstein/ts-utils

Various stuff implemented in TypeScript.

## Contents

---

### `@nrosenstein/ts-utils/dataframe`

A `DataFrame` class inspired by Pandas, with minimal features.

__Quickstart__

```ts
import { DataFrame } from "@nrosenstein/ts-utils/dataframe";

let df = new DataFrame([[1, 2, 3], {4, 5, 6]], ["col1", "col2", "col3"]);
console.log(df.column("col2").sum());  // 7
```

---

## Development

### Publishing

    $ npm run build
    $ cd ./dist
    $ npm publish