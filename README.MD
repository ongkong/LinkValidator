# LinkValidator
Used to validate links
`*` is the wildcard character
## Usage and Examples
`'*.google.com'.valid('wow.google.com') //true`
`'*'.valid('linkhere')` will match any valid link
`'*.google.com/*'.valid('gogo.google.com/dfodfk') //true`
