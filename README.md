# Grey-coins
This projects aims to demonstate, the working of blockchain and mining of bitcoins.
<br />
## **blockchain.py**
<br />
This file contains the basic structure of a blockchain, it contains basic functions which every blockchain has
following member functions <br />
- create_block(Function to create a new block).<br />
- get_previous_block(return the index of last block present in the blockchain).<br />
- proof_of_work(Function to generate hash of a block with the SHA256 algorithm).<br />
- is_chain_valid(Function to check weather the blockchain is consistent/valid or not).<br />
 <br />
It also contains function which are <br />
- get_chain(Function to display the entire blockchain i.e.  each block with block id, hash , previous hash).<br />
- mine block(Function to add new block to the chain). <br />
<br />
<br />.
### **grey_coins.py**
<br />
-All the 3 files **grey_coins1.py, grey_coins2.py, grey_coins3.py** are almost the same, they are the 3 users and miners in our chain they run on 3 different ports("http://127.0.0.1:5001,"http://127.0.0.1:5002","http://127.0.0.1:5003").
-This is the extension of the file blockchain.py

