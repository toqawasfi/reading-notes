Hash Table Cheat Sheet
Overview:
Hash table is a data structure that stores key-value pairs.
It uses a hash function to map keys to indices in an array.
Operations:
Insertion:

Compute the hash value of the key.
Map the hash value to an index in the array.
If the index is empty, insert the key-value pair.
If there's a collision (multiple keys hash to the same index), handle it (explained below).

Retrieval:

Compute the hash value of the key.
Map the hash value to an index in the array.
Retrieve the value associated with the key.
Deletion:

Compute the hash value of the key.
Map the hash value to an index in the array.
If the index is not empty, delete the key-value pair.