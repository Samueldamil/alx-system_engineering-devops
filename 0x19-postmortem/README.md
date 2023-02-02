  REMOTE SERVER FAILURE:
Last month, it was reported that the remote server web-01 was returning 403 e
rror (permission denied) anytime i need to connect to the server, all the ser
vice were down because i could not access the server. 90% of the users were a
ffected. The root cause was the ssh public key.

TIMELINE:
The error was realised on Friday 9th December 2022 1:00pm (West Africa Time)
when i saw that i could not connect to the server. I consulted other software
 engineers for help and due to their advice, i created the new ssh key, added
 it to my profile on the alx intranet and i asked for a new server. The probl
em was solved by Monday 12th December 2022 10:00am (West Africa Time).

ROOT CAUSE AND RESOLUTION:
The web-01 server is supposed to serve all request but i did not have connect
ion to the server as a result of not generating a new ssh key.
The issue was fixed when i created the new ssh plublic key using ssh-keygen,
updated it on my intranet profile and asked for a new server.

CORRECTIVE AND PREVENTIVE MEASURE:
• Establish a secure connection
• Use SSH Keys Authentication
• Ensure that your ssh key is correct when copying it to your intranet profil
e.
