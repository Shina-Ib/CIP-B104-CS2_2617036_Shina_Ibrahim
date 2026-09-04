# Digital Forensics Investigation – Beat Step Case
Case Overview

This project documents a digital forensic investigation into the alleged theft and distribution of two Beat Step audio files:

1. Contraband.mp3 – copyrighted audio intended for the movie Fate With Money
2. Sample-1.mp3 – confidential audio intended for a private meeting
The investigation focuses on identifying whether these files were present on the suspect computer, how they were acquired and distributed, and whether torrenting, email, browser activity, or other artefacts can associate the activity with Kamryn Allen or Willis Gibbs.

**Investigation Objectives**
The investigation was designed to examine:

1. Disk partitions, Windows environment, and system configuration
2. NTFS MFT and USN Journal activity
3. MP3 files and their cryptographic hashes
4. Torrent files, torrent client activity, and peer information
5. Thunderbird email artefacts and attachments
6. Microsoft Edge and Internet Explorer browser history
7. Tracker-list and torrent-upload activity
8. Timeline correlations between file, email, browser, and P2P events
9. Evidence linking the activity to the individuals involved


**Evidence Access Limitation**
The supplied forensic disk-image download was not available for analysis during the investigation. Attempts to obtain the image repeatedly returned a "temporarily disabled" message from the provided download link.

Because the disk image could not be acquired, I was unable to complete the full forensic examination of the image or independently verify all case artefacts and supplied reference hashes.

However, I was still able to perform and document available forensic commands and analysis procedures within the laboratory environment, including working with the provided case materials and demonstrating the relevant investigation techniques.


**Status
Investigation status: Partially completed**

The project therefore serves as a record of the forensic methodology, laboratory work performed, commands used, and findings that could be established from the accessible evidence. Conclusions requiring direct examination of the unavailable disk image are clearly distinguished from verified laboratory observations.


**Key Forensic Areas**
NTFS • MFT • USN Journal • Torrent Analysis • Email Forensics • Browser Forensics • File Hashing • Timeline Analysis • Digital Evidence


**Disclaimer**
This investigation is conducted for academic/laboratory purposes. Any attribution of responsibility should be based only on verified forensic evidence and the limitations of the available evidence should be considered when interpreting conclusions.
