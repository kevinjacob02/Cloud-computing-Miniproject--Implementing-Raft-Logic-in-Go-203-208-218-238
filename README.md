# Cloud-computing-Miniproject--Implementing-Raft-Logic-in-Go-203-208-218-238
Implementing Raft Logic in Go

## **In this project, you will:**

1. Learned the basics of GoLang.
2. Understood the basic logic behind Raft
3. Implemented part of the logic behind raft, in GoLang, for leader election and log replication.

We have implemented **4** specific functionalities:

1. Implemented the **becomeFollower** function entirely.
2. Implemented the logic for a **follower** node to handle a received **RequestVote function** from a candidate.
3. Implemented the logic for a **candidate** to handle a reply to the above RequestVote it sent out to its peers, be it successfully or unsuccessfully.
4. Implemented the logic for the **leader** to commit its log successfully in the event of majority confirmation, or fail in case majority confirmation is not received.



