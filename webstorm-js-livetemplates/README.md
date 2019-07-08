# Javascript Live Templates for the Webstorm IDE

*Used as a basis: https://github.com/thehulke/webstorm-js-es6-live-templates*  
<br>
<br>
Put the `es6-live-tmpls.xml` file into the following folder and restart the Webstorm:
`~/Library/Preferences/WebStorm{Version}/templates`  
e.g. `~/Library/Preferences/WebStorm2019.1/templates`

### Live Templates List:
| #  | Shorthand | Output | 
| ---  | --- | --- |
| 1  | `cl`  | `console.log('$VAR1$', $VAR2$);$END$` |
| 2  | `t` | `this.$END$` |
| 3  | `v` | `var $VAR1$ = $VAR2$;`<br>`$END$` |
| 4  | `l` | `let $VAR1$;`<br>`$END$` |
| 5  | `le` | `let $VAR1$ = $VAR2$;`<br>`$END$` |
| 6  | `c` | `const $VAR1$ = $VAR2$;`<br>`$END$` |
| 7  | `co` | `const $VAR1$ = {`<br>`$VAR2$: $VAR3$,`<br>`}`<br>`$END$` |
| 8  | `if` | `if ($CONDITION$){`<br>`$BODY$`<br>`}$END$` |
| 9  | `el` | `else {`<br>`$BODY$`<br>`}`<br>`$END$` |
| 10 | `eif` | `else if ($CONDITION$){`<br>`$ACTION$`<br>`}$END$` |
| 11 | `for` | `just a for loop with an empty body` |
| 12 | `fo` | `just a for of loop with an empty body` |
| 13 | `fn` | `function $NAME$($ARGUMENTS$) {`<br>`$BODY$`<br>`}`<br>`$END$` |
| 14 | `afn` | `async function $NAME$($ARGUMENTS$) {`<br>`$BODY$`<br>`}`<br>`$END$` |
| 15 | `=` | `($ARGS$) => $RETURNS$` |
| 16 | `=b` | `($ARGS$) => {`<br>`$BODY$`<br>`}`<br>`$END$`<br> |
| 17 | `a=b` | `async ($ARGS$) => {`<br>`$BODY$`<br>`}`<br>`$END$`<br> |
| 18 | `cls` | `class $NAME$ {`<br>`constructor(){}`<br><br>`$BODY$`<br>`}` |
| 19 | `clsf` | `$NAME$() {`<br>`$BODY$`<br>`}` |
| 20 | `r` | `return $VAL$;` |



