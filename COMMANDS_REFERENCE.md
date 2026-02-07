# COMMANDS REFERENCE

## enum4linux Commands

- **Basic usage**: `enum4linux [options] <target>`  
- **Options**:
  - `-a` : Retrieve all information  
  - `-U` : List users  
  - `-S` : List shares  

## smbclient Commands

- **Connect to a share**: `smbclient //<target>/<share>`  
- **Options**:
  - `-U <user>` : Specify username  
  - `-p <port>` : Specify port  

## nmap Commands

- **Basic scan**: `nmap <target>`  
- **Scan for SMB services**: `nmap -p 445 --script smb-enum-users <target>`  
- **Scan for open ports**: `nmap -sS <target>`  

---  

*Last updated: 2026-02-07 11:40:24 UTC*