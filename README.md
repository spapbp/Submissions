Create Submissions
First I used "mkdir Submissions" while in the /home/sphan10 directory.
Then to change the ownership of the folder I would use chgrp eg-aff-faculty /home/sphan10/Submissions.
Then change the permissions with chmod u=rwx,g=rx,o-rwx /home/sphan10/Submissions.

Hungergames part
First I moved a copy of HungerGames to my Submissions folder  using "cp Hungergames /home/sphan10/Submissions" while in the directory with the HungerGames file.
Then I replaced all instances of Prim with Sage using "sed -i 's/Prim/Sage/g' HungerGames".
Then I used mv "HungerGames MyHungerGames" to rename the file.


