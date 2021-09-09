# Grey-coins
This projects aims to demonstate, the working of blockchain and mining of bitcoins.
<br />
## **blockchain.py**
<br />
This file contains the basic structure of a blockchain, it contains basic functions which every blockchain has
following member functions
- create_block(Function to create a new block).
- get_previous_block(return the index of last block present in the blockchain).
- proof_of_work(Function to generate hash of a block with the SHA256 algorithm).
- is_chain_valid(Function to check weather the blockchain is consistent/valid or not).
It also contains function which are 
- get_chain(Function to display the entire blockchain i.e.  each block with block id, hash , previous hash).
- mine block(Function to add new block to the chain).
<br />
<br />
## **grey_coins.py**
-All the 3 files **grey_coins1.py, grey_coins2.py, grey_coins3.py** are almost the same, they are the 3 users and miners in our chain they run on 3 different ports("http://127.0.0.1:5001,"http://127.0.0.1:5002","http://127.0.0.1:5003").
-This is the extension of the file blockchain.py

