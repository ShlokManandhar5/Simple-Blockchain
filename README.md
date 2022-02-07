# Blockchain
## A blockchain is a ledger which has been written in such a way that updating the data contained within it becomes very difficult, some say the blockchain is immutable and to all intents and purposes they’re right but immutability suggests permanence and nothing on a hard drive could ever be considered permanent.

<p> In this repo I have develop  simple blockchain with different  programming language just for educational pyrpose.</p>

# Simple-blockchain with c++ <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a>  
<a href="https://github.com/Aryanstha/Simple-Blockchain/tree/main/blockchain%20with%20C%2B%2B">Click here..</a>
<p> As with most C/C++ programs, everything is kicked off by calling the main method, this one creates a new blockchain (line 2) and informs the user that a block is being mined by printing to the output buffer (line 4) then creates a new block and adds it to the chain (line 5); the process for mining that block will then kick off until a valid hash is found. Once the block is mined the process is repeated for two more blocks.</p>

<p>Time to run it! If you are using CLion simply hit the ‘Run TestChain’ button in the top right hand corner of the window. If you’re old skool, you can compile and run the program using the following commands from the command line:</p>

```
gcc -lstdc++ \
    -o TestChain \
    -std=c++11 \
    -stdlib=libc++ \
    -x c++ \
    main.cpp Block.cpp Blockchain.cpp sha256.cpp
./blockchain with c++

```
# With Python <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
## Prerequisites
### To follow along, you should have:

-Some knowledge of Object-Oriented Programming Language with Python
-A basic understanding of using Postman Desktop

## Tools requirements
-Pycharm, Visual Studio Code or Anaconda
-<a href="https://www.postman.com/" >Postman Desktop</a>
-A virtual environment
-<a href="https://flask.palletsprojects.com/en/2.0.x/">Flask</a>

<h2> We make use of Flask to create a web application containing blockchain technology.</h2>

<h2>We also require Postman to make requests to interact with our blockchain. The GET request allows us to retrieve the actual state of our blockchain or to mine a block.</h2>

## Running Via The Web Browser
<h2>Let’s run our app through the web browser. When we run the application on Pycharm, we get a local address to run our app from the terminal:</h2>

![image](https://user-images.githubusercontent.com/67673221/152830936-b132ad1b-2ebf-4385-9d48-9982e0848cd1.png)

<h2>From my terminal, the URL address is 172.20.10.2:5000.</h2>

<h2>In the browser, we start by mining a block, and we do this by calling the mine_block route function we created:</h2>
![image](https://user-images.githubusercontent.com/67673221/152831162-0233597e-82cd-459f-86d2-cbe9c814f95d.png)

<p>To call the mine_block function, we add the function name after the forward-slash, and it runs the code instruction under the block.</p>
<p>From the result, we can see the index of the block, a message showing that the block is mined, the previous hash, the proof of work, and the timestamp.</p>
<p>Every time we refresh the page, it mines a new block. Now, let’s get the chain data by replacing mine_block with get_chain. You should have something similar to the one below:</p>

![image](https://user-images.githubusercontent.com/67673221/152831407-fe3e4592-8c19-49ed-9671-80e9f95ec397.png)


<p>The above functions display the blocks in the chain and their index as intended. Now, let’s repeat this process on the Postman desktop application.</p>

## Running via Postman
<h>To mine a block, we copy the mine_block URL and paste it into the request URL bar. Make sure that the request type is GET before sending the request.</h>

<h>The result should be similar to the ones shown below:</h1>

![image](https://user-images.githubusercontent.com/67673221/152831685-9d2a59f5-5730-48a5-a0e1-271556f7e6c0.png)

Next, let’s get the chain data:

![image](https://user-images.githubusercontent.com/67673221/152831797-67fcbd0a-0b2b-49bd-998b-cb232b4459f5.png)

# conclusion
 ## You can mine a block as well as view the list of blocks in the chain.
 
 




