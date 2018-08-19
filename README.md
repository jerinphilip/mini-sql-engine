MiniSQL Engine
---

Moving
[https://github.com/jerinphilip/monsoon-17/tree/master/database-systems/hw/1-mini-sql-engine/](this)
to a standalone repository. This was originally (over)done for a
database introductory course in Monsoon '17.

Assumes only need to implement an engine which takes in SQL and
processes it with correctness - speed is not taken into account.

# Rough Guide 

```bash
├── ast.py
├── dtype # Data Structures
│   ├── dops.py
│   ├── __init__.py
│   ├── ops.py
│   └── table.py
├── engine.py # Interpreter Logic
├── own-samples.txt
├── parser.py # Parser for provided data
├── README.md
├── sample.txt
├── sqlparser # Parser, AST Building
│   ├── ast.py # AST
│   ├── __init__.py  # Main parsing code using pyparsing
│   └── main.py # sample file with __init__.py builds on
└── store.py
```
