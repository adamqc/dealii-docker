# deal.II Docker images

This repository automatically builds the dealii library every week using GitHub
Actions. The build is done by using spack, and will result in two Docker images:

- `adamqc/dealii-real:latest`: build with PETSc real numbers
- `adamqc/dealii-complex:latest`: build with PETSc complex numbers
