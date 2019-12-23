# Web Hosting

This project is to set up a web server on the DSSE server. The main components seen so far are
1. Setting up an SFTP server with the following features
  1. synchronized with Active Directory for user authentication
  1. a root directory with a default quota for successfully authenticated users.
1. Setting up an Apache web server with the following features
  1. reads user data from the SFTP server
