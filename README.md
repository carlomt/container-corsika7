# Apptainer for Coriska7

In the input file specify an output directory:
```
DIRECT /out/
```

create such a directory and bind it to the container:
```bash
apptainer run --bind $(pwd)/out:/out corsika7.sif < <inpfile>
```