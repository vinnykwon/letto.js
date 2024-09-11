# letto.js
Mobile-API for Letto a unique dating app where thoughts and emotions are more important than photos

## Example
```JavaScript
async function main() {
	const { Letto } = require("./letto.js")
	const letto = new Letto()
	await letto.signIn("email", "password")
}

main()
```
