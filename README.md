
 <p align="center">
  <img width="500" height="417" alt="Gemini_Generated_Image_bmakh6bmakh6bmak" src="https://github.com/user-attachments/assets/0f95ba2d-7765-48e2-aea0-7dd672cafa51" />

</p>

***Advent of Cyber – Day 1***. McSkidy has vanished, and without her, Wareville is slipping into chaos. The TBFC team is scrambling for answers, and their first clue leads to tbfc-web01, a Linux wishlist-processing server. Somewhere in its files might be evidence of what McSkidy was doing before she disappeared or hints of King Malhare’s bizarre plans for EASTMAS. The investigation begins with digging into that server to uncover the truth.

I reviewed the core commands and habits that make Linux navigation smooth during investigations: <img width="200" height="200" alt="678ecc92c80aa206339f0f23-1762788024698" src="https://github.com/user-attachments/assets/7e99323c-145f-493a-8589-8808e06a9910" />                                           

- **Filesystem navigation:** Using `ls`, `ls -a`, and directory changes to see visible and hidden files.  
- **File inspection:** Using `cat`, `type`, and path awareness to read and verify file contents.
- **Path accuracy:** Noticing how Linux treats capitalization, slashes, and exact file locations.
- **Troubleshooting missing files:** Understanding when a file is genuinely missing vs. when you’re just in the wrong directory or it’s hidden.

These basics sharpened my speed and accuracy during SOC work — especially when digging through artifacts, user directories, or system logs during an investigation.

<img width="500" height="500" alt="Screenshot 2025-12-01 at 9 47 36 PM" src="https://github.com/user-attachments/assets/237de42e-3270-453c-bd3a-e2fa363b8999" />

----

<p align="center">
  <img width="500" height="417" alt="Screenshot 2025-12-02 at 5 19 32 PM" src="https://github.com/user-attachments/assets/2929a1b3-e2f5-41f2-a40e-9b4576d0c3d9" />

</p>

***Advent of Cyber – Day 2***. Today’s focus was phishing operations from a red-team perspective.
 🐍 Hosted a cloned login portal using a Python server script on port 8000 to capture submitted credentials.
 • Validated the page locally to confirm the credential-capture logic was working.
 • Used the Social-Engineer Toolkit (SET) to build and deliver a phishing email with sender spoofing, SMTP setup, and the embedded harvest link.
 📸 Captured valid credentials and after logging into the victim’s mailbox, confirmed they were reused and found internal data, including the 1,984,000 toys 🧸 expected for delivery.
 
<p align="center">
  <img width="500" height="800" alt="Screenshot 2025-12-02 at 5 06 23 PM" src="https://github.com/user-attachments/assets/6bdd0c1a-2392-49d7-8ace-ed17866ac22f" />

 <img width="500" height="250" alt="Screenshot 2025-12-02 at 4 31 01 PM" src="https://github.com/user-attachments/assets/72c3f43f-9b1e-4fa5-b82c-f94756b112ee" />

</p>

----
<p align="center">
 <img width="500" height="417" alt="Gemini_Generated_Image_tgf7ettgf7ettgf7" src="https://github.com/user-attachments/assets/896ac54d-1c3e-4ba1-b8e5-bababb4af52e" />

</p>

***Advent of Cyber – Day 3*** I walked through a full intrusion chain that kicked off from ██████████. The attacker started by poking at sensitive application paths, then ramped up into wide path-traversal and SQL-injection attempts driven by automated tools (████████, ████████). From there, they managed to land remote code execution through a dropped webshell (████████.php) and ran a malicious payload (████████.bin). I also caught attempts to pull archived data off the server (████████.zip, ████████.gz) and confirmed outbound C2 activity coming from the compromised host (██████████). The whole sequence lined up cleanly across the kill chain recon, exploitation, post exploitation, and C2—which made it a solid end-to-end investigation to run through Splunk

<p align="center">
  <img width="500" height="800" alt="5e8dd9a4a45e18443162feab-1762375952691" src="https://github.com/user-attachments/assets/e4073ce0-c628-48e6-b6bc-784a74024108" />

<img width="500" height="800" alt="Screenshot 2025-12-03 at 1 06 27 PM" src="https://github.com/user-attachments/assets/0a9b3d3f-d6f1-41a3-99ce-76d5a514d78a" />

</p>
