# KerbHash

Kerberos RC4 Hash Spray Tool

## Features

- NTLM hash spraying over Kerberos
- Uses Impacket getTGT.py
- User and hash file support
- Delay control
- Valid credential logging

## Usage

```bash
python3 kerbhash.py \
-d htb.local \
-u users.txt \
-p hashes.txt
