# compwhile
Web IDE for Computability Theory Course

## Features
- Edit WHILE programs.
- Run WHILE programs.
- Visualizing input of trees.

## Main Components
- Core
  - **editor** - A web component for editing supported programs.
  - **while-syntax-highlighter(whileSrc)**
    - Returns a formatted while source code.
  - **while-tokenizer(whileSrc)**
    - Returns an array of whileTokens.
    - Example: https://jsfiddle.net/yckart/mb8sL3aa/
  - **while-ast-builder(whileTokens)**
    - Returns a whileAST object or an error.
  - **while-executer(whileAST, input)**
    - Has  many handlers for each type of node.
  - **while-highlighter(string)**
    - Returns a formatted string.
- Visualizers
  - **while-ast-visualizer(whileAST)** returns a svg.
  - **tree-notation-visualizer(treeStr)** returns a svg.
  - **list-notation-visualizer(listStr)** returns a svg.

## Project Team Members
* [HagaiNuriel](https://github.com/HagaiNuriel) -
**Hagai Nuriel** &lt;hagai.nuriel@gmail.com&gt;
* [DorSav](https://github.com/DorSav) -
**Dor Savion** &lt;dorsav@gmail.com&gt;
* [elizehavi](https://github.com/elizehavi) -
**Eli Zehavi** &lt;eli.zehavi@gmail.com&gt;
