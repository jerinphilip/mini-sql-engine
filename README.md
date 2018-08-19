MiniSQL Engine
===

Moving
[this](https://github.com/jerinphilip/monsoon-17/tree/master/database-systems/hw/1-mini-sql-engine/)
to a standalone repository. This was originally (over)done for a
database introductory course in Monsoon '17.

Assumes only need to implement an engine which takes in SQL and
processes it with correctness - speed is not taken into account.

## Rough Guide 

```bash
├── dtype # Data Structures
│   ├── __init__.py
│   ├── dops.py             # Data <Op> Data (2 + 3)
│   ├── ops.py              # Table <Op> Table (A UNION B)
│   └── table.py            # Table DataType
│ 
├── sqlparser               # Parser, AST Building
│   ├── ast.py              # AST
│   ├── __init__.py         # Main parsing code using pyparsing
│   └── main.py             # sample file with __init__.py builds on
│ 
├── engine.py               # Interpreter Logic/Pattern
└── store.py                # Holding tables mapped to their names
├── parser.py               # Parser for provided data
├── own-samples.txt
├── sample.txt
```
