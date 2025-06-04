# Cyber Security Internship - Task 5

## Task: Capture and Analyze Network Traffic Using Wireshark
---

## Objective:
Capture live network traffic using **Wireshark**, identify different network protocols, and analyze packet data.

---

## Tools Used:
- **Wireshark v4.4.6**
- **Npcap v1.8x**
- **Windows 11/10**
- **Command Prompt**

---

## Steps Followed:

1. Installed Wireshark and verified Npcap was up to date.
2. Selected the **Wi-Fi** interface (active network connection).
3. Started packet capture.
4. Visited websites like:
   - https://www.google.com
   - https://www.wikipedia.org
   - https://www.wireshark.org/#download
   - https://www.wireshark.org/docs/wsug_html_chunked/ChapterIntroduction.html
5. Also used Command Prompt to run:
6. Stopped capture after 1 minute.
7. Applied protocol filters (`http`, `dns`, `tcp`) to identify packet types.
8. Exported the capture as a `.pcap` file.
9. Took screenshots of the process and analysis.

---

## Files Included:
- `network_traffic.pcap` – The captured packet file.
  
## Protocols Identified:

| Protocol | Description | Example Packet Info |
|----------|-------------|----------------------|
| **DNS**  | Domain Name Resolution | Resolved `google.com` to an IP address |
| **HTTP** | Web browsing traffic | GET request sent to `wikipedia.org` |
| **TCP**  | Transport protocol | Used for reliable delivery of HTTP/DNS |
