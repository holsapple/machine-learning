Udacity Machine Learning Nanodegree
Capstone Project: Mushroom Identification

-----------------------------------------

Author: Raymond Holsapple  
Last Update: Jan 28, 2018

-----------------------------------------

Executing this project is very simple. The code is all written in Python 3 
and completely contained in the file "mushroom_id.ipynb". There are no special 
startup instructions. Just open it up using a Python 3 kernel and start executing 
the cells. 

TIME: Executing all cells with all functionality enabled (feature reductions, 
grid searches, making graphs) takes about 30 minutes or so to run.

PYTHON MODULES: matplotlib, numpy, pandas, seaborn, sklearn, and keras

NOTES: 

1) There are no deep NNs processing huge datasets in this project, so there is
no need to run this code on a big machine in an AWS instance. I ran it on my 
MacBook Air just fine. 

2) The code automatically creates PDF figures (via plt.savefig()) and saves them
in a folder 'images'. For example, the code might has many lines similar to this:
plt.savefig('image/my_fig.pdf')
If you want this functionality disabled you'll need to comment out those lines.

3) I have also included a file "mushroom_id.html" in the submission. If you want
to begin by scrolling though this file to get a feel for the code before running
it, feel free to do so.