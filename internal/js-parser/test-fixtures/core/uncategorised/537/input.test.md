# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 537`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "core/uncategorised/537/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/537/input.js"
		end: Object {
			column: 19
			index: 19
			line: 1
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSForStatement {
			test: undefined
			update: undefined
			loc: Object {
				filename: "core/uncategorised/537/input.js"
				end: Object {
					column: 19
					index: 19
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			body: JSEmptyStatement {
				loc: Object {
					filename: "core/uncategorised/537/input.js"
					end: Object {
						column: 19
						index: 19
						line: 1
					}
					start: Object {
						column: 18
						index: 18
						line: 1
					}
				}
			}
			init: JSVariableDeclaration {
				kind: "const"
				loc: Object {
					filename: "core/uncategorised/537/input.js"
					end: Object {
						column: 15
						index: 15
						line: 1
					}
					start: Object {
						column: 4
						index: 4
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "core/uncategorised/537/input.js"
								identifierName: "x"
								end: Object {
									column: 11
									index: 11
									line: 1
								}
								start: Object {
									column: 10
									index: 10
									line: 1
								}
							}
						}
						loc: Object {
							filename: "core/uncategorised/537/input.js"
							end: Object {
								column: 15
								index: 15
								line: 1
							}
							start: Object {
								column: 10
								index: 10
								line: 1
							}
						}
						init: JSNumericLiteral {
							value: 0
							format: undefined
							loc: Object {
								filename: "core/uncategorised/537/input.js"
								end: Object {
									column: 15
									index: 15
									line: 1
								}
								start: Object {
									column: 14
									index: 14
									line: 1
								}
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```