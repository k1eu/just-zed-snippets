# Just Typescript Snippets

This extension only includes Typescript (ofc Javascript also supported) snippets.

## Snippets list

### Basic Methods

|  Prefix | Method                                              |
| ------: | --------------------------------------------------- |
|  `imp→` | `import moduleName from 'module'`                   |
|  `imn→` | `import { namedModule } from 'module'`              |
|  `ime→` | `import * as alias from 'module'`                   |
|  `ima→` | `import { originalName as aliasName} from 'module'` |
| `expd→` | `export default moduleName`                         |
| `expn→` | `export { destructuredModule } from 'module'`       |
| `expa→` | `export { originalName as aliasName} from 'module'` |
| `enaf→` | `export const functionName = (params) => { }`       |
|  `enf→` | `export function functionName(params) { }`          |
| `ednf→` | `export default function functionName(params) { }`  |
|  `met→` | `methodName = (params) => { }`                      |
|  `fea→` | `arrayName.forEach(element => { }`                  |
|  `fof→` | `for(let itemName of objectName { }`                |
|  `fin→` | `for(let itemName in objectName { }`                |
| `anfn→` | `(params) => { }`                                   |
| `nafn→` | `const functionName = (params) => { }`              |
|  `nfn→` | `function name(params) { }`                         |
|  `dob→` | `const {propName} = objectToDescruct`               |
|  `dar→` | `const [propName] = arrayToDescruct`                |
|  `sti→` | `setInterval(() => { }, intervalTime`               |
|  `sto→` | `setTimeout(() => { }, delayTime`                   |
| `prom→` | `new Promise((resolve, reject) => { }`              |
| `cmmb→` | `comment block`                                     |
|   `cp→` | `const { } = this.props`                            |
|   `cs→` | `const { } = this.state`                            |

### Console

| Prefix  | Method                                                       |
| ------- | ------------------------------------------------------------ |
| `clg→`  | `console.log(object)`                                        |
| `clo→`  | `console.log({name})`                                        |
| `cln→`  | `` console.log(`object`, object) ``                          |
| `clj→`  | `` console.log(`object`, JSON.stringify(object, null, 2)) `` |
| `cltm→` | `` console.time(`timeId`) ``                                 |
| `clte→` | `` console.timeEnd(`timeId`) ``                              |
| `cas→`  | `console.assert(expression,object)`                          |
| `cldi→` | `console.dir`                                                |
| `cler→` | `console.error(object)`                                      |
| `cltr→` | `console.trace(object)`                                      |
| `clwa→` | `console.warn`                                               |
| `clin→` | `console.info`                                               |

### Others

#### `cmmb`

```JS
/**
|--------------------------------------------------
| $1
|--------------------------------------------------
*/
```

#### `desc`

```javascript
describe("$1", () => {
  $2;
});
```

#### `test`

```javascript
test("should $1", () => {
  $2;
});
```

#### `tit`

```javascript
it("should $1", () => {
  $2;
});
```
