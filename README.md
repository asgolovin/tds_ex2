# Topics in Dynamical Systems
## Exercise sheet 2

### How to run

1. Install Julia: https://julialang.org/
2. Make sure that you can run Julia Jupyter notebooks
3. Start Julia in your terminal with `julia` and install the required libraries (in a virtual env, if you're fancy):
```julia
julia> ]add GLMakie, LinearAlgebra
```
4. Run the notebook

Note: on the first run, the plotting cells can take a lot of time to execute (around one minute on my laptop). This is because Julia is precompiling the plotting library in the background; after the first iteration, the code will execute fast. 