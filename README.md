# XAMPPv3.3.0-BOF
Proof-of-Concept exploit code for XAMPP v3.3.0 — '.ini' Buffer Overflow (Unicode + SEH)

## Steps to Reproduce:
1. Run the python script "poc.py", it will create a new file "xampp-control.ini"
2. Open the application (xampp-control.exe)
3. Click on the "admin" button in front of any service (e.g Apache, MySQL).
4. Profit

## POC Video
![POC gif Video](https://github.com/ripp3rdoc/XAMPPv3.3.0-BOF/blob/main/xamppv3.3.0_BOF-POC.gif?raw=true)
