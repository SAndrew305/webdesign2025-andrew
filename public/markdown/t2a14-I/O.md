Calculator Function?
Would look like this:

`[Input field]
`{Calculate Button}`
`Output`

Input field would need `nums` and `+, -, *,` and `/` as valid integers and operations. NO variables.

`parseInt` converts numbers to full integers i.e., 1234,
`parseFloat` converts numbers to floating point i.e., 1234.5

User-defined variables
`nums = User defined`, `mathop = User defined`
Variables in program
`X, Y, Z = nums`, `o = mathop`, `A = answer`

If  `X != num` then return `"Invalid Integer"`. 
If  `X = num` without `o` then return `X` 

Won't use codegen for this... that takes all the fun out of it.. F- cursor.

Front-end;
`<input id="textBox" type="text" value="0">`
// Text box to input numbers.
// start with `x` and separate `o` by a space, and `y` after `o` space.
// Example `x o y`
//                ^ ^

`<span id="calcSpan">...</span><br>`
// Where the answer is displayed. `I f I = A`

`<input type="button" value="Calculate Answer">`
// `onClick` event for the button returns answer
// return `invalid` if input is `x / 0` or `0 / 0`.

O needs to be a dynamic variable