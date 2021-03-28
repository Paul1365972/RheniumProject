# RheniumProject: Reinventing the wheel, but better™

This project aim is to research what a secure system could look like today.
It should be noted that I am in no way an expert and 
am primarily writing this to vent my dissatisfaction in response to the many careless decisions being made.
Like not providing privacy, where it would have been nearly free to implement, 
or the many closed systems that do not expose a proper API or specification that could allow for healthy competition.
With this document I do not intend to attack any person or entity, I love many of the services I indirectly address here
and use them daily, but am frustrated by their anti-competitive and closed nature.

In the past many decisions were made, that seemed and were good at the time, 
but contribute to many security and design issues today.
Especially through the many band-aid fixes that were applied.

That's why one needs to redesign the whole system.

*I hope no one actually takes any advice from here, but please let me know about flaws I did not consider or features 
that are missing. Head over to the [Discussion Page](https://github.com/Paul1365972/RheniumProject/discussions) or 
mail me at [paul1365972@gmail.com](mailto:paul1365972@gmail.com)*


## Goals

Come up with suggestions for all lacking aspects of a current end-user device, from hardware, to operating systems, over software up until networking.

Stay realistic, no single person will be able to change the Internet Protocol, the aim is to imagine a user device that replaces the few current alternatives from the ground up.

Provide such a high standard that intelligence agencies wouldn't be able to compromise the system, and even a government could use it without worry (User as only point of failure).

The current tech landscape actually makes it nearly impossible to write completely secure code, this must change.

### Some guidelines

- Security, Privacy and Anonymity are not a Trilemma, but all build on each other and should be inherently supported by any specification

- Usability, no system is worth anything if users and especially the public don't use them

- Simplicity, if a module cannot be understood by a single person anymore there are bound to be vulnerabilities

- Transparency, a user should only need to trust open-source code or at least be able to isolate untrusted code

- Free, not only in a monetary, but also in a time investment sense

- Standardized, you should be able to seamlessly replace all modules of your system, that can be a file explorer, a tls library or even just an icon

- Sustainability, expect future use cases and make the system extensible, so that we won't repeat history


## Disclaimer

In no way does will any of these ideas ever be implemented.
Again this is mostly me venting, dreaming and hopefully learning something along the way.

Most businesses accept the increase in design flaws and lowered security to provide their service cheaper and faster. 
This is to be expected, many of the tools we use today would not exist otherwise.
This whole stack would not make any sense commercially, at least for the software developers.


## Stack

Archiving these goals requires changes on most levels of a device.

- [**Hardware**](HARDWARE.md)
- [**Operating System**](OPERATING_SYSTEM.md)
- [**Cryptography**](CRYPTOGRAPHY.md)
- [**Networking**](NETWORKING.md)
- [**Web Browser**](WEB_BROWSER.md)


### Scrambled thoughts

- Fix password fatigue
- Cold boot attack
