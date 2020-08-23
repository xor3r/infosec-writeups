# Tags
![Class](https://img.shields.io/static/v1?label=Class&message=Reconnaissance&color=green)

# Usage
This is a quickstart with Metasploit framework, it is not an extensive guide.

Initialize database:

```console
msfdb init
```

Run Metasploit console:

```console
sudo msfconsole
```

Start a basic scan with built-in NMAP:

```console
msf> db_nmap -sV <ip-addr>
```

Discover recent hosts:

```console
msf> hosts
```

Discover running services:

```console
msf> services
```

Discover found vulnerabilities:

```console
msf> vulns
```

Search for modules:

```console
msf> search <module-or-exploit>
```

Load modules for exploitation:

```console
msf> use <module-name-or-id>
```

Set exploit to be used:

```console
msf> set PAYLOAD <full-payload-name>
```

Set the interface to run on:
```console
msf> set INTERFACE tun0
```

Set your host address to be the listener:

```console
msf> set LHOST <your-ip-addr>
```

Set remote host address to be the target:

```console
msf> set RHOST <remote-ip-addr>
```

Run the exploit:

```console
msf> exploit
```


# References
[SUID binaries exploitation](https://www.hackingarticles.in/linux-privilege-escalation-using-suid-binaries/)

[SUID systemctl exploitation #1](https://medium.com/@klockw3rk/privilege-escalation-leveraging-misconfigured-systemctl-permissions-bc62b0b28d49)

[SUID systemctl exploitation #2](https://gtfobins.github.io/gtfobins/systemctl/)

[Metasploit](https://github.com/Code-L0V3R/suid_systemctl)