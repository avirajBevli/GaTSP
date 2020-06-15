# GaTSP
Implementation of the Travelling Salesman Problem using genetic algorithm

bier127.txt = Sample file from the TSPLIB data set collection

data_cleanser.cpp = Program to read the file bier127.txt (or any other data set file) and output a file "city_coord_data.txt" which contains the coordinates of all the cities in the data set, which is in a format that can be read by the main program

main.cpp = main file for running GA on the TSP problem with the city coordinates read from the file "city_coord_data.txt". It outputs various txt files containing info about the fiitest chromosome of the generation, fiitest chromosome till now, best fitness of the generation, best fitness till now

graph_plotter.py = python script that inputs the file "city_coord_data.txt",  "best_chromosome_global.txt", "best_total_distance_global.txt", "best_fitness_global.txt" that are generated by main. It then shows a visualisation in a matplotlib window showing the best path evolving over time.
