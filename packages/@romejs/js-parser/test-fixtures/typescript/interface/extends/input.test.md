# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > interface > extends`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.ts'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array ['ts']
  loc: Object {
    filename: 'input.ts'
    end: Object {
      column: 0
      index: 30
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    TSInterfaceDeclaration {
      id: BindingIdentifier {
        name: 'I'
        loc: Object {
          filename: 'input.ts'
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
      typeParameters: undefined
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 29
          index: 29
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: TSInterfaceBody {
        body: Array []
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 29
            index: 29
            line: 1
          }
          start: Object {
            column: 27
            index: 27
            line: 1
          }
        }
      }
      extends: Array [
        TSExpressionWithTypeArguments {
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 26
              index: 26
              line: 1
            }
            start: Object {
              column: 20
              index: 20
              line: 1
            }
          }
          expression: TSQualifiedName {
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 23
                index: 23
                line: 1
              }
              start: Object {
                column: 20
                index: 20
                line: 1
              }
            }
            left: ReferenceIdentifier {
              name: 'X'
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 21
                  index: 21
                  line: 1
                }
                start: Object {
                  column: 20
                  index: 20
                  line: 1
                }
              }
            }
            right: Identifier {
              name: 'Y'
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 23
                  index: 23
                  line: 1
                }
                start: Object {
                  column: 22
                  index: 22
                  line: 1
                }
              }
            }
          }
          typeParameters: TSTypeParameterInstantiation {
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 26
                index: 26
                line: 1
              }
              start: Object {
                column: 23
                index: 23
                line: 1
              }
            }
            params: Array [
              TSTypeReference {
                typeParameters: undefined
                loc: Object {
                  filename: 'input.ts'
                  end: Object {
                    column: 25
                    index: 25
                    line: 1
                  }
                  start: Object {
                    column: 24
                    index: 24
                    line: 1
                  }
                }
                typeName: ReferenceIdentifier {
                  name: 'Z'
                  loc: Object {
                    filename: 'input.ts'
                    end: Object {
                      column: 25
                      index: 25
                      line: 1
                    }
                    start: Object {
                      column: 24
                      index: 24
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
  ]
}
```
