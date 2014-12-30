ansible-role-postfix-relay
==========================

Sets up your system to send mail over {{ postfix_relay_host }} and sets domain to {{ postfix_domain }}.
Tested on ubuntu 12.04 and smartos. On smartos generates self-signed certificate for secure connection, on ubuntu it's presented out of the box.