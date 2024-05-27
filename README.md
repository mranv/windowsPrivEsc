
# Windows Privilege Escalation

This repository contains a collection of tools and scripts written in Rust for performing privilege escalation on Windows systems. These tools are designed to assist penetration testers and security researchers in identifying and exploiting vulnerabilities that can lead to elevated privileges.

## Tools

### AlwaysInstallElevated

This tool identifies and exploits the "AlwaysInstallElevated" registry key vulnerability, which allows non-privileged users to install Microsoft Windows Installer packages with elevated (SYSTEM) permissions.

### Get-Unquoted

A script that enumerates and identifies unquoted service paths on the system. Unquoted service paths can potentially be exploited to gain elevated privileges by loading malicious binaries from vulnerable directories.

## Usage

Each tool or script has its own set of instructions and options, which can be accessed by running the tool with the `--help` flag. For example:

```
Compile it with rust.c to use it in a windows environment.
```

## Contributing

Contributions to this repository are welcome! If you find any issues or have ideas for new tools or improvements, please open an issue or submit a pull request.

## Disclaimer

These tools are provided for educational and research purposes only. They should be used only on systems or networks where you have explicit permission to perform security assessments. Any unauthorized or unlawful use is strictly prohibited.

The tools in this repository are designed to exploit known vulnerabilities and misconfigurations in Windows systems. While they can be useful for ethical security testing and research, they should never be used for malicious purposes or without proper authorization.

It is important to note that the use of these tools may have unintended consequences or cause system instability if not used correctly. Always exercise caution and thoroughly understand the potential risks before using any of these tools.

By using the tools in this repository, you agree to use them solely for legal and authorized purposes, and you assume all responsibility for their use. The authors of these tools are not responsible for any misuse or damages caused by these tools.
