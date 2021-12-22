
![logo](./doc/images/logo.png)

# usefull-elevation-of-privilege

[English](./README.md) | [中文简体](./README_zh.md)

| Category | instruction |
| ---- | --- |
| Author | [0x727](https://github.com/0x727) | 
| Team | [0x727](https://github.com/0x727) Open source tools will continue for some time to come |
| Position | This is used to store information about Windows privilege escalation exploits |
| Language | C++、C#... |



## Windows Elevation of Privilege

| CVE                                                       | Verified | Exploit                                                   | Comment |
| --------------------------------------------------------- | -------- | --------------------------------------------------------- | ------- |
| [CVE-2021-1675](https://msrc.microsoft.com/update-guide/zh-cn/vulnerability/CVE-2021-1675) | true     | [CVE-2021-1675](https://github.com/cube0x0/CVE-2021-1675) | :zap: :zap: :zap: :zap:   |
|  [CVE-2021-34527](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-34527)    | true    |    [CVE-2021-34527](https://www.anquanke.com/post/id/246818)    |   :zap: :zap: :zap: :zap: |
| [CVE-2020-1472](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-1472) | true | [CVE-2020-1472](https://github.com/gentilkiwi/mimikatz) |  :zap: :zap: :zap: :zap: |


### CVE-2021-1675 & CVE-2021-34527

<details>
  <summary>影响范围</summary>
Windows Server 2012 R2(Server Core installation)

Windows Server 2012 R2

Windows Server 2012(Server Core installation)

Windows Server 2012

Windows Server 2008 R2 for x64-based Systems Service Pack 1(Server Core installation)

Windows Server 2008 R2 for x64-based Systems Service Pack 1

Windows Server 2008 for x64-based Systems Service Pack 2(Server Core installation)

Windows Server 2008 for x64-based Systems Service Pack 2

Windows Server 2008 for 32-bit Systems Service Pack 2(Server Core installation)

Windows Server 2008 for 32-bit Systems Service Pack 2

Windows RT 8.1

Windows 8.1 for x64-based systems

Windows 8.1 for 32-bit systems

Windows 7 for x64-based Systems Service Pack 1

Windows 7 for 32-bit Systems Service Pack 1

Windows Server 2016(Server Core installation)

Windows Server 2016

Windows 10 Version 1607 for x64-based Systems

Windows 10 Version 1607 for 32-bit Systems

Windows 10 for x64-based Systems

Windows 10 for 32-bit Systems

Windows Server, version 20H2(Server Core Installation)

Windows 10 Version 20H2 for ARM64-based Systems

Windows 10 Version 20H2 for 32-bit Systems

Windows 10 Version 20H2 for x64-based Systems

Windows Server, version 2004(Server Core installation)

Windows 10 Version 2004 for x64-based Systems

Windows 10 Version 2004 for ARM64-based Systems

Windows 10 Version 2004 for 32-bit Systems

Windows 10 Version 21H1 for 32-bit Systems

Windows 10 Version 21H1 for ARM64-based Systems

Windows 10 Version 21H1 for x64-based Systems

Windows 10 Version 1909 for ARM64-based Systems

Windows 10 Version 1909 for x64-based Systems

Windows 10 Version 1909 for 32-bit Systems

Windows Server 2019(Server Core installation)

Windows Server 2019

Windows 10 Version 1809 for ARM64-based Systems

Windows 10 Version 1809 for x64-based Systems

Windows 10 Version 1809 for 32-bit Systems
</details>

<details>
  <summary>相关文章</summary>

- [POC公开 CVE-2021-1675：Windows Print Spooler远程代码执行漏洞通告](https://www.anquanke.com/post/id/245747)
- [Windows 打印后台处理程序远程执行代码漏洞](https://msrc.microsoft.com/update-guide/zh-cn/vulnerability/CVE-2021-1675)

</details>

## Contributing

Interested in getting involved? We would like to help you!

* Take a look at our [issues list](https://github.com/usefull-elevation-of-privilege/issues) and consider sending a Pull Request to **dev branch**.
* If you want to add a new feature, please create an issue first to describe the new feature, as well as the implementation approach. Once a proposal is accepted, create an implementation of the new features and submit it as a pull request.
* Sorry for my poor English. Improvements for this document are welcome, even some typo fixes.
* If you have great ideas, email 0x727Team@gmail.com.


## Stargazers over time

[![Stargazers over time](https://starchart.cc/0x727/usefull-elevation-of-privilege.svg)](https://github.com/0x727/usefull-elevation-of-privilege)