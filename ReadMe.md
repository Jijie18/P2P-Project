The test can be done on single cumputer or multiple computers.

The version we provide is for running on a single computer.

1. Open four comand windows and enter src/ (or you can use IDE like pyCharm)
2. run **tracker.py, node1.py, node2server.py, node3server.py** in the four window respectively.
3. Input "seeds.txt" in the window of node1.py
4. Check the result.

Of course you can try different nodes, but make sure that the server should be running when the node is sending request to it.



 To test it on multiple computers, you need to change the address in the files: 

1. In node{i}.py, change **addr** (line 4) to the ip address of the computer that runs node{i}.py, for example, ('10.21.12.16', 1000), and change the **serverName** (line 5) to the ip address of the computer that runs tracker.py, for example, '10.21.14.139'.
2. In node{i}server.py, change address in line 6 to the ip address of the computer that runs node{i}server.py, notice that it should be the same with the **addr** in node{i}.py, since each two of them should be run on the same computer.
3. In tracker.py, change the **addr1**, **addr2**, **addr3** (line 4~6) to the addresses of the three client respectively, and change the address in line 49 to the ip address of the computer that runs tracker.py



If you still can't run the test successfully, please check the video we provided, or contact us directly.