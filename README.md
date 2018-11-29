#  SELinux Tomcat Custom Profile

This repository includes a custom SELinux profile to prevent RCE exploits such as Struts RCEs, deserialization attacks resulting in RCE and from other attack vectors.  For more details, refer to my blog series on [Defeating RCE Exploits in Webs Apps](https://www.osamaelnaggar.com/defeating-rce-exploits-in-web-apps/)

This repo contains 4 files:

- 3 source files (.te, .fc, .if)
- the compiled policy package (.pp) file
