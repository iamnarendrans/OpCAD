Basic example of the genetics optimization framework

The ltiGeneticsTester files contain example code of the interaction
between a lti::functor to be evaluated and the class inherited from
lti::genetics used in the evaluation.

This example shows how to use the lti::paretoFront class with the
genetics class to perform the real optimization.

With the default configuration, a file "pareto.pf" will be generated, which can be grafically visualized with the example/pareto.

Assuming that the example/pareto is already compiled, just do a 

> ../pareto/pareto -p show.gp -x pareto.pf

This produces a file "show.gp", which can be visualized with gnuplot with

> gnuplot --persist show.gp
