Playbook entry 3

Summary:

Wireshark can be used to filter through network traffic. One use for this could be to monitor which devices are the biggest talkers on the network as well as searching for any suspicious activity.  The statistics tab of wireshark can be very useful. You can use it to find the most active devices, which conversations are sending the most information, etc.

Key takeaways
-Use the statistics tab to isolate which conversations are talking the most or least.
-Use the protocol hierarchy tab under the statistics tab to see important information on protocols

Lab summary

Lab31: Filter most active conversations.
Select statistics and then conversations
Click the TCP tab and sort the bytes column to show the highest at the top
This shows us what port the most active conversation is using 

Lab33:Detect suspicious protocols or applications
Open the protocol hierarchy tab under the statistics tab
Apply a filter for the IRC protocol to see all traffic using IRC then find the username and target server


