# Presentation Title
XXE for Dummies (or How to Make an XML Parser Send You Files)

## Description
In 2017 OWASP added XML External Entity (XXE) Processing to its list of Top Ten Vulnerabilities. Do you know what XXE is, how it can be exploited, and how to defend against XXE attacks? Most of the standard examples use open source stacks. Have you seen XXE in .NET? This crystal-clear explanation and demo will give you all the facts.

## Intended Audience
This is a technical talk for software developers. Using simple, easily understood examples, the talk demonstrates how hackers exploit XML External Entities to exfiltrate files from servers.

## Key Takeaways
- XXE attacks are potentially very dangerous.
- They result from exploiting an optional feature of XML that allows user-defined string expansions.
- In most cases XXE vulnerabilities can be avoided as a simple matter of configuration.

## Resources
- [A Compendium of Known Techniques](https://www.nccgroup.com/media/bndihh0n/_xmldtdentityattacks.pdf) by security researcher Tim Morgan.

## Events
- **Name**: BSides PDX
- **Date**: October 2019
- **Location**: Portland, Oregon
- **Recording**: [YouTube](https://youtu.be/ZIYKLjI5ooE?si=pD1LUs9_Pho98ohy)

<br/>

- **Name**: OWASP PDX
- **Date**: April 2021
- **Location**: Portland, Oregon
- **Recording**: [YouTube](https://www.youtube.com/watch?v=bY_Z-9s9xXU&ab_channel=OWASPPortland%2COregon) (improved from 2019)

## Comments
This presentation began as an internal developer training at the company where I worked. I subsequently polished it into a presentation for BSides. Several years later I gave an improved version of the talk for my local OWASP chapter. 

The 2021 version of the OWASP Top Ten Web Application Security Risks dropped XXE as a distinct vulnerability. Instead, it was moved under the more general heading "Security Misconfiguration." "XXE vulnerabilities are less common now that more parsers default to safer configurations, but they persist. I saw it on a pen test as recently as November 2024.

## Contact
I like to give talks. I like giving this talk. If you or someone you know might want me to do that, send email to talks (at) safetylight (dot) dev.

## License
This work is licensed under CC BY-NC 4.0. For full details, visit [Creative Commons License Page](https://creativecommons.org/licenses/by-nc/4.0/).

A summary of the main license points is available [here](https://creativecommons.org/licenses/by-nc/4.0/).