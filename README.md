# Scanmap

Scanmap is a lightweight bash wrapper around Nmap designed to speed up reconnaissance during CTFs, labs, and security assessments.

The tool performs a fast port scan, extracts open ports, launches targeted service enumeration, and displays results with colorized output for improved readability. Its goal is to simplify the typical multi-step Nmap workflow into a single command.

## Features

- Fast TCP port discovery
- Automatic extraction of open ports
- Service and version detection
- Vulnerability checks using Nmap NSE scripts
- Colorized console output
- One-shot execution workflow
- Ideal for CTFs and quick assessments

## Requirements

- Nmap
- Linux-based environment (recommended)

## Usage

```bash
./scanmap.sh <target>
```

### Example

```bash
./scanmap.sh 10.10.10.10
```

## Workflow

1. Perform an initial port scan.
2. Identify open ports.
3. Launch service/version enumeration.
4. Execute vulnerability-related NSE scripts.
5. Present results in a clear, colorized format.

## Disclaimer

This tool is intended for authorized security testing, learning environments, and Capture The Flag (CTF) challenges only. Always obtain proper permission before scanning systems you do not own or manage.

## License

Licensed under the Apache License, Version 2.0. See the `LICENSE` file for details.
