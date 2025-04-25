# This is a snapshot of Solidity repo at the time when it was still lllc support. 
The lllc support here continues to handle new opcodes as lllc is used in the ethereum/tests repo

# !!! THERE IS NO UPDATED SOLIDITY HERE !!!

## How to build and install
* sudo apt install build-essential z3
* mkdir build && cd build && cmake .. -DCMAKE_BUILD_TYPE=Release -DLLL=1  && make
* Now run either:
    * `sudo make install` (if you want to install all binaries, might overwrite e.g. your solc)
    * `sudo cp ./lllc/lllc /usr/local/bin/ && sudo chmod +x /usr/local/bin/lllc` (if you only want to install lllc)
