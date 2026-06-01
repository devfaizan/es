AD: works on a domain; is just a DB for objects(emp, devices & groups); has different containers called OUs,

DC: works on a domain; one domain can have multiple DCs, handles 
Authentication: credentials> validated from DC not locally > Kerberos protocol generates a Ticket-Granting-Ticket
ticket_lifetime
renew_lifetime
Authorization: tells a user what they can do within a network. checks security groups 
your account belongs to and matches them against the permissions (Access Control Lists) of the resource you are trying to access


DPLC


Restart-Computer -ComputerName "111.222.3.4", "111.222.3.5", "111.222.3.6" -Force


shutdown /m \\111.222.3.4 /r /f /t 0 & shutdown /m \\111.222.3.5 /r /f /t 0
