# Finding Vulnerable Info Using Google Dorks — Ethical Hacking

> Google Dorking is a technique that hackers use to find information that may have been accidentally exposed to the internet.

first dork:
```js
allintext:username filetype:log
```

second dork:
```js
intitle:”webcamxp 5"
```

third dork:
```js
intext:"index of" "wp-content.zip"
```

fourth dork:
```js
intitle:"index of" /etc/shadow
```