# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-import-declaration > import-namespace-specifier`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-import-declaration/import-namespace-specifier/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-import-declaration/import-namespace-specifier/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSImportDeclaration {
			defaultSpecifier: undefined
			importKind: undefined
			namedSpecifiers: Array []
			loc: Object {
				filename: "esprima/es2015-import-declaration/import-namespace-specifier/input.js"
				end: Object {
					column: 27
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			source: JSStringLiteral {
				value: "foo"
				loc: Object {
					filename: "esprima/es2015-import-declaration/import-namespace-specifier/input.js"
					end: Object {
						column: 26
						line: 1
					}
					start: Object {
						column: 21
						line: 1
					}
				}
			}
			namespaceSpecifier: JSImportNamespaceSpecifier {
				loc: Object {
					filename: "esprima/es2015-import-declaration/import-namespace-specifier/input.js"
					end: Object {
						column: 15
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				local: JSImportSpecifierLocal {
					name: JSBindingIdentifier {
						name: "foo"
						loc: Object {
							filename: "esprima/es2015-import-declaration/import-namespace-specifier/input.js"
							identifierName: "foo"
							end: Object {
								column: 15
								line: 1
							}
							start: Object {
								column: 12
								line: 1
							}
						}
					}
					importKind: undefined
					loc: Object {
						filename: "esprima/es2015-import-declaration/import-namespace-specifier/input.js"
						end: Object {
							column: 15
							line: 1
						}
						start: Object {
							column: 12
							line: 1
						}
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```