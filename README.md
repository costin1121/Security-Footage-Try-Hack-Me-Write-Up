# Security-Footage-Try-Hack-Me-Write-Up
1. We open the .pcap file using Wireshark.
2. Since it involves video cameras and we observe the GET request, we conclude that it is about video images.

  ![Capture](https://github.com/user-attachments/assets/d45e93c3-6f73-4e9a-a6e9-99665769f0cc)

3. We add the following filter in Wireshark: tcp.contains "image"

   ![Capture1](https://github.com/user-attachments/assets/6cc0a2c8-62ee-4584-a4ba-d5a805edf591)

4. Right-click on Follow TCP Stream, and in the Show and save data as section, select the Raw option.

  ![capture 2](https://github.com/user-attachments/assets/cd14c167-3feb-4c57-8818-a5a67ef13b46)

5. Click the Save As button and save the file with the .mjpeg extension.
6. The file can be opened with any video editor, and the flag is visible in the video


