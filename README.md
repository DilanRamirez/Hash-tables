# Hash-tables

## Description
Natural Language Processing (NLP) is the sub-field of artificial intelligence that deals with designing algorithms, programs, and systems that can understand human languages in written and spoken forms. Word embeddings are a recent advance in NLP that consists of representing words by vectors (or arrays) of floating point numbers in such a way that if two words are similar, their embeddings are also similar.
The task for this lab is to implement hash tables with linear probing to retrieve word embeddings to enable the (hopefully fast) comparison of two given words. You will compare several hash functions and determine which is the best for this task. Implement and compare the following hash functions, where n is the length of the table:
 * 1.	The length of the string % n 
 * 2.	The ascii value (ord(c)) of the first character in the string % n 
 * 3.	The product of the ascii values of the first and last characters in the string % n 
 * 4.	The sum of the ascii values of the characters in the string % n 
 * 5.	The recursive formulation h(”,n) = 1; h(S,n) = (ord(s[0]) + 255*h(s[1:],n))% n 
 * 6.	Another function of your choice

## Author
Dilan R. Ramirez
