# kr_project2_explanation_by_forgetting

This is a very repository for a very simple code-base for the course Knowledge Representation 2020 of the Master AI.
 
This repository provides a number of (partial) stand-alone versions of established programs (LETHE or the OWL-API) 
with the sole goal of allowing you to programme and evaluate a forgetting-based explanation tool for Project 2 of the course. 
Both those programs are provided as jars. 

The most important file is myProgram.py, which illustrates four the usages of the kr_functions.jar file for loading and 
classifying an ontology, and printing and writing the entailed subclass statements to a fail, and the application of
lethe_standalone for forgetting vocabulary specified in a file signature.txt from an ontology. 

You can run myPrograms.py with your Python installation and you need a Java installation (I believe a runtime version is sufficient). 

If you want more functionality from the OWL-API you might want to modify kr_functions.jar. 
We also provide the java directory that allows you to do this at the following GIT repository 
https://github.com/raadjoe/kr_forgetting.git 
 believe you need a Java jdk version in that case. 
