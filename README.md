# SSMGV
```sh
Super-stable matching graphic visualizer (variant of the stable marriage problem).
```

## Features
- Input preferences, with potential indifferences, by
    - Manual configuration
    - Vertices of integer size
    - Randomization
- Display the super-stable matching if one exists, otherwise state none exsits
- Each edge represents the final match between the verticies
- Clicking an edge displays the preferences of the two adjacent vertices

## Dependencies
- Python 3.10.2
    - Flask library (2.0.2)
    - NetworkX library (2.6.3) (under consideration)
    - Matching library (1.4) (under consideration)

## TODO
- Complete input preferences
- Graph via NetworkX
- Display via Flask mirco-framework
