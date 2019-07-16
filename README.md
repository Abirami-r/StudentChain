# StudentChain
Identity verification for university students, built on top of blockchain.

How to use the StudentChain prototype:

1. Install `python3`, along with `flask`, and the `requests` library
1. Run `python3 uninode2.py` - to create a node. Spectator nodes can be set up similarly but will not have any additional
functionality.
1. Go to "http://localhost:5000/add/" to access the form for adding a student as a university node
1. After adding one or more student, click "Mine" to mine a new block in the blockchain, storing records of all the students 
added in the previous step.
1. Go to "http://localhost:5000/check" to verify someone's student status. 
Enter their information and click "Check Student" to check if they are a student on this blockchain.
1. Go to "http://localhost:5000/chain" to view the entire blockchain at any given time.
1. To connect an additional node, repeat steps 1 and 2 and be sure to click "resolve" in the check page before attempting to verify students from the new node.
