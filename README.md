# reddit-unblock
unblock reddit hostlists

## 1) Open your hosts file with write permissions using Vim which is a built-in text editor.

sudo vim /etc/hosts

Windows users:

Open the Notepad, Open `C:\Windows\System32\Drivers\etc\hosts`

## 2) Paste the following at the bottom of the file.
```
151.101.129.140   i.redditmedia.com 
52.34.230.181     www.reddithelp.com 
151.101.65.140    g.redditmedia.com 
151.101.65.140    a.thumbs.redditmedia.com 
151.101.1.140     redditgifts.com 
151.101.1.140     i.redd.it 
151.101.1.140     old.reddit.com 
151.101.1.140     new.reddit.com 
151.101.129.140   reddit.com 
151.101.129.140   gateway.reddit.com 
151.101.129.140   oauth.reddit.com 
151.101.129.140   sendbird.reddit.com 
151.101.129.140   v.redd.it 
151.101.1.140     b.thumbs.redditmedia.com 
151.101.1.140     events.reddit.com 
54.210.123.98     stats.redditmedia.com 
151.101.65.140    www.redditstatic.com 
151.101.193.140   www.reddit.com 
52.3.23.26        pixel.redditmedia.com 
151.101.65.140    www.redditmedia.com 
151.101.193.140   about.reddit.com 
52.203.76.9       out.reddit.com
```
