run 'make' to make the executable

run pso in the format provided below

./pso function-name dimension swarm-size xmin xmax max-iter num-threads

where,

    function-name: The name of the function the swarm particle needs to be optimizewd for. Possible values: booth, holder_table, eggholder, rastrigin, schwefel

    dimension: Dimension of the search space

    swarm-size: The number of particles in a single swarm

    xmin, xmax: lower and upper bounds on search domain

    max-iter: Number of iterations to run the optimizer

    num-threads: Number of parallel threads to create