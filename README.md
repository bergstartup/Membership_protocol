<h1>Membership protocol</h1>
A distributed algorithm that is used to identify state of processes. Since, in distributed system all processes aren't executed in the same hood. A algorithm is required to handle process join, leaves and churns.
<br><br>
<b>Structure of membership protocol</b><br>
This algorithm is classified into two components,<br>
1.Failure Detector - Detects a process failure.<br>
2.Dissemination - Broadcasts the process failure info to other process.<br><br>

Following are the characteristics of the membership protocol<br>
1.Completeness - If a process fails that will be noted by other process.<br>
2.Accuracy - A process is marked as failed only if its failed.<br>
<br>
<b>Note</b><br>
In asynchronous distributed systems with lossy network, its impossible to achieve a membership protocol that is both complete and 100% accurate.<br><br>

There are several implementation of membership protocol few are,<br>
Ring heart beating<br>
All to All heart beating<br>
Centralized<br>
Gossip protocol<br>
SWIM protocol<br>
<hr>
  In this implementation, we have developed protocol over emulated network which implements pseudo network and process are synchronous, since they follow lock-step execution. Read mp1_specification.pdf for more details on structure.
