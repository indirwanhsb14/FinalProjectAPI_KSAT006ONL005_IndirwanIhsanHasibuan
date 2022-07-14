<h4>Nama : Indirwan Ihsan Hasibuan<br>
Kode Peserta : KSAT006ONL005<br>
Link Github : https://github.com/indirwanhsb14 </h4>

Explanation of Final Project QA Automation API Testing

-----------------------------------------------------------

Final Project - API Testing : `reqres.in`


`Test Scenarios are in excel to help you understand test case flow`

Test Case and endpoints :
    
 Integration Jira : WP-2 Indirwan-TC Login Website
    
 1. GET
    - TC01 - List Users `/api/users?page=2`
    - TC02 - Single User  `/api/users/2`
    - TC03 - Single User Not Found  `/api/users/23`
    - TC04 - List `/api/unknown`
    - TC05 - Single `/api/unknown/2`
    - TC06 - Single Not Found `/api/unknown/23`
    - TC15 - Delayed Response `/api/users?delay=3`

 2. POST
    - TC07 - Create `/api/users`
    - TC11 - Register Successful  `/api/register`
    - TC12 - Register Unsuccessful  `/api/register`
    - TC13 - Login Successful `/api/login`
    - TC14 - Login Unsuccesful  `/api/login`

 3. PUT
    - TC08 - Update `/api/users/2`
   
 4. PATCH
    - TC09 - Update `/api/users/2`
 
 5. DELETE
    - TC10 - Delete `/api/users/2`

-----------------------------------------------------------------------------
<h4>How to use :<h4>

<br>

     1. Open Project With Katalon

     2. Run Test Case if you want run one by one

     3. Run Test Suites endpoint if you want to run one endpoint at a time

     4. Run Test Suites Collection if you want to run all test suites at once

     5. Open Report if you want see and share the result
