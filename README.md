<h1>Disk Sanitization</h1>

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Problems Solved by Disk Sanitization</h2>
Disk sanitization addresses critical security risk associated with data remanence, the residual tracesof data that remain on storage media even after deletion or formatting.

## Use Cases

This tool is ideal for real-world IT security and support scenarios, including:

- **End-of-life device disposal**: Securely wipe HDDs, SSDs, and removable media before recycling, donation, resale, or decommissioning to protect sensitive data.
- **Compliance and regulatory requirement**: 
Achieve verifiable sanitization per **NIST SP 800-88** guidelines (Clear, Purge, Destory metjods) for audits in regulated industries.
-**Incident response and breach containment**: Quickly erase potentially compromised drives to remove malware or sentitive data during security incidents.


Built with a focus on practical, verifiable wiping (multi-pass overwrite, verification, progress tracking), perfect for IT Support, SOC analysts, and aspiring security professionals.
