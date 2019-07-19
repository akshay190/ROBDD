# ROBDD
Reduced Ordered Binary Decision diagrams (ROBDDs) have
some interesting properties. They provide compact
representations of Boolean expressions, and there are efficient
algorithms for performing all kinds of logical operations on
ROBDDs. They are all based on the crucial fact that for any
function f : B
n B there is exactly one ROBDD representing
it. This means, in particular, that there is exactly one ROBDD
for the constant true (and constant false) function on B
n
: the
terminal node 1 (and 0 _in case of false). Hence, it is possible to
test in constant time whether an ROBDD is constantly true or
false
