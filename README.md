In this assignment I used replaced Prim's name with mine in the Humger Games text document. First I used the copy command to copy the document from /home/cumoja1 to my submissions folder /home/mamos7/Submissions.

I then entered the document in the vi editor and used the command :%s/Prim/Mya/g to replace every instance of Prim with my name, Mya.

To change the permissions of my folder to only allow the TA and Professor in the folder, I would find out the group that both the professor and TA belong to and I would use the command chgrp -R groupname {MyHungerGames}* with groupName being the group that the TA and Professor belong to. I could also use chown -R newUserID {MyHungerGames}* twice with newuserID being cumoja1 and umuhamood1 giving them ownership of the file. I would also use chmod g+rx {MyHungerGames} or chmod u+rx {MyHungerGames] 
