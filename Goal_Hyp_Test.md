#[ Weighted Graph Comparison Techniques for Brain Connectivity Analysis ](http://delivery.acm.org/10.1145/2480000/2470724/p483-alper.pdf?ip=131.193.76.114&id=2470724&acc=ACTIVE%20SERVICE&key=B63ACEF81C6334F5%2EAACB7351D18CAF98%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&CFID=631055731&CFTOKEN=92392225&__acm__=1425320081_03c06d62e2baa64f55b0756088b557ab)

##Goals
1.	Identify connections and their weight. 
2.	Easily compare weight of the edges.
2.	Identify structural patterns in the intrinsic geometry.
3.	Identify the effects of virtual injuries.
4.	Identify the absolute importance of given brain regions.
5.	Compare different data reduction techniques on the same dataset.
6.	Inspecting each dimension of a multi-dimensional dataset, such as the one about connectome
7.	Easy exploration: visualization flexibility in terms of level of abstraction, perspective and data that can be visualized.
8.	


##Hypothesis
1.	Using different levels of transparency to highlight different weights is the right dimension and it is better than other techniques (width, colors).
1.	The technique "Edges on demand" associated with different filters (according to the weight and the most weighted n edges) is better than visualize all the connections.
2.	3D rendering and virtual reality are the techniques that can better represent the intrinsic geometry of the brain. 
1.	


##Tests
1.	*Accuracy test*. Given a set of edges ask the user to compare their weight and see which is the accuracy achieved, namely how many times the user identify the most/least weighted edge.
1.	*Accuracy test*. Given two nodes, ask to the user if they are directly connected.
1.	*Accuracy test*. Given a node, ask the user to count the number of edges that go through that node.
1.	*Performance test*. Measure how much time user spend before giving the answer, whether it is correct or not. Also known as *completion time* test.
1. Ask user if they can have an insight of the structure and if they can link what they see to a real object. (Here the question is more psychological: how do people perceive the structure of an object?). It weak test could be to check if people can end to a real object or shape and how much time they spend to give an answer.