# PCAP Filter

**A Python script that can be used to filter several .pcap files to find similar IP addresses between them**

- Several .pcap files can be supplied to the script as command line arguments
- The '-x' option can be used to pass a list of IP addresses to be ignored (ex. Google)
- The list of IPs to be ignored should be formatted one per line in a plain text file
- Currently it only searches based on destination IP

## Requisites
- pypcapfile
```sh
pip install pypcapfile
```

## Example
```sh
python pcapFilter.py -x ignore.txt cap1.pcap cap2.pcap
```
