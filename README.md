# linux_server_configuration
  Udacity curriculum project. Configuration and deployment of an AWS linux server that hosts 
  a previously completed catalog application. This application is hosted using Amazon Web Services 
  and Lightsail and an Apache2 web server running on Linux with Mod_WSGI.

## Project Details
  ### Configuration Summary
  * File and directory permissions set using octal permission values and the `chmod` command
  * Firewall(Linux's UFW) configured to only allow specific connection types and ports
  * Additional user created for grading purposes and given `sudo` privileges along with a private
    key for key-based authentication when logging in 
  * Uses key-based authentication through key-pairs and a passphrase with user password-based 
    login disabled. Key-pair was created on a local machine (so private key has never been shared 
    with server) using `ssh-keygen`
  * Required installation of Apache2/mod_wsgi(installed through `apt-get`) and manual creation 
    and configuration of Apache config file along with the WSGI file
  * Application functions through a PostgreSQL database. PostgreSQL installed through `apt-get` and 
    configured with an additional user that has limited permissions. A blank database was created and 
    then populated through the application functionality once it became live
  * Several Python 3 modules were required for this application including Flask, SQLAlchemy and Oauth2 
    which were installed into Python 3.5 using `pip3`

  ### Third-Party Resources Utilized
  * Relied upon the following resources for knowledge and information as needed:
    * Udacity Forums
    * Stack Overflow
    * Digital Ocean
    * PostgreSQL Official Documentation
    * Apache Official Documentation
    * Mod_WSGI Official Documentation
    * Flask Official Documentation
