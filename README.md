# letto.js
Mobile-API for [Letto](https://play.google.com/store/apps/details?id=com.tokarevco.letto) a unique dating app where thoughts and emotions are more important than photos

## Example
```JavaScript
async function main() {
	const { Letto } = require("./letto.js")
	const letto = new Letto()
	await letto.signIn("email", "password")
}

main()
```
