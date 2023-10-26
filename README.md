# XAMPPv3.3.0-BOF
Exploit Proof-of-Concept code for XAMPP v3.3.0 — '.ini' Buffer Overflow (Unicode + SEH)

## Steps to Reproduce:
1. Run the python script "poc.py", it will create a new file "xampp-control.ini"
2. Open the application (xampp-control.exe)
3. Click on the "admin" button in front of Apache service.
4. Profit

## POC Video
![POC gif Video](../xamppv3.3.0_BOF-POC.gif)
