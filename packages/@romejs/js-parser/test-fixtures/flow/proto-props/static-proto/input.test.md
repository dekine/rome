# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > proto-props > static-proto`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 41
      line: 4
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        advice: Array []
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unexpected token, expected :'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 16
          index: 34
          line: 2
        }
        start: Object {
          column: 15
          index: 33
          line: 2
        }
      }
    }
  ]
  body: Array [
    FlowDeclareClass {
      id: BindingIdentifier {
        name: 'C'
        loc: Object {
          filename: 'input.js'
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
      extends: Array []
      implements: Array []
      mixins: Array []
      typeParameters: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 1
          index: 40
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: FlowObjectTypeAnnotation {
        exact: false
        inexact: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 40
            line: 3
          }
          start: Object {
            column: 16
            index: 16
            line: 1
          }
        }
        properties: Array [
          FlowObjectTypeProperty {
            kind: 'init'
            key: Identifier {
              name: 'proto'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 14
                  index: 32
                  line: 2
                }
                start: Object {
                  column: 9
                  index: 27
                  line: 2
                }
              }
            }
            value: FlowGenericTypeAnnotation {
              id: ReferenceIdentifier {
                name: 'p'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 16
                    index: 34
                    line: 2
                  }
                  start: Object {
                    column: 15
                    index: 33
                    line: 2
                  }
                }
              }
              typeParameters: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 16
                  index: 34
                  line: 2
                }
                start: Object {
                  column: 15
                  index: 33
                  line: 2
                }
              }
            }
            optional: false
            proto: false
            static: true
            variance: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 16
                index: 34
                line: 2
              }
              start: Object {
                column: 2
                index: 20
                line: 2
              }
            }
          }
          FlowObjectTypeProperty {
            kind: 'init'
            key: Identifier {
              name: ''
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 17
                  index: 35
                  line: 2
                }
                start: Object {
                  column: 16
                  index: 34
                  line: 2
                }
              }
            }
            value: FlowGenericTypeAnnotation {
              id: ReferenceIdentifier {
                name: 'T'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 19
                    index: 37
                    line: 2
                  }
                  start: Object {
                    column: 18
                    index: 36
                    line: 2
                  }
                }
              }
              typeParameters: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 19
                  index: 37
                  line: 2
                }
                start: Object {
                  column: 18
                  index: 36
                  line: 2
                }
              }
            }
            optional: false
            proto: false
            static: false
            variance: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 19
                index: 37
                line: 2
              }
              start: Object {
                column: 16
                index: 34
                line: 2
              }
            }
          }
        ]
      }
    }
  ]
}
```
