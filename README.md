<img  src="images/SesameSoftwareLogo-2020Final.png" width="100"><img align=right src="images/RJOrbitLogo-2021Final.png" width="100">

# Deployment Guide 

[![Pre-Installation](images/Button_PreInstall.png)](README.md)[![Installation](images/Button_Installation.png)](guides/installguide.md)[![Registration](images/Button_Registration.png)](guides/RegistrationGuide.md)[![Configuration](images/Button_Configuration.png)](guides/configurationGuide.md)[![Datasource](images/Button_Datasource.png)](Datasources/README.md)

---

## Pre-Install

Data Gathering

* Datasource Credentials
  * Target Database [see Datasource Guide for specifics](Datasources/README.md)
  * Source Data [see Datasource Guide for specifics](Datasources/README.md)
* SMTP Information
  * Information needed
    * SMTP Server: ip/named server 
    * Port: Port to connect on default is 25
    * Mail from : Who is the from on the email being sent *(ie rj@sesamesoftware.com)*
    * Username: Login for mail server (optional, server dependant rules)
    * Password: Password to the server (optional, server dependant rules)
    * Use TLS: True/False if server uses TLS
  * Cloud email accounts
    * Gmail 
      * SMTP Server: `smtp.gmail.com`
      * Port: `587`
      * Mail from : Must be an actual account *(ie rj@sesamesoftware.com)*
      * Username: Login for mail server (Required)
      * Password: Password to the server (Required)
      * Use TLS: `True`
    * office 365
      * SMTP Server: `smtp.office365.com`
      * Port: `587`
      * Mail from : Must be an actual account *(ie rj@sesamesoftware.com)*
      * Username: Login for mail server (Required)
      * Password: Password to the server (Required)
      * Use TLS: True

[Pre-Installation](guides/installguide.md)
