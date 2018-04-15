# Quadratic equation solver
A module what contains a function to solve quadratic equation. 

## Usage
Python >= 3.5 required.
To be able to use current function you need to import this module into your project. 
### Example use
```python
from quadratic_equation import get_roots

root1, root2 = get_roots(a, b, c)
```
Where 

![](http://latex.codecogs.com/gif.latex?a%2C%20b%2C%20c)

 coefficients of quadratic equation

![](http://latex.codecogs.com/gif.latex?a%5E2%20&plus;%20b%20&plus;%20c)

### Tests
Repository contains a set of tests. You can execute it with shell inside directory with tests.py:
```bash
python -m unittest
``` 
## Project goals
This project is created for educational purposes [DEVMAN.org](https://devman.org)