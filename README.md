# Paper Backups of Ascii GPG Keys
Scripts for encoding GPG keys into QR codes and QR codes into GPG keys

## Dependencies
* [zbar](https://zbar.sourceforge.net/)
* [qrencode](https://fukuchi.org/works/qrencode/index.html.en)

## Examples
Export Keys From GPG
```bash
gpg --a --export-secret-keys KEY_ID > sec.asc
```
Convert To QR Code
```bash
./asc2qr sec.asc 
```
Convert To Ascii Armor Key Files
```bash
./qr2asc sec.asc-*.qr.png    
```