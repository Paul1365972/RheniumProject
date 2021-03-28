# Operating System

A microkernel is probably the right choice. Keep the kernel as small as possible, properly isolate programs etc.

Implement a node based permission system.

Super simplified example:
```
    kernel
   /      \           
 Inet   keyboard
   \      /   \       
 web-browser  terminal
```

The Inet module in this case would only provide an api to create outbound connections.
To expand on this idea, a VPN module could be put between the browser and Inet to rewrite the protocol and provide an isolated VPN connection.

This will create a permission hell, but properly isolate untrusted code and solve the problem many end users face, optional security/privacy/anonymity.

Another important feature this would enable is playing games over the bare faster connection, 
but connecting the Browser to the Tor network to stay anonymous, both at the same time,
without switching the OS or even the entire hardware.


### Scrambled thoughts
- NULL-terminated strings bad
- Permission popup should to easily distinguishable from fakes
