# FixChatLag

The chat has a message queue size of 200 while you can only see the last 5 messages.<br>
When this queue is full many people will get a CPU spike with every new incoming message.<br>
This mod sets the queue to a minimum (6) so the lag doesn't get caused.<br><br>
The performance graph shows the cpu response in yellow. You can see 3 spikes that all appeared when a message came in.
<img src="https://i.imgur.com/IfWKdP9.jpg"/>
