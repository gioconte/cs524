#[ Weighted Graph Comparison Techniques for Brain Connectivity Analysis ](http://dl.acm.org/citation.cfm?id=2470724)
This paper clearly states what are the goal that the visualization aims at and lists the hypothesis for the experimentation phase. The evaluation phase is very well described as well as the results obtained. The hypothesis made are reasonable with respect to the goals/tasks described.
In this paper, authors are comparing different flavors of node-link diagram and matrix-based diagram to compare general weighted-graphs.
Goals are as follows:
*	"Assess weight change of a node’s connections (Trend)"
*	"Assess connectivity of common neighbors (Connectivity)"
*	"Identify the region with most changes (Region)"

Hypothesis:
*	"For the Trend task, we expected Matrix to outperform (accuracy and completion time) Node-Link for high-density
datasets. "
*	"For the Connectivity task, we expected Matrix not to outperform Node-Link"
*	"For the Region task, we expected Matrix to outperform Node-Link (accuracy and completion time)"
*	"Overall, we expected Node-Link to decrease in performance (accuracy and completion time) for Dense datasets"

For what concern the tests made, they measured the accuracy of the given answers and the completion time to give an answer as it is mentioned in the hypothesis.

Still there some aspects that make me confuse, precisely:
*	Although they based all the paper upon connectome data and focus their approach on those kind of visualization, to test their new technique they use synthetic data.
*	Only 11 people test the visualization techniques. Is this a relevant statistical sample? Which is the confidence of those result.
*	When the authors present the completion time, they discard the time spent for wrong answers. In my opinion, the completion time of a given task is interesting on itself whether or not the answer is correct. Of course, comparing also the completion time for correct and wrong answers could give deeper insight, but discarding a priori wrong answer did not convince me completely.


##Goals
1.	Identify connections and their weight. 
2.	Easily compare weight of the edges.
3.	Identify structural patterns in the intrinsic geometry.
4.	Identify the effects of virtual injuries.
5.	Identify the absolute importance of given brain regions.
6.	Compare different data reduction techniques on the same dataset.
7.	Inspecting each dimension of a multi-dimensional dataset, such as the one about connectome
8.	Easy exploration: visualization flexibility in terms of level of abstraction, perspective and data that can be visualized.
9.	Visualize the shortest path tree given a root node
10.	Visualize graph-based metrics such as nodal strength, nodal efficiency etc. more metrics [here](http://www.sciencedirect.com/science/article/pii/S105381190901074X).


##Hypothesis
1.	Using different levels of transparency to highlight different weights is the right dimension to use and it is better than other techniques (width, colors).
2.	The technique "Edges on demand" associated with different filters (according to the weight and the most weighted n edges) is better than visualize all the connections.
3.	3D rendering and virtual reality are the techniques that can better represent the intrinsic geometry of the brain rather than circle views or matrix-based diagram.
4.	Filtering by number of hops and maximum distance the shortest path tree is effective.
5.	Billboarding guarantees the minimum performances for rendering the graph
6.	A javascript web-based application guarantees the minimum flexibility and cross-platform feature required
7.	Filtering edges according to their weight (fixed threshold or first n most weighted edges) is effective
8.	Using Leap Motion makes the visualization more interactive and engaging.
9.	Combine 2D and 3D graph visualization give a better overview of the entire network.
10.	


##Tests
1.	*Accuracy test*. Given a set of edges ask the user to compare their weight and see which the accuracy achieved is, namely how many times the user identify the most/least weighted edge.
1.	*Accuracy test*. Given two nodes, ask to the user if they are directly connected.
1.	*Accuracy test*. Given a node, ask the user to count the number of edges that go through that node.
1.	*Performance test*. Measure how much time user spend before giving the answer, whether it is correct or not. Also known as *completion time* test. This test could be performed together with the afore mentioned tests.
1. Ask user if they can have an insight of the structure and if they can link what they see to a real object/shape. (Here the question is more psychological: how do people perceive the structure of an object?). A weak test could be to check if people can point out a similar real object or shape and how much time they spend to give an answer. In order to get more accurate result, the test can propose a set of predefined shapes and then we can see if users' answers converge or not.
