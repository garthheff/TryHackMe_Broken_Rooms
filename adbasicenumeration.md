[adbasicenumeration](https://tryhackme.com/room/adbasicenumeration)

Issues found: 20/5/2025 

# Task 1 Introduction
Attackbox does not have interface network yet? did wait for network to start before starting attackbox 

# Task 2 Mapping Out the Network
This step is alittle odd, it sounds like it's saying this is how you add the ip's to the hosts.txt, but this is just for viewing 

``` We can conveniently add the two IPS we've discovered to a text file called "hosts.txt" for our port scans.

user@tryhackme$ cat hosts.txt
10.211.11.20
10.211.11.10
```

should be something like, 

```
echo -e "10.211.11.20\n10.211.11.10" > hosts.txt
cat hosts.txt
10.211.11.20
10.211.11.10
```

# Task 4 Domain Enumeration
Command is slightly wrong 
```enum4linux-ng -A 10.211.11.10 -oA results.txt```

The -oA option in enum4linux-ng expects a file prefix, not a full filename with extension

it should just the base name (no .txt):

``` enum4linux-ng -A 10.211.11.10 -oA results ```
This will generate:

- results.xml
- results.json 

even the switch description says 
``` -oA: Writes output to YAML and JSON files.``` 
