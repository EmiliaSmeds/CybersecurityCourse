I used the zip-file in the assignment to complete this.


| Issue | How it was found | How it could be fixed |
| --- | --- | --- |
| On the login page anyone can choose to be an administrator | This issue was brough up on the lecture | This could be fixed by removing the Role-option from the register-page, and automatically register everyone as Reserver. Then use an if-statement int he code for those usernames that are administrators. Then I would add a functionality to the system where administrators could change the roles for the users, to be either a Reserver or Administrator. |
| A user can choose whatever birth date, no matter what age | This issue was also brough up on the lecture | This could be fixed by adding a requirement to the code, where the birthdate has to be at least x years ago, and if not, the registering is not possible. |
| The password does not need to be strong | I found this by testing to register with a weak password | The only requirement is that the password has to be 8 characters. It could be fixed by adding more requirements for a password in the code. |
| The booked resources are visible on the front page, before logging in or registering | I found this by testing the page | The names of the persons who have booked the resources are not visible, but I'm not sure if I would like everyone to see what bookings have been made and the exact times, especially if the resources contain names of persons or places. I would make the bookings visible only for registered users by fixing the code so the table isn't visible on the front page. |
| Anyone can add new resources | I found this by testing the page | I think only the administrators should be able to add resources. This could be fixed by hiding the functionality for other users, by using an IF-statement in the code. |


