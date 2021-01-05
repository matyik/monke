# monke
Monke.js official open source repository

## Installation
`npm i monkejs`

## Usage
* Node.js v1.13 or lower: `const monke = require('monke')`
* Node.js v1.14 or higher: `import monke from 'monke'`

### Logging
* Table: `monke.table([<Rows>])`
** Example: `monke.table([['Ape', 'Monke', 'Banana'], ['Golira', 'Le Monke', 'Yellow'], ['Chimanzee', 'Me', 'Brown'])`
** Returns: `  __Ape__  | __Monke__ | __Banana__  
                Golira  | Le Monke  |   Yellow  
              Chimanzee |     Me    |   Brown`
