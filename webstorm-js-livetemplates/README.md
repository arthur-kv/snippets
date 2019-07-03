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
| 7  | `co` | `const $VAR1$ = {`<br>&nbsp;&nbsp;`$VAR2$: $VAR3$,`<br>`}`<br>`$END$` |
| 8  | `if` | `if ($CONDITION$){`<br>&nbsp;&nbsp;`$BODY$`<br>`} $END$` |
| 9  | `el` | `else {`<br>&nbsp;&nbsp;`$BODY$`<br>`}`<br>`$END$` |
| 10 | `eif` | `else if ($CONDITION$){`<br>&nbsp;&nbsp;`$ACTION$`<br>`} $END$` |
| 11 | `for` | `just a for loop with an empty body` |
| 12 | `fo` | `just a for of loop with an empty body` |
| 13 | `fn` | `function $NAME$($ARGUMENTS$) {`<br>&nbsp;&nbsp;`$BODY$`<br>`}`<br>`$END$` |
| 14 | `afn` | `async function $NAME$($ARGUMENTS$) {`<br>&nbsp;&nbsp;`$BODY$`<br>`}`<br>`$END$` |
| 15 | `=` | `($ARGS$) => $RETURNS$` |
| 16 | `=b` | `($ARGS$) => {`<br>&nbsp;&nbsp;`$BODY$`<br>`}`<br>`$END$`<br> |
| 17 | `cls` | `class $NAME$ {`<br>&nbsp;&nbsp;`constructor(){}`<br><br>&nbsp;&nbsp;`$BODY$`<br>`}` |
| 18 | `clsf` | `$NAME$() {`<br>&nbsp;&nbsp;`$BODY$`<br>`}` |
| 19 | `r` | `return $VAL$;` |



