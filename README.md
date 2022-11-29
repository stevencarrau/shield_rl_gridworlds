#GridStorm - Python binding for gridworld environments
===================================

* **gridfull** - Fully observable gridworld environments
* **gridfullsparse** - Fully observable gridworld environments with a non-sparse reward function
* **gridstorm** - Partially observable gridworld environments
* **gridstormsparse** - Partially observable gridworld environments with a non-sparse reward function


Adapted from [gridstorm](https://github.com/sjunges/gridworld-by-storm)

Requires [Storm](https://www.stormchecker.org/) and [stormpy bindings](https://github.com/sjunges/stormpy).

Install can be performed automatically by running:
```
bash setup.sh
```

Otherwise you can install each individual environment set by running in each subdirectory:

```
python setup.py develop
```
