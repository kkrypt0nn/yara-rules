# YARA Rules

A collection of YARA rules I’ve created for personal projects or gathered from research.

## Usage

1. Install YARA: https://github.com/VirusTotal/yara
2. Clone or download this repository.
3. Run YARA against a target file or directory using the rules in the `rules/` folder.

Example:

```bash
# Single rule
yara rules/malware/APT_Lotus_Blossom_Chrysalis_Backdoor.yar /path/to/scan

# Single rule, recursive path to scan
yara rules/malware/APT_Lotus_Blossom_Chrysalis_Backdoor.yar -r /path/to/scan
```

## Structure

`rules/` contains all the YARA rules.

## Contributing

Rules are for personal use and research purposes. Contributions are welcome, but please ensure rules are tested and are ideally unique.

## Disclaimer

These rules are provided as-is. Use at your own risk.
