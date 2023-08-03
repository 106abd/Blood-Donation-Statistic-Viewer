<h1> Blood-Donation-Statistic-Viewer Web Application </h1>

<h2> Description </h2> 
A place where blood donors can view the statistics of their donation as well as general statistics about all logged blood donations. This website was built using a WAMP stack.

<h2> Installation and Execution Guide </h2>
</div> <b> NOTE: </b> You must have Wampserver installed in order for the installation guide to be effective. </div>
<div></div>
<div> <b> 1.</b> Run Wampserver </div>

<div> <b> 2.</b> Open phpMyAdmin on Wampserver (left click on the WAMP icon on the bottom of windows taskbar and click phpMyAdmin) </div>
<div> <b> 3.</b> Login to phpMyAdmin (if the user has no account, username shall be <b>root</b> with no password) and create a new database titled <b>bloodbanksystem</b>. </div>
<div> <b> 4.</b> Click on the bloodbanksystem database and insert the script "bloodbanksystem" SQL text file (titled bloodbanksystem) by clicking "Import" and then selecting the script. </div>
<div> <b> 5.</b> The "bloodbanksystem" database shall now appear with many tables within it on the menu on the left side of the screen. </div>
<div> <b> 6.</b> Place the "BloodDonationViewer" in the Wampserver WWW folder (left click on the WAMP icon on the bottom of windows taskbar and click www directory) </div>
<div> <b> 7.</b> Place the "BloodDonationViewer" in the WAMP WWW folder </div>
<div> <b> 8.</b> Go to the login page by typing in "localhost/login.php" and typing enter (might be localhost:[PORTNUMBER]/login.php if you have a custom port. </div>
<div> <b> 9.</b> Using PHPmyAdmin, select any health card number from the "healthCardNum" column in table "donor" and enter any health card number into the login bar. If you enter a false health card number, the website will prompt you of this action. </div>
<div> <b> 10.</b> Once logged on, you can navigate to the many pages. </div>

