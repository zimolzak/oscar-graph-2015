Oscars graph, 2015
========================

Many years, I have made a graph (in the "graph theory" sense) for the
Academy Awards (Oscars). Nodes are either categories or nominees. I
removed categories and nominees that aren't part of the giant
component of the graph (example: this year no nominees for Best
Animated have more than one nomination). Requires Graphviz.

Usage:

    fdp -Tpng oscars2015.dot >  oscar_graph.png

Alternate layout engine:

    neato -Tpng oscars2015.dot > neato.png

