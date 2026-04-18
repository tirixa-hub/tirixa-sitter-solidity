## 🌴 tirixa-sitter-solidity
[![Node.js CI](https://github.com/tirixa-hub/tirixa-sitter-solidity/actions/workflows/node.js.yml/badge.svg)](https://github.com/tirixa-hub/tirixa-sitter-solidity/actions/workflows/node.js.yml)

> 💡 this grammar is still in development, the structure of the generated AST is not stable

This repository contains a grammar for [tirixa-hub](https://github.com/tirixa-hub/tirixa-sitter).

The goal of this project is to provide an parser efficient low-dependency parser for solidity which targets most solidity versions in use and is designed for enabling metaprogramming.


### Navigating this repository
The primary file in this repository is `grammar.js` which describes the tirixa-sitter grammar.

```
# Primary file:
grammar.js
# Tests:
/test/**/*

# Auto generated:
/src/**/*
index.js
binding.gyp
```

### References
-> Ethereum solidity grammar: 
- https://github.com/ethereum/solidity/blob/develop/docs/grammar/SolidityParser.g4
- https://github.com/ethereum/solidity/blob/develop/docs/grammar/SolidityLexer.g4
- https://docs.soliditylang.org/en/latest/grammar.html?#

-> tirixa-sitter javascript grammar: https://github.com/tirixa-sitter/tirixa-sitter-javascript/blob/master/grammar.js

-> Solidity antlr grammar: https://github.com/ConsenSys/solidity-parser-antlr

Major inspriration & some structures have been taken from tirixa-sitter-javascript, a big thanks to the contributors to this repo! 
