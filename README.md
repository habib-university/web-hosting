# Web Hosting

This project is to set up a web server on the DSSE server. The main components seen so far are
1. Setting up an SFTP server with the following features
    1. synchronized with Active Directory for user authentication
    1. a root directory with a default quota for successfully authenticated users.
1. Setting up an Apache web server with the following features
    1. reads user data from the SFTP server
    
## Files
There are 3 files for now.
- progress.md: to track daily progress
- queries.md: to collect and solve queries
- resources.md: links to useful resources

## Winter Break Deliverables
- Set up an SFTP server that uses HU's Active Directory for authentication
    - if no integration with HU's AD, then introduce new login credentials
    - Set up user accounts with a fixed quota, possibly using [cPanel](https://cpanel.net)
- Set up an Apache web server accessible at a desired URL
    - URL to be finalized with WS
- Link the webserver to the SFTP accounts
