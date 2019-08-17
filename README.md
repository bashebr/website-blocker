# Website blocker
This is just a simple script where it helps to block some website from browsing into them. For example, you might be at work
from 8 to 16, then you don't want to access youtube or facebook, on this time, then you should redirect to, your localhost
something that can't be reached.

Example:
redirected sites: www.youtube.com
So, you should write something in hosts directory( /etc/hosts ), a redirect, like the following:
127.0.0.1   www.youtube.com
The it automatically redirects to that page when ever you try to reach youtube in working hours.
