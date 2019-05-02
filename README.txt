Author: Kevin Walsingham

This project implements Text Retrieval in the form of jeopardy. It creates a Lucene Index based off of the provided documents in "wiki-docs" and then provides a Mean Reciprocal Rank for 
the questions that are answered in "questions.txt"

It can be compiled through maven with:

mvn compile



The index is already built and stored into my created FSDir which is available in this project and at this link:

https://drive.google.com/drive/folders/1F2iNuVyaSVKNfrimL9AXfVdwxqoQdgV5?usp=sharing



The code in QueryEng.java for building the index is currently commented out.

Run the QueryEng.java class to see the MRR that is returned for running all of the queries from the questions.txt file through the index.
Run the main class with:

mvn exec:java -Pprofile1
