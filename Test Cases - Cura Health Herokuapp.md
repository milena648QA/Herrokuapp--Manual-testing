POSITIVE TEST CASES:

  -----------------------------------------------------------------------------------------------------------------
  **Test Case ID:                                                                        Test Designed by: Milena
  TC001**                                                                                Stojanović
  -------------------- --------------------- ------------------------------------------- --------------------------
                                                                                         

  Test Priority                                                                          Test Designed date:
  (Low/Medium/High):                                                                     05.05.2025.
  High                                                                                   

                                                                                         

  Test Case Name:                                                                        Test Executed by: Milena
  Successfully Login                                                                     Stojanović
  and Logout flow                                                                        

                                                                                         

  Description: Verify                                                                    
  that a user can                                                                        
  successfully login                                                                     
  and logout                                                                             

                                                                                         

  No                   Test Steps            Test Data                                   Expected Result

  1                    Launch the website.    https://katalon-demo-cura.herokuapp.com/   The website is displayed.

  2                    Click on the                                                      The **side-bar menu** is
                       **side-bar menu**.                                                opened with option Home
                                                                                         and Login.

  3                    Click on the                                                      The user is redirected to
                       **Login** link.                                                   the **Login page**.

  4                    Click on the                                                      Text cursor appears and
                       **Username** field.                                               the field\`s outline turns
                                                                                         blue.

  5                    In the field          John Doe                                    The provided data is
                       **Username** enter                                                displayed in the
                       valid data.                                                       **Username** field.

  6                    Click on the                                                      Text cursor appears and
                       **Password** field.                                               the field\`s outline turns
                                                                                         blue.

  7                    In the field          ThisIsNotAPassword                          The provided data is
                       **Password** enter                                                displayed in the
                       valid data.                                                       **Password** field. The
                                                                                         provided data is displayed
                                                                                         as dots.

  8                    Click on the button                                               The user is redirected to
                       **Login**.                                                        the **appointment page**.

  9                    Click on the                                                      The side-bar menu is
                       **side-bar** menu.                                                opened with option Home,
                                                                                         History, Profile and
                                                                                         Logout.

  10                   Click on the                                                      The user is redirected to
                       **Logout** link.                                                  the **website\`s
                                                                                         homepage**.

                                                                                          

                                                                                         

                                                                                         

  **Test Case ID:                                                                        
  TC002**                                                                                

                                                                                         

  Test Priority                                                                          Test Designed by: Milena
  (Low/Medium/High):                                                                     Stojanović
  High                                                                                   

                                                                                         

  Test Case Name: Make                                                                   Test Designed date:
  appointment using                                                                      05.05.2025.
  mandatory fields                                                                       

                                                                                         

  Description: Verify                                                                    Test Executed by: Milena
  that a user can                                                                        Stojanović
  successfully make an                                                                   
  appointment                                                                            

                                                                                         

                                                                                         

  No                   Test Steps            Test Data                                   Expected Result

  1                    Launch the website.   https://katalon-demo-cura.herokuapp.com/    The website is displayed.

  2                    Click on **Make                                                   The user is redirected to
                       Appointment** button.                                             the **Login page**.

  3                    Click on the                                                      Text cursor appears and
                       **Username** field.                                               the field\`s outline turns
                                                                                         blue.

  4                    In the field          John Doe                                    The provided data is
                       **Username** enter                                                displayed in the
                       valid data.                                                       **Username** field.

  5                    Click on the                                                      Text cursor appears and
                       **Password** field                                                the field\`s outline turns
                                                                                         blue.

  6                    In the field          ThisIsNotAPassword                          The provided data is
                       **Password** enter                                                displayed in the
                       valid data.                                                       **Password** field. The
                                                                                         provided data is displayed
                                                                                         as a dots.

  7.                   Click on the button                                               The user is redirected to
                       **Login**.                                                        the **appointment page**.

  8                    Click on the **Visit                                              The cursor appears and the
                       Date (Required)**                                                 C**alendar** is displayed.
                       field.                                                            

  9                    In the **Calendar**   12/05/2025                                  The date is displayed in
                       select the current                                                the field **Visit Date**
                       date.                                                             and is marked with a blue
                                                                                         background in the
                                                                                         **Calendar**.

  10                   Click on the button                                               The user is redirected to
                       **Book Appointment**.                                             the **summary page** with
                                                                                         all booked appointment
                                                                                         data.

  11                   Click on the button                                               The user is redirected to
                       **Go to Homepage**.                                               the **home page**.

                                                                                         

                                                                                         

  **Test Case ID:                                                                        
  TC003**                                                                                

                                                                                         

  Test Priority                                                                          Test Designed by: Milena
  (Low/Medium/High):                                                                     Stojanović
  High                                                                                   

                                                                                         

  Test Case Name: Make                                                                   Test Designed date:
  appointment with all                                                                   05.05.2025.
  data/all fields                                                                        

                                                                                         

  Description: Verify                                                                    Test Executed by: Milena
  that a user can                                                                        Stojanović
  successfully make                                                                      
  appointment filling                                                                    
  in all fields                                                                          

                                                                                         

  **Precondition:**                                                                      
  The user is loged in                                                                   
  and it\`s on the                                                                       
  home page.                                                                             

  No                   Test Steps            Test Data                                   Expected Result

  1                    Click on the field                                                **The dropdown menu** is
                       **Facility dropdown                                               displayed with 3 options.
                       menu**.                                                           

  2                    **Choose the second   HongKong CURA Healthcare Center             **The second option** is
                       option.**                                                         selected and displayed.

  3                    Tick the checkbox                                                 Checkbox **Apply for
                       **Apply for hospital                                              hospital readmission** is
                       readmission**.                                                    ticked.

  4                    Select the second     Medicaid radio button                       The second option from
                       option from                                                       **Healthcare Program** is
                       **HealthCare                                                      selected.
                       Program**.                                                        

  5                    Click on the **Visit                                              The cursor appears and the
                       Date (Required)**                                                 C**alendar** is displayed.
                       field.                                                            

  6                    Enter valid data      15/05/2025                                  The date is displayed in
                       using the keyboard.                                               the field **Visit Date**
                                                                                         and is marked with a blue
                                                                                         background in the
                                                                                         **Calendar**.

  7                    In the field          Enter minimum one character (e.g. **n**)    In the field **Comment**
                       **Comment** enter                                                 entered data is displayed.
                       valid data.                                                       

  8                    Click on the **Book                                               The user is redirected to
                       Appointment** button.                                             the **summary page** with
                                                                                         all booked appointment
                                                                                         data.

  9                    Click on the                                                      The **side-bar** menu
                       **side-bar** menu.                                                opens with the Home,
                                                                                         History, Profile and Login
                                                                                         option.

                                                                                          

                                                                                          

                                                                                         

                                                                                         

  **Test Case ID:                                                                        
  TC004**                                                                                

                                                                                         

  Test Priority                                                                          Test Designed by: Milena
  (Low/Medium/High):                                                                     Stojanović
  High                                                                                   

                                                                                         

  Test Case Name: the                                                                    Test Designed date:
  user can                                                                               05.05.2025.
  successfully view                                                                      
  the history of all                                                                     
  booked appointments                                                                    

                                                                                         

  Description: The                                                                       Test Executed by: Milena
  user will book a new                                                                   Stojanović
  appointment and                                                                        
  verify that all                                                                        
  appointments are                                                                       
  displayed on the                                                                       
  History page                                                                           

                                                                                         

  **Precondition**:                                                                      
  The user has one                                                                       
  booked appointment                                                                     
  at least.                                                                              

  No                   Test Steps            Test Data                                   Expected Result

  1                    Launch the website.   https://katalon-demo-cura.herokuapp.com/    The website is displayed.

  2                    Click on **Make                                                   The user is redirected to
                       Appointment** button.                                             the **Login page**.

  3                    Click on the                                                      Text cursor appears and
                       **Username** field.                                               the field\`s outline turns
                                                                                         blue.

  4                    In the field          John Doe                                    The provided data is
                       **Username** enter                                                displayed in the
                       valid data.                                                       **Username** field.

  5                    Click on the                                                      Text cursor appears and
                       **Password** field                                                the field\`s outline turns
                                                                                         blue.

  6                    In the field          ThisIsNotAPassword                          The provided data is
                       **Password** enter                                                displayed in the
                       valid data.                                                       **Password** field. The
                                                                                         provided data is displayed
                                                                                         as a dots.

  7                    Click on the button                                               The user is redirected to
                       **Login**.                                                        the **appointment page**.

  8                    Click on the field                                                **The dropdown menu** is
                       **Facility dropdown                                               displayed with 3 options.
                       menu**.                                                           

  9                    **Choose the last     Seoul CURA Healthcare Center                **The last option** is
                       option.**                                                         selected and displayed.

  10                   Click on the **Visit                                              The cursor appears and the
                       Date (Required)**                                                 **Calendar** is displayed.
                       field.                                                            

  11                   Enter valid data      12.05.2025                                  The date in the field
                       using the keyboard                                                **Visit Date** is
                       with full-stops                                                   displayed in default
                       instead slash symbol.                                             format and is marked with
                                                                                         a blue background in the
                                                                                         **Calendar**.

  12                   In the field          Entered 370 characters including all types  In the field **Comment**
                       **Comment** enter     of symbols                                  entered data is displayed.
                       valid data.                                                       

  13                   Click on the **Book                                               The user is redirected to
                       Appointment** button.                                             the **summary page** with
                                                                                         all booked appointment
                                                                                         data.

  14                   Click on the                                                      The **side-bar** menu is
                       **side-bar** menu.                                                opened with the option
                                                                                         Home, History, Profile and
                                                                                         Login.

  15                   Click on the                                                      The user is redirected to
                       **History** link.                                                 the **History page** and
                                                                                         **a list of booked**
                                                                                         Appointments is displayed.

                                                                                         

                                                                                         

  **Test Case ID:                                                                        
  TC005**                                                                                

                                                                                         

  Test Priority                                                                          Test Designed by: Milena
  (Low/Medium/High):                                                                     Stojanović
  Medium                                                                                 

                                                                                         

  Test Case Name:                                                                        Test Designed date:
  Inspect the Facebook                                                                   05.05.2025.
  link                                                                                   

                                                                                         

  Description: Verify                                                                    Test Executed by: Milena
  that user is                                                                           Stojanović
  redirected on the                                                                      
  Facebook page                                                                          

                                                                                         

  Pre-condition: The                                                                     
  user is loged in and                                                                   
  it\`s on the home                                                                      
  page.                                                                                  

  No                   Test Steps            Test Data                                   Expected Result

  1                    Click on the                                                      The user is redirected on
                       **Facebook link**.                                                the Facebook page.

  2                    ** **                                                             ** **

  3                                                                                       

  Comment\* - There is                                                                   
  a bug. A new tab                                                                       
  with Facebook page                                                                     
  didn\`t open.                                                                          

                                                                                         
  -----------------------------------------------------------------------------------------------------------------

NEGATIVE TEST CASES:

  -----------------------------------------------------------------------------------------------------------------
  **Test Case ID:                                                                        
  NTC001**                                                                               
  -------------------- ---------------------- ------------------------------------------ --------------------------
                                                                                         

  Test Priority                                                                          Test Designed by: Milena
  (Low/Medium/High):                                                                     Stojanović
  High                                                                                   

                                                                                         

  Test Case Name: The                                                                    Test Designed date:
  user can\`t login if                                                                   05.05.2025.
  leave mandatory                                                                        
  fields empty                                                                           

                                                                                         

  Description: Verify                                                                    Test Executed by: Milena
  that the user can't                                                                    Stojanović
  login with the blank                                                                   
  mandatory fields                                                                       

                                                                                         

  No                   Test Steps             Test Data                                  Expected Result

  1                    Launch the website     https://katalon-demo-cura.herokuapp.com/   The website is displayed.

  2                    Click on the **Login**                                            The user has stayed on the
                       button.                                                           same page, **error
                                                                                         message** is displayed:
                                                                                         ''Login failed! Please
                                                                                         ensure the username and
                                                                                         password are valid.''

  3                                                                                       

  4                                                                                       

                                                                                         

                                                                                         

  **Test Case ID:                                                                        
  NTC002**                                                                               

                                                                                         

  Test Priority                                                                          Test Designed by: Milena
  (Low/Medium/High):                                                                     Stojanović
  High                                                                                   

                                                                                         

  Test Case Name: The                                                                    Test Designed date:
  user can't login on                                                                    05.05.2025.
  Make Appointment                                                                       
  page with wrong                                                                        
  Username                                                                               

                                                                                         

  Description: Verify                                                                    Test Executed by: Milena
  that the user cannot                                                                   Stojanović
  login with wrong                                                                       
  Username                                                                               

                                                                                         

  No                   Test Steps             Test Data                                  Expected Result

  1                    Launch the website     https://katalon-demo-cura.herokuapp.com/   The website is displayed.

  2                    Click on the field                                                Text cursor appears and
                       **Password**.                                                     the field\`s outline turns
                                                                                         blue.

  3                    In the field           ThisIsNotAPassword                         The provided data is
                       **Password** enter                                                displayed in the
                       valid data.                                                       **Password** field. The
                                                                                         provided data is displayed
                                                                                         as a dots.

  4                    Click on the **Login**                                            The user has stayed on the
                       button                                                            same page, **error
                                                                                         message** is displayed:
                                                                                         ''Login failed! Please
                                                                                         ensure the username and
                                                                                         password are valid.''

  5                                                                                       

  6                                                                                       

                                                                                         

                                                                                         

  **Test Case ID:                                                                        
  NTC003**                                                                               

                                                                                         

  Test Priority                                                                          Test Designed by: Milena
  (Low/Medium/High):                                                                     Stojanović
  Medium                                                                                 

                                                                                         

  Test Case Name: The                                                                    Test Designed date:
  user can't login on                                                                    05.05.2025.
  Make Appointment                                                                       
  page with wrong                                                                        
  Password                                                                               

                                                                                         

  Description: Verify                                                                    Test Executed by: Milena
  that the user cannot                                                                   Stojanović
  login with wrong                                                                       
  Password                                                                               

                                                                                         

  No                   Test Steps             Test Data                                  Expected Result

  1                    Launch the website     https://katalon-demo-cura.herokuapp.com/   The website is displayed.

  2                    Click on the field                                                Text cursor appears and
                       **Username**.                                                     the field\`s outline turns
                                                                                         blue.

  3                    In the field           John Doe                                   The provided data is
                       **Username** enter                                                displayed in the
                       valid data.                                                       **Username** field.

  4                    Click on the **Login**                                            The user has stayed on the
                       button                                                            same page, **error
                                                                                         message** is displayed:
                                                                                         ''Login failed! Please
                                                                                         ensure the username and
                                                                                         password are valid.''

  5                                                                                       

  6                                                                                       

                                                                                         

                                                                                         

  **Test Case ID:                                                                        
  NTC004**                                                                               

                                                                                         

  Test Priority                                                                          Test Designed by: Milena
  (Low/Medium/High):                                                                     Stojanović
  Medium                                                                                 

                                                                                         

  Test Case Name: user                                                                   Test Designed date:
  can\`t Make                                                                            05.05.2025.
  Appointment in past                                                                    
  (in previous days)                                                                     

                                                                                         

  Description: Verify                                                                    Test Executed by: Milena
  that the user cannot                                                                   Stojanović
  Make Appointment in                                                                    
  the past (previous                                                                     
  days, weeks,years)                                                                     

                                                                                         

  No                   Test Steps             Test Data                                  Expected Result

  1                    Launch the website     https://katalon-demo-cura.herokuapp.com/   The website is displayed.

  2                    Click on **Make                                                   The user is redirected to
                       Appointment** button.                                             the **login page**.

  3                    Click on the                                                      Text cursor appears and
                       **Username** field.                                               the field\`s outline turns
                                                                                         blue.

  4                    In the field           John Doe                                   The provided data is
                       **Username** enter                                                displayed in the
                       valid data.                                                       **Username** field.

  5                    Click on the                                                      Text cursor appears and
                       **Password** field                                                the field\`s outline turns
                                                                                         blue.

  6                    In the field           ThisIsNotAPassword                         The provided data is
                       **Password** enter                                                displayed in the
                       valid data.                                                       **Password** field. The
                                                                                         provided data is displayed
                                                                                         as a dots.

  7                    Click on the button                                               The user is redirected to
                       **Login**.                                                        the **appointment page**.

  8                    Click on the **Visit                                              The cursor appears and the
                       Date (Required)**                                                 calendar is displayed.
                       field.                                                            

  9                    In the **Calendar**    27/10/2024                                 The user cannot click on
                       select the past date                                              the date in the past
                       (previous date).                                                  because previous dates are
                                                                                         not clickable.

                                                                                         

  Comment\* - In step                                                                    
  9 there is a bug.                                                                      
  The user can select                                                                    
  a date in the past                                                                     
  and Make an                                                                            
  Appointment in the                                                                     
  past.                                                                                  
  -----------------------------------------------------------------------------------------------------------------
