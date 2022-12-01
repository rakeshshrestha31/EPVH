Implementation of "Exact Polyhedral Visual Hull".

Based on

"Jean-Sébastien Franco, Edmond Boyer. Exact polyhedral visual hulls. British Machine Vision Conference (BMVC’03), Sep 2003, Norwich, United Kingdom. pp.329–338. ffinria-00349075v1f"


Dependencies: OpenGL, VTK

Install:

```
conda env create -f environment.yml
conda activate epvh
cmake .. -DEIGEN_INCLDUE_DIR=$CONDA_PREFIX/include/eigen3/
make -j
```

Output of demo sample.

 ![Alt text]( /datasets/visualhull_result.png?raw=true "Visual Hull of alien")


