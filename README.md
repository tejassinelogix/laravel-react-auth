# Overview
Laravel + react authentication process and registeration using <a href="https://laravel.com/docs/10.x/sanctum" target="_blank">Laravel Sanctum</a>.

Server Requirements
=====================================
<ul>
  <li><a href="https://www.php.net/" target="_blank">PHP Version</a> => 7.4 or higher</li>
  <li><a href="https://laravel.com/docs/master" target="_blank">Laravel Version</a> => 8 or higher</li>
  <li><a href="https://www.mysql.com/" target="_blank">MySQL Version</a> => 5.7 or higher</li>
</ul>

Setup Basic Commands
=====================================
1) git clone repository_url
2) cd laravel-react-auth
3) composer update
4) create database and configure .env database connection
5) php artisan migrate
6) php artisan db:seed
7) php artisan serve

Routes Lists
=====================================
<ol>
  <li> Auth Routes </li>
  <ul>
    <li>User Login : http://127.0.0.1:8000/api/login </li>
    <li>User Register : http://127.0.0.1:8000/api/register </li>
  </ul>
</ol>

Credentials Details
=====================================
<b>User Role</b>
<ul>
  <li>Username : <a href="mailto:user@yopmail.com">user@yopmail.com</a></li>
  <li>Password : user@123456</li>
</ul>

Project Requirement 
=====================================
<ol>
  <li> Authentication Using Laravel Web Gaurd : </li>
  <li>User Role Requirement</li>
      <ul>
          <li> <b> User Registration Fields </b> </li>
          <li> Name : [ Validation Rules : Accept only strings and space, Required ] </li>
          <li> Email : [ Validation Rules : Accept only valid email address, Required ] </li>
          <li> Mobile : [ Validation Rules : Accept only digits maximum lenght 10, Required ] </li>
          <li> Password : [ Validation Rules : Accept only valid password minimum 8 length with alphanumeric, Required ] </li>
          <li> Confirm Password : [ Validation Rules : should be same as Password field, Required ] </li>
          <li> On Registration button give json response successfull register message with token </li>                              
          <li> Generate 5 dummy sample for User role using Factory and Seeder </li>          
          <li> Make Seprate dashboard view ,user table and User model </li>
          <li> <b> User Login Fields </b> </li>
          <li> Email : [ Validation Rules : Accept only valid email address, Required ] </li>          
          <li> On Login button click It will give response with new token and login success message with loggedIn user details.</li>
</ol>
  
References : 
=====================================
a) 123

