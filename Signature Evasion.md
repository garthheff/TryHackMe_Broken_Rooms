https://tryhackme.com/room/signatureevasion

Reported: 23/04/2025

Confirmed fix: ? 

## Automating Signature Identification 

Issue: Path says tools are within Administrator folder but is student folder.

```
ThreatCheck does not provide a pre-compiled release to the public.
For ease of use we have already compiled the tool for you; it can
be found in `C:\Users\Administrator\Desktop\Tools` of the attached machine.
```

Should be 

```
ThreatCheck does not provide a pre-compiled release to the public.
 For ease of use we have already compiled the tool for you;
it can be found in `C:\Users\Student\Desktop\Tools` of the attached machine.
```
