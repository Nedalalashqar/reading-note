# Hash Tables

## What is a Hashtable?

> Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

![token](https://he-s3.s3.amazonaws.com/media/uploads/e880c21.jpg)

## Why do we use them?

* **Hold unique values**
* **Dictionary**
* **Library**

## Hashing is implemented in two steps

1- An element is converted into an integer by using a hash function. This element can be used as an index to store the original element, which falls into the hash table.

2- The element is stored in the hash table where it can be quickly retrieved using hashed key.

## Hash function

> A hash function is any function that can be used to map a data set of an arbitrary size to a data set of a fixed size, which falls into the hash table. The values returned by a hash function are called hash values, hash codes, hash sums, or simply hashes.

## Hash maps do this to store values:

* accept a key
* calculate the hash of the key
* use modulus to convert the hash into an array index
* store the key with the value by appending both to the end of a linked list
* Hash maps do this to read value:

## accept a key

* calculate the hash of the key
* use modulus to convert the hash into an array index
* use the array index to access the short LinkedList representing a bucket
* search through the bucket looking for a node with a key/value pair that matches the key you were given
