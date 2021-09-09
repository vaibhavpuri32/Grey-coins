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
<br />


## **grey_coins.py**
-All the 3 files **grey_coins1.py, grey_coins2.py, grey_coins3.py** are almost the same, they are the 3 users and miners in our chain they run on 3 different ports("http://127.0.0.1:5001,"http://127.0.0.1:5002","http://127.0.0.1:5003"). <br />
-For communication and performing CURD operations, we have used Postman(You can install it from )
-This is the extension of the file blockchain.py. It gives the user options to add transactions/ mine blocks and gain rewards, it also resolves the issue of longest chain, consideing the longest chain as correct.<br />
-To connect all the nodes together run http://127.0.0.1:{port_number}/connect_node as post request, giving other 2 port addresses as inpt, now you can mine_block, add transactions, to make chain consistent run http://127.0.0.1:{port_number}/replace_chain as get request, to get the current chain of block run http://127.0.0.1:{port_number}/get_chain as get request. <br />
-


## **Run Project**
-To run the project, open 3 terminals and postman, run 3 different python files on 3 different terminals
<br />
- python3 grey_coins1.py <br />
- python3 grey_coins2.py <br /> 
- python3 grey_coins3.py <br />
- run postman in another terminal.
<br />

