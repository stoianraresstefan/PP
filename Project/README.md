The questions for each exercise for the final project (taken from MS Teams course channel):

## 1
Hi, everyone! In the attached zip file ex_1_graph.zip you will see a pickle file containing the network graph for the first exercise, 2-Faction Party. After extracting the pickle from the zip archive, install pickle and networkx libraries (in Google Colab environment they should already be installed) and read the graph using:
 
Python

~~~
import pickle
import networkx as nx
G = pickle.load(open('ex_1_graph.pickle', 'rb'))
~~~

Each node in the networkx graph has two attributes (name - randomly generated, not important - and faction) and each edge has one attribute (messages).
- In addition to what you have already been told, there are now several interactions between factions. You can ponder to and answer the question 'What happens if the 2 factions are completely separated?' in the notebook you provide.
- We recommend you use networkx for some of the visualizations, check out https://networkx.org/documentation/stable/reference/drawing.html
- If there are mistakes on our part regarding the network data we will modify the graph promptly.
You can start a thread of questions regarding the project, if you have any, in the Reply section of this post.


## 2
I have attached the data you need for the second exercise. In addition to a new graph with three factions, you will also notice a csv file with label assignments for half of the members of Crassus's faction. The csv contains two columns: node_id and new_faction. You have to answer the questions for the second exercise:
- Who gathers more more politicians from Crassus's faction?
- Who are the most undecided politicians when it comes to choosing between Caesar and Pompey?

on the remaining half of the set. As for the first exercise, if there are mistakes on our part regarding the data we will change it promptly and let you know.