# Implementation of TextRank Algorithm

## NLP Project Report

### Introduction:

TextRank is a general purpose, graph based ranking algorithm for NLP. It can also be defined as an automatic summarisation technique.

The basic idea implemented by a graph-based ranking model is that of voting or recommendation. Since we work with text, we build a graph that represents the text by interconnecting words (or other text-like entities) with meaningful relations, such that, when one vertex links to another one, it is basically casting a vote for that vertex. The higher the number of votes cast for a vertex, the higher the importance of that vertex.

TextRank algorithm includes two NLP tasks:

   > Keyword extraction task
   > Sentence extraction task

   ---> Keyword Extraction: The aim of keyword extraction algorithm is to automatically identify a set of terms that best describe the given document, and the simplest possible approach to do that is to use a frequency criterion, which unfortunately, leads to poor results. The TextRank keyword extraction algorithm requires no prior training (unsupervised).

   ---> Sentence Extraction: TextRank is very apt for documents involving complete sentences, as it allows for a ranking over text units that are computed recursively based on the information drawn from the entire text.

**Language of implementation:** Python3

**Libraries used:** nltk, string

**Note:** A brief overview of what each block of code does is provided just above it.

Adios mates!
