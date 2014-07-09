Workloads.jl
============

From the Julia homepage graph to speed.julia.org, existing benchmarks for Julia are microbenchmarks. We want to look at the performance characteristics of real-world workloads that people run and care about.

We need your help to create a collection of workloads that matter to Julians. This is a place to collect the code, any data they require to run, and instructions for running them.

## Contributing

If you have a program that you have written in Julia and care about the performance of, then we're interested. Please fork this repository, make a new folder to put your program in, and make a pull request.

You folder should include:
* The code for your program
* A dataset, if your program requires one
* A README file (describing how to run your code)
* A LICENSE file (containing the license for your code)
* A REQUIRES file (containing the names of any Julia packages you depend on)

If you include a dataset, we reccommend that it is a real dataset you care about, since that's the workload that matters. If you do not want to or cannot release your dataset, then please include some generated workload that you consider realistic.

Important information for the README includes any non-Julia dependencies you may have and one or more sample invocations of your workload.
