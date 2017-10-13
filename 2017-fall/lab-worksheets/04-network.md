# Worksheet 4: Network

## Instructions

- Due on Sunday at Midnight
- Upload to Courseworks
- I recommend completing the [networking tutorial][02] before starting this
  worksheet.

[02]: https://github.com/dh-notes/dhnotes/blob/master/tutorials/command-line/107-network.md


1. What is your IP Address at the library? What is your IP address at home?
   What is your device's MAC address? (Omit the last four digits for privacy
reasons). Use `ifconfig` to explore. Use `man ifocnfig` to learn about what
you are seeing.

2. Log into your CUNIX account using SSH. Create a folder called `public_html`
   using `mkdir`. Using `nano` create an `index.html` with some minimal
content. I suggest:

```
<!doctype html>
<html lang=en>
<head>
<meta charset=utf-8>
<title>my page</title>
</head>
<body>
<p>Hello world!</p>
</body>
</html>
```

3. Verify that your page works by going to `http://www.columbia.edu/~YOURUNIHERE/`

4. Pick a site that you go to often. Using `traceroute` (you might have to
   install it on your machine) identify some of the servers that stand between
you and that site. Google some of the names to learn about what they are and
where they are located. Report your findings here.

## For an extra challenge

Use `ifconfig` to get the name of your wireless interface. Run something like
`sudo tcpdump -nni NAMEOFYOURWIRELESSIFACEHERE -A -X src port 80 >
payload.txt` to capture a few packets. Try going to several websites that take
input (forms, searches, or logins) to simulate browsing. After some time,
interrupt `tcpdump` (with ctrl-c) and examine the `payload.txt`. Report any
findings here (omit any sensitive information if found).
