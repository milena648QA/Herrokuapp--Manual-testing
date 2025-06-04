POSITIVE TEST CASES:


|**Test Case ID: TC001**||Test Designed by: Milena Stojanović||
| :- | :-: | :- | :- |
|||||
|Test Priority (Low/Medium/High): High||Test Designed date: 05.05.2025.||
|||||
|Test Case Name: Successfully Login and Logout flow|Test Executed by: Milena Stojanović|||
|||||
|Description: Verify that a user can successfully login and logout||||
|||||
|No|Test Steps|Test Data|Expected Result|
|1|Launch the website.|` `https://katalon-demo-cura.herokuapp.com/|The website is displayed.|
|2|Click on the **side-bar menu**.| |The **side-bar menu** is opened with option Home and Login.|
|3|Click on the **Login** link.| |The user is redirected to the **Login page**.|
|4|Click on the **Username** field.| |Text cursor appears and the field`s outline turns blue.|
|5|In the field **Username** enter valid data.|John Doe|The provided data is displayed in the **Username** field. |
|6|Click on the **Password** field.| |Text cursor appears and the field`s outline turns blue.|
|7|In the field **Password** enter valid data.|ThisIsNotAPassword|The provided data is displayed in the **Password** field. The provided data is displayed as dots.|
|8 |Click on the button **Login**.| |The user is redirected to the **appointment page**.|
|9|Click on the **side-bar** menu.| |The side-bar menu is opened with option Home, History, Profile and Logout.|
|10|Click on the **Logout** link.| |The user is redirected to the **website`s homepage**.|
| | | | |
|||||
|<p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p>||||
|**Test Case ID: TC002**||||
|||||
|Test Priority (Low/Medium/High): High||Test Designed by: Milena Stojanović||
|||||
|Test Case Name: Make appointment using mandatory fields|Test Designed date: 05.05.2025.|||
|||||
|Description: Verify that a user can successfully make an appointment |Test Executed by: Milena Stojanović|||
|||||
|||||
|No|Test Steps|Test Data|Expected Result|
|1|Launch the website.|https://katalon-demo-cura.herokuapp.com/|The website is displayed.|
|2|Click on **Make Appointment** button.| |The user is redirected to the **Login page**.|
|3|Click on the **Username** field.| |Text cursor appears and the field`s outline turns blue.|
|4|In the field **Username** enter valid data.|John Doe|The provided data is displayed in the **Username** field. |
|5|Click on the **Password** field| |Text cursor appears and the field`s outline turns blue.|
|6|In the field **Password** enter valid data.|ThisIsNotAPassword|The provided data is displayed in the **Password** field. The provided data is displayed as a dots.|
|7\. |Click on the button **Login**.| |The user is redirected to the **appointment page**.|
|8|Click on the **Visit Date (Required)** field.| |The cursor appears and the C**alendar** is displayed.|
|9|In the **Calendar** select the current date. |12/05/2025|The date is displayed in the field **Visit Date** and is marked with a blue background in the **Calendar**.|
|10|Click on the button **Book Appointment**.| |The user is redirected to the **summary page** with all booked appointment data.|
|11|Click on the button **Go to Homepage**.| |The user is redirected to the **home page**.|
|||||
|||||
|**Test Case ID: TC003**||||
|||||
|Test Priority (Low/Medium/High): High||Test Designed by: Milena Stojanović||
|||||
|Test Case Name: Make appointment with all data/all fields|Test Designed date: 05.05.2025.|||
|||||
|Description: Verify that a user can successfully make appointment filling in all fields|Test Executed by: Milena Stojanović|||
|||||
|**Precondition:** The user is loged in and it`s on the home page.||||
|No|Test Steps|Test Data|Expected Result|
|1|Click on the field **Facility dropdown menu**.| |**The dropdown menu** is displayed with 3 options.|
|2|**Choose the second option.**|HongKong CURA Healthcare Center|**The second option** is selected and displayed.|
|3|Tick the checkbox **Apply for hospital readmission**.| |Checkbox **Apply for hospital readmission** is ticked.|
|4|Select the second option from **HealthCare Program**.|Medicaid radio button|The second option from **Healthcare Program** is selected.|
|5|Click on the **Visit Date (Required)** field.| |The cursor appears and the C**alendar** is displayed.|
|6|Enter valid data using the keyboard.|15/05/2025|The date is displayed in the field **Visit Date** and is marked with a blue background in the **Calendar**.|
|7|In the field **Comment** enter valid data.|Enter minimum one character (e.g. **n**)|In the field **Comment** entered data is displayed.|
|8|Click on the **Book Appointment** button.| |The user is redirected to the **summary page** with all booked appointment data.|
|9|Click on the **side-bar** menu.| |The **side-bar** menu opens with the Home, History, Profile and Login option.|
| | | | |
| | | | |
|||||
|||||
|<p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p>**Test Case ID: TC004**</p>||||
|||||
|Test Priority (Low/Medium/High): High||Test Designed by: Milena Stojanović||
|||||
|Test Case Name: the user can successfully view the history of all booked appointments|Test Designed date: 05.05.2025.|||
|||||
|Description: The user will book a new appointment and verify that all appointments are displayed on the History page|Test Executed by: Milena Stojanović|||
|||||
|**Precondition**: The user has one booked appointment at least.||||
|No|Test Steps|Test Data|Expected Result|
|1|Launch the website.|https://katalon-demo-cura.herokuapp.com/|The website is displayed.|
|2|Click on **Make Appointment** button.| |The user is redirected to the **Login page**.|
|3|Click on the **Username** field.| |Text cursor appears and the field`s outline turns blue.|
|4|In the field **Username** enter valid data.|John Doe|The provided data is displayed in the **Username** field. |
|5|Click on the **Password** field| |Text cursor appears and the field`s outline turns blue.|
|6|In the field **Password** enter valid data.|ThisIsNotAPassword|The provided data is displayed in the **Password** field. The provided data is displayed as a dots.|
|7|Click on the button **Login**.| |The user is redirected to the **appointment page**.|
|8|Click on the field **Facility dropdown menu**.| |**The dropdown menu** is displayed with 3 options.|
|9|**Choose the last option.**|Seoul CURA Healthcare Center|**The last option** is selected and displayed.|
|10|Click on the **Visit Date (Required)** field.| |The cursor appears and the **Calendar** is displayed.|
|11|Enter valid data using the keyboard with full-stops instead slash symbol.|12\.05.2025|The date in the field **Visit Date** is displayed** in default format and is marked with a blue background in the **Calendar**.|
|12 |In the field **Comment** enter valid data.|Entered 370 characters including all types of symbols |In the field **Comment** entered data is displayed.|
|13|Click on the **Book Appointment** button.| |The user is redirected to the **summary page** with all booked appointment data.|
|14|Click on the **side-bar** menu.| |The **side-bar** menu is opened with the option Home, History, Profile and Login.|
|15|Click on the **History** link.| |The user is redirected to the **History page** and **a list of  booked** Appointments is displayed.|
|||||
|||||
|<p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p>**Test Case ID: TC005**</p>||||
|||||
|Test Priority (Low/Medium/High): Medium||Test Designed by: Milena Stojanović||
|||||
|Test Case Name: Inspect the Facebook link|Test Designed date: 05.05.2025.|||
|||||
|Description: Verify that user is redirected on the Facebook page|Test Executed by: Milena Stojanović|||
|||||
|Pre-condition: The user is loged in and it`s on the home page.||||
|No|Test Steps|Test Data|Expected Result|
|1|Click on the **Facebook link**.| |The user is redirected on the Facebook page.|
|2|** | |** |
|3| | | |
|Comment\* - There is a bug. A new tab with Facebook page didn`t open.||||
|||||


















NEGATIVE TEST CASES:

<table><tr><th colspan="2" valign="bottom"><b>Test Case ID: NTC001</b></th><th></th><th></th></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="2" valign="top">Test Priority (Low/Medium/High): High</td><td valign="bottom"></td><td valign="bottom">Test Designed by: Milena Stojanović</td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="3">Test Case Name:  The user can`t login if leave mandatory fields empty</td><td>Test Designed date: 05.05.2025.</td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="3" valign="bottom">Description: Verify that the user can’t login with the blank mandatory fields </td><td>Test Executed by: Milena Stojanović</td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td>No</td><td>Test Steps</td><td>Test Data</td><td>Expected Result</td></tr>
<tr><td>1</td><td>Launch the website</td><td>https://katalon-demo-cura.herokuapp.com/</td><td>The website is displayed.</td></tr>
<tr><td>2</td><td>Click on the <b>Login</b> button.</td><td> </td><td>The user has stayed on the same page, <b>error message</b> is displayed: ’’Login failed! Please ensure the username and password are valid.’’</td></tr>
<tr><td>3</td><td> </td><td> </td><td> </td></tr>
<tr><td>4</td><td> </td><td> </td><td> </td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td valign="bottom"><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p></td><td valign="bottom"><p></p><p></p><p></p><p></p><p></p></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="2" valign="bottom"><p></p><p></p><p><b>Test Case ID: NTC002</b></p></td><td></td><td></td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="2" valign="top">Test Priority (Low/Medium/High): High</td><td valign="bottom"></td><td valign="bottom">Test Designed by: Milena Stojanović</td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="3">Test Case Name: The user can’t login on Make Appointment page with wrong Username</td><td>Test Designed date: 05.05.2025.</td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="3" valign="bottom">Description:  Verify that the user cannot login with wrong Username</td><td>Test Executed by: Milena Stojanović</td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td>No</td><td>Test Steps</td><td>Test Data</td><td>Expected Result</td></tr>
<tr><td>1</td><td>Launch the website</td><td>https://katalon-demo-cura.herokuapp.com/</td><td>The website is displayed.</td></tr>
<tr><td>2</td><td>Click on the field <b>Password</b>.</td><td> </td><td>Text cursor appears and the field`s outline turns blue.</td></tr>
<tr><td>3</td><td>In the field <b>Password</b> enter valid data.</td><td>ThisIsNotAPassword</td><td>The provided data is displayed in the <b>Password</b> field. The provided data is displayed as a dots.</td></tr>
<tr><td>4</td><td>Click on the <b>Login</b> button</td><td> </td><td>The user has stayed on the same page, <b>error message</b> is displayed: ’’Login failed! Please ensure the username and password are valid.’’</td></tr>
<tr><td>5</td><td> </td><td> </td><td> </td></tr>
<tr><td>6</td><td> </td><td> </td><td> </td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td valign="bottom"><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p></td><td valign="bottom"><p></p><p></p><p></p><p></p></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="2" valign="bottom"><p></p><p></p><p></p><p><b>Test Case ID: NTC003</b></p></td><td></td><td></td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="2" valign="top">Test Priority (Low/Medium/High): Medium</td><td valign="bottom"></td><td valign="bottom">Test Designed by: Milena Stojanović</td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="3">Test Case Name: The user can’t login on Make Appointment page with wrong Password</td><td>Test Designed date: 05.05.2025.</td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="3" valign="bottom">Description:  Verify that the user cannot login with wrong Password</td><td>Test Executed by: Milena Stojanović</td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td>No</td><td>Test Steps</td><td>Test Data</td><td>Expected Result</td></tr>
<tr><td>1</td><td>Launch the website</td><td>https://katalon-demo-cura.herokuapp.com/</td><td>The website is displayed.</td></tr>
<tr><td>2</td><td>Click on the field <b>Username</b>.</td><td> </td><td>Text cursor appears and the field`s outline turns blue.</td></tr>
<tr><td>3</td><td>In the field <b>Username</b> enter valid data.</td><td>John Doe</td><td>The provided data is displayed in the <b>Username</b> field.</td></tr>
<tr><td>4</td><td>Click on the <b>Login</b> button</td><td> </td><td>The user has stayed on the same page, <b>error message</b> is displayed: ’’Login failed! Please ensure the username and password are valid.’’</td></tr>
<tr><td>5</td><td> </td><td> </td><td> </td></tr>
<tr><td>6</td><td> </td><td> </td><td> </td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td valign="bottom"><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="2" valign="bottom"><b>Test Case ID: NTC004</b></td><td></td><td></td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="2" valign="top">Test Priority (Low/Medium/High): Medium</td><td valign="bottom"></td><td valign="bottom">Test Designed by: Milena Stojanović</td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="3">Test Case Name: user can`t Make Appointment in past (in previous days)</td><td>Test Designed date: 05.05.2025.</td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td colspan="3" valign="top">Description: Verify that the user cannot Make Appointment in the past (previous days, weeks,years)</td><td>Test Executed by: Milena Stojanović</td></tr>
<tr><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td><td valign="bottom"></td></tr>
<tr><td>No</td><td>Test Steps</td><td>Test Data</td><td>Expected Result</td></tr>
<tr><td>1</td><td>Launch the website</td><td>https://katalon-demo-cura.herokuapp.com/</td><td>The website is displayed.</td></tr>
<tr><td>2</td><td>Click on <b>Make Appointment</b> button.</td><td> </td><td>The user is redirected to the <b>login page</b>.</td></tr>
<tr><td>3</td><td>Click on the <b>Username</b> field.</td><td> </td><td>Text cursor appears and the field`s outline turns blue.</td></tr>
<tr><td>4</td><td>In the field <b>Username</b> enter valid data.</td><td>John Doe</td><td>The provided data is displayed in the <b>Username</b> field. </td></tr>
<tr><td>5</td><td>Click on the <b>Password</b> field</td><td> </td><td>Text cursor appears and the field`s outline turns blue.</td></tr>
<tr><td>6</td><td>In the field <b>Password</b> enter valid data.</td><td>ThisIsNotAPassword</td><td>The provided data is displayed in the <b>Password</b> field. The provided data is displayed as a dots.</td></tr>
<tr><td>7</td><td>Click on the button <b>Login</b>.</td><td> </td><td>The user is redirected to the <b>appointment page</b>.</td></tr>
<tr><td>8</td><td>Click on the <b>Visit Date (Required)</b> field.</td><td> </td><td>The cursor appears and the calendar is displayed.</td></tr>
<tr><td rowspan="2">9</td><td rowspan="2">In the <b>Calendar</b> select the past date (previous date). </td><td rowspan="2">27/10/2024</td><td rowspan="2" valign="top"><p></p><p>The user cannot click on the date in the past because previous dates are not clickable.</p><p><br></p></td></tr>
<tr></tr>
<tr><td colspan="4">Comment* - In step 9 there is a bug. The user can select a date in the past and Make an Appointment in the past.</td></tr>
</table>

