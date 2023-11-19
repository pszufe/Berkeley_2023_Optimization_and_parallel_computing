# Scaling up numerical computing in Julia

## Course content

1. Basic performance tips
    1. Avoid global variables
    2. Avoid abstract lists and structs
    3. Do not change the type of a variable within a function
    4. Mitigate type uncertainty with barrier functions
    5. Remember about column-major layout of matrices
    6. Prealocate, use views, vectorize
    7. Check type stability with the `@code_warntype` macro

2. Parallel and distributed computing
    1. Parallelize via Single Instruction Multiple Data (SIMD)
    2. Green threading
    3. Multithreading
    4. Multi-processing and distributed computing](#multiprocessing)