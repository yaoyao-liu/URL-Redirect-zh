# URL Redirect via GitHub
Sometimes, you register a domain but you don't have a server. You may want this domain to redirect to your homepage/FB/IG or etc. However, most domain registrars do not provide this service, or this service charges. At this point, you can do url redirecting with the github page.

First, create a new empty repo and import this repo to it.

Second, add a CNAME record to your domain as follows:
```
Host: whatever you want. e.g. "www"
Target / Canonical name: your_username.github.io.
TTL: 20 min
```

Third, change the contents of the "CNAME" file in the repo to your domain.

Fourth, replace the URL is the "index.html" to whatever your want.
