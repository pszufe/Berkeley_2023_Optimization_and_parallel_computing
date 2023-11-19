# Optimization and mathematical programming in Julia with applications to spatial data

## Course content

1. Introduction to optimization models with JuMP
2. Macros and JuMPs performance
3. Warehouse transportation optimization
4. Collection of points-of-interest (POI) is spatial data
5. Travelling salesman problem (TSP)
6. Quadratic programming - parameter estimation
7. Modelling pandemic dynamics in a small community
8. Modelling restaurant walkability in SF

## Installation instructions

1. Please download Julia from [https://julialang.org/downloads/](https://julialang.org/downloads/) and follow the installation instructions presented at https://julialang.org/downloads/platform/. The 64-bit version is recommended.

2. Install Julia packages that will be used throughout the workshop. Once Julia is installed please follow the steps:

    1. Clone this repository by running the following git command:
        ```
        git clone https://github.com/pszufe/Berkeley_2023_Optimization_and_parallel_computing.git
        ```

    2. Change the directory to where `Project.toml` and `Manifest.toml` files are located
        ```
        cd "Berkeley_2023_Optimization_and_parallel_computing"
        ```
    3. Run the Julia console or in the command line (run command **julia** in the project folder). Once Julia interpreter is running paste the following Julia code:
        ```
        using Pkg
        pkg"activate ."
        pkg"instantiate"
        using Conda
        Conda.runconda(`install jupyter --yes`) # if you never used IJulia in your Julia
        Conda.runconda(`install folium -c conda-forge --yes`)
        ```

4. (OPTIONAL) The recommended programming environment for the Julia language is Visual Studio Code (https://code.visualstudio.com/) with Julia extension. Please follow the steps below:

    a) Download and install VS Code (available at https://code.visualstudio.com/download/)

    b) Start VS Code, click View->Command Palette...  and type `View: Show Extensions` to go to the extension manager

    c) In the extension manager search box type “Julia”

    d) On the top of the extension list you should see “Julia Language Support” – click *Install* to install the extension.

    If you run into any installation problem, more detailed instructions can be found in https://github.com/julia-vscode/julia-vscode#getting-started


5. During the workshop will be working with Julia within Jupyter notebook (this can be also used instead of VS Code)

    To run Julia inside a Jupyter notebook start the Julia console (this assumes that the console is run in the main folder of this repository) and run the two following commands:
    ```
    using Pkg
    Pkg.activate(".")
    using IJulia
    notebook(dir=".")
    ```
    After running the above commands a new web browser tab should open with Jupyter Notebook.
