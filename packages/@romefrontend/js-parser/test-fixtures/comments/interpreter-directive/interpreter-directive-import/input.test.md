# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `comments > interpreter-directive > interpreter-directive-import`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 57
			line: 4
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	interpreter: JSInterpreterDirective {
		value: "/usr/bin/env babel-node"
		loc: Object {
			filename: "input.js"
			end: Object {
				column: 25
				index: 25
				line: 1
			}
			start: Object {
				column: 1
				index: 1
				line: 1
			}
		}
	}
	body: Array [
		JSImportDeclaration {
			defaultSpecifier: undefined
			importKind: undefined
			namespaceSpecifier: undefined
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 29
					index: 56
					line: 3
				}
				start: Object {
					column: 0
					index: 27
					line: 3
				}
			}
			source: JSStringLiteral {
				value: "foobar"
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 28
						index: 55
						line: 3
					}
					start: Object {
						column: 20
						index: 47
						line: 3
					}
				}
			}
			namedSpecifiers: Array [
				JSImportSpecifier {
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 13
							index: 40
							line: 3
						}
						start: Object {
							column: 8
							index: 35
							line: 3
						}
					}
					imported: JSIdentifier {
						name: "spawn"
						loc: Object {
							filename: "input.js"
							identifierName: "spawn"
							end: Object {
								column: 13
								index: 40
								line: 3
							}
							start: Object {
								column: 8
								index: 35
								line: 3
							}
						}
					}
					local: JSImportSpecifierLocal {
						name: JSBindingIdentifier {
							name: "spawn"
							loc: Object {
								filename: "input.js"
								identifierName: "spawn"
								end: Object {
									column: 13
									index: 40
									line: 3
								}
								start: Object {
									column: 8
									index: 35
									line: 3
								}
							}
						}
						importKind: undefined
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 13
								index: 40
								line: 3
							}
							start: Object {
								column: 8
								index: 35
								line: 3
							}
						}
					}
				}
			]
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```