# subdomain-takeover

This is a personal script made to search and test for subdomain takeover using Amass, Findomains and Subjack.
The requirements to use this tool is the same as the requirements for every tool mentioned before.
Theres a filenamed fingerprints.json needed for Subjack, you can place it wherever you like, you just need to set the path in $finger variable.

Basically it use findomain for the first scan and amass for a second and it merge the unique results.
After this it uses subjack for testing if the subdomain can be taken.

Please feel free to use it, change it, and distribute it.
If you think you can improve it, share it with me!
