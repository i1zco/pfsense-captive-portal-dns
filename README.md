# pfSense DNS issue with Captive Portal not redirecting


## The problem:

Login page Captive Portal It does not appear on network devices.
curl It does not provide a redirect.


## the solution:
The device itself or the client does not pfsense As Getaway And DNS It refers to the router itself, not pfsense


## How to solve the problem practically:
In Windows, 

press (Windows + R)
Write (control)
Go to option Adapter Settings
Left-click on the root network card that provides the computer with internet access.
Select Properties and go to TCP IPv4 Press it twice
Choose the manual option and edit The domain name server, so that it points to...pfsense And also Getaway So that it pfsense

