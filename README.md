# RTOP
The problem instances is structured as follows:\
n {number of targets}\
m {number of agents}\
tmax {distance budget}\
{x coordinate for node 1 (source)} {y coordinate for node 1 (source)} 0 {risk of traversing from node 1 to 1} {risk of traversing from node 1 to 2} ... {risk of traversing form node 1 to n}\
{x coordiante for node 2} {y coordinate for node 2} {score of node 2} {risk of traversing from node 2 to 1} {risk of traversing from node 2 to 2} ... {risk of traversing from node 2 to n}\
... \
{x coordiante for node n - 1} {y coordiante for node n - 1} {score of node n-1} {risk of traversing from node n - 1 to 1} {risk of traversing from node n - 1 to 2} ... {risk of traversing from node n - 1 to n}\
{x coordinate for node n (sink)} {y coordinate for node n (sink)} 0 {risk of traversing from node n to 1} {risk of traversing from node n to 2} ... {risk of traversing from node n to n}

