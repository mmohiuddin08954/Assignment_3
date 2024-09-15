# Project Overview
This project contains two key algorithm implementations: Randomised Quicksort and Hashing using Chaining. The purpose is to evaluate and compare their behavior in respect to the input signals, and thereby design an analytical and experimental assessment. This repository also contains the code for the implementations as well as a report of the conclusions and outcomes.
# How to Run the Code
Prerequisites; Ensure you have Python installed on your system. 
# Summary of Findings
# Randomized Quicksort
•	Theoretical Performance - The time complexity of Randomized Quicksort is the worst-case time complexity is O(n) and the best/worst case space complexity if O(1). Randomized pivot selection that means we will select a random middle element to compare with other elements of the array also eliminates worst case scenarios like the already sorted arrays which will take O(n2) time in Deterministic Quicksort. 
•	Empirical Results - The performance of Randomized Quicksort proves to be thereby uniformly superior to that of Deterministic Quicksort particularly when applied on sorted and reverse sorted arrays. It performs near to O(nlogn) in all the test cases while the performance of Deterministic Quicksort is an issue in sorted or reverse sorted inputs.
# Hashing with Chaining
•	Theoretical Performance - For insertions, deletions and search operations each the best performing case of simple uniform hashing has an expected time complexity of O(1 +λ), where λ is the average load factor defined as number of elements divided by number of slots in the hash table. 
•	Empirical Results - When the load factor of the hash table is low the system runs with efficiency. The worst case is for insertions, searches and deletions, they slow down as the load factor goes higher due to forming of long chains. Dynamic resizing reconstructs the hash table in a way that increases efficiency because the load factor is maintained low.
