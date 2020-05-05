# Solution Search Project
[University of Campinas](https://www.unicamp.br/unicamp/)

[Introduction to Artificial Intelligence](https://www.dac.unicamp.br/portal/caderno-de-horarios/2020/1/S/P/IC/MO416)

## Group

* Aissa Hadj - 265189
* Lucas Zanco Ladeira - 188951
* Matheus Ferraroni - 212142
* Maria Vitória Rodrigues Oliveira - 262884
* Oscar Ciceri - 164786

## File Tree

* [Core](https://github.com/lucaslzl/search_ia_p1/tree/master/core) - Main classes.
* [Maps](https://github.com/lucaslzl/search_ia_p1/tree/master/maps) - Maps to be utilized as input.
* [Strategies](https://github.com/lucaslzl/search_ia_p1/tree/master/strategies) - Search strategies implemented.
* [Results](https://github.com/lucaslzl/search_ia_p1/tree/master/results) - Results generated by the strategies.
* [Plots](https://github.com/lucaslzl/search_ia_p1/tree/master/plots) - Plots of the results generated.



## How to execute

* Good idea to use virtualenv
* Tested on python 3.8

1. Clone https://github.com/aimacode/aima-python
2. cd aima-python
3. pip install -r requirements.txt
4. cd ../search_ia_p1/
5. Edit line 2 in the file "core/work.py" to point to aima-python folder
6. run "python main.py --(strategy flag)" to execute

It is worth to point out that you may run "python main.py --help" to visualize all the possible flags and parameters.


For instance, "python main.py --bfs --maps=./maps/map1.txt,./maps/map2.txt" will execute both files with bfs.

To see the state after aplying each action add the tag "--print"


## Open Jupyter Notebook on Google Colab

https://colab.research.google.com/github/lucaslzl/search_ia_p1/blob/master/Pac_man_Project.ipynb


## Points to discuss in the Report

how do we define an optimal solution?

1. compare the methods on their own metrics
2. compare the methods based on game conditions (countdown or bonus points more important)
3. compare the methods based on the device specificities (limited battery life or limited memory)
