
<img width="798" height="125" alt="image" src="https://github.com/user-attachments/assets/08d921b4-fb9f-4e4d-a78e-bcf3ceb54bab" />

<br>
<br>

You can access this room at the following link:
**https://tryhackme.com/room/neighbour*

<br>

Per the instructions, open the web browser and navigate to the following URL using the AttackBox: http://10.65.190.62
The page loads to a login screen that includes a form which accepts a username and password.
There is a blurb at the bottom of the form which states Don't have an account? Use the guest account! And directs you to hit (Ctrl+U).

<br>

<img width="1865" height="654" alt="image" src="https://github.com/user-attachments/assets/19987db3-069e-4dd6-add4-be4cf4676711" />

<br>
<br>

Doing this will open up a new tab in the browser which displays the website code. An alternate way of view this is to use the developer tools which can be access by right clicking on the page and selecting inspect.
This looks like pretty standard HTML. However, if you scan towards the bottom, you can see a comment that contains the credentials guest:guest to use in the login form. It also mentions that the "admin" user account is off limits.

<br>

<img width="1066" height="641" alt="image" src="https://github.com/user-attachments/assets/97a2ceb6-0429-4c51-9136-091d15d76705" />

<br>
<br>

After logging in with the guest account credentials, you are directed to a page with a message that states 'Hi, guest. Welcome to our site. Try not to peep your neighbor's profile."
Using Ctrl+U to view the source code of this page is a good idea, but in this instance it doesn't provide any additional clues.
However, if you look at the URL in the browser window, you will see that the url ends with "user=guest"

<br>
<br>

<img width="1949" height="505" alt="image" src="https://github.com/user-attachments/assets/2e5ecf5c-f229-495c-9136-eb4456641826" />
















