### "Optimization and high performance computing in Julia" - 2 day workshop

**1. Optimization and mathematical programming with applications to spatial data** <br/>
**2. Scaling up computations in Julia**

**Instructor:** Przemysław Szufel

**Dates:** Nov 20 & 21, 2023

**Time:**  
  &nbsp; Monday: 10:30am-noon; 1:30pm-3pm PST
  &nbsp; Tuesday: 9:30am-11am; 1:30pm-3pm PST

**Location**:<br/> 
  &nbsp; University of California, Berkeley, CA, USA<br/>
  &nbsp; Simons Laufer Mathematical Sciences Institute  <br/>
  &nbsp; Eisenbud Auditorium<br/>


Data analysis has become one of the core processes in virtually any professional activity. 
The collection of data becomes easier and less expensive, so we have ample access to it.
The Julia language which was designed to address the typical challenges that data scientists 
face when using other tools. Julia, like Python, supports an efficient and convenient development process. 
At the same time, programs developed in Julia have performance comparable to C.

This workshop consists of two parts:

### 1. Optimization and mathematical programming in Julia with applications to spatial data (Monday, Nov, 20)

The Julia programming language boasts a specialized development in mathematical programming models, centered around the robust JuMP.jl ecosystem. It offers a comprehensive and user-friendly suite of packages tailored for various optimization problems, including LP, MILP, MINLP, QP, and SOCP. The JuMP.jl platform serves as a cohesive, Julia-based domain-specific language for mathematical programming, compatible with over 40 solvers. This suite encompasses all leading commercial packages, significant Open Source options, and solvers natively written in Julia.

This lecture will navigate you through the intricate JuMP.jl ecosystem, from constructing basic optimization models to the advanced optimization of transportation systems.

### 2. Scaling up numerical computing in Julia (Tuesday, Nov, 21)

Writing code that seamlessly scales from an individual workstation to a supercomputing cluster is a complex task. In this tutorial, we will guide you on crafting efficient and high-performance code in Julia. We'll begin by identifying common pitfalls that can severely impact performance, such as type instability, the utilization of parametric types, and optimal data layout in memory.

Subsequently, we'll delve into techniques for scaling your code. We'll explore single instruction-multiple data (SIMD) operations, then progress to the use of green threads to enhance the performance of I/O processing. Following that, we'll demonstrate the principles of multithreading. The final stage of our journey will cover multiprocessing and the intricacies of massively parallel and distributed computing.

This workshop will be enriched with practical examples of parallelization patterns that are broadly applicable across various numerical computing endeavors.


### Installation instructions
Detailed installation instructions can be found in materials for the day 1.

If you have Julia installed and running this should be sufficient:
```julia
using Pkg
Pkg.activate(".") # assumes running the code in the main folder of this repository
Pkg.instantiate() # needed only when run for the first time 
using IJulia
ENV["JULIA_NUM_THREADS"]=4
notebook(dir=".")
```


**Schedule** (all times are PST time zone)

<table>
<tr><td><b>Day 1 (Monday, Nov 20, 2023)</b></td><td>10:30am-noon & 1:30pm-3pm</td><td>Optimization and mathematical programming in Julia with applications to spatial data
<br>
  <br>
  <a href="https://www.slmath.org/video-details/27815/34782">https://www.slmath.org/video-details/27815/34782</a><br>
  <a href="https://www.slmath.org/video-details/27816/34783">https://www.slmath.org/video-details/27816/34783</a><br>
  (For the lecture recording video link scroll to the bottom of the web page)
 
</td></tr>
<tr><td><b>Day 2 (Tuesday, Nov 21, 2023)</b></td><td>9:30am-11am & 1:30pm-3pm</td><td>Scaling up numerical computing in Julia<br>
  <br>
  <a href="https://www.slmath.org/video-details/27817/34784">https://www.slmath.org/video-details/27817/34784</a><br>
  <a href="https://www.slmath.org/video-details/27818/34785">https://www.slmath.org/video-details/27818/34785<a/><br>
  (For the lecture recording video link scroll to the bottom of the web page)

</td></tr>
</table>


This course has been supported by the Polish  National Agency for Academic Exchange under  the Strategic Partnerships programme, grant  number BPI/PST/2021/1/00069/U/00001. 



![img](nawalogo.png)

<br/>
