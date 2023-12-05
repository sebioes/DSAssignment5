Assignment 5 
---------------------

# Team Members

- 

# GitHub link to your (forked) repository

...

# Task 1

Note: Some questions require you to take screenshots. In that case, please join the screenshots and indicate in your answer which image refer to which screenshot.

1. What happens when Raft starts? Why?

Ans: 

2. Perform one request on the leader, wait until the leader is committed by all servers. Pause the simulation.
Then perform a new request on the leader. Take a screenshot, stop the leader and then resume the simulation.
Once, there is a new leader, perform a new request and then resume the previous leader. Once, this new request is committed by all servers, pause the simulation and take a screenshot. Explain what happened?

Ans: 
3. Stop the current leader and two other servers. After a few increase in the Raft term, pause the simulation and take a screenshot. Then resume all servers and restart the simulation. After the leader election, pause the simulation and take a screenshot. Explain what happened.

Ans: 

# Task 2

Indicate the replies that you get from the "/admin/status" endpoint of the HTTP service for each servers. Which server is the leader? Can there be multiple leaders?

Ans: 

Perform a Put request for the key ``a" on the leader. What is the new status? What changes occurred and why (if any)?

Ans:

Perform an Append request for the key ``a" on the leader. What is the new status? What changes occurred and why (if any)?

Ans: 

Perform a Get request for the key ``a" on the leader. What is the new status? What change (if any) happened and why?

Ans:



# Task 3

Shut down the server that acts as a leader. Report the status that you get from the servers that remain active after shutting down the leader.

Ans:

 Perform a Put request for the key "a". Then, restart the server from the previous point, and indicate the new status for the three servers. Indicate the result of a Get request for the key ``a" to the previous leader.

Ans:

Has the Put request been replicated? Indicate which steps lead to a new election and which ones do not. Justify your answer using the statuses returned by the servers.

Ans:

Shut down two servers, including the leader --- starting with the server that is not the leader. Report the status of the remaining servers and explain what happened.

Ans:

Can you perform Get, Put, or Append requests in this system state? Justify your answer.

Ans:

Restart the servers and note down the new status. Describe what happened.

Ans:




# Task 4

1. What is a consensus algorithm? What are they used for in the context of replicated state machines? 

Ans: 

2. What is a consensus algorithm? What are they used for in the context of replicated state machines? 

Ans: 


3. What are Byzantine failures? Can Raft handle them?

Ans: 