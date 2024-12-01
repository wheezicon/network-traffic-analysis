# Network Traffic Analysis with Wireshark

This project demonstrates the process of capturing and analyzing HTTP traffic using Wireshark. The goal of this analysis is to highlight potential security risks associated with unencrypted HTTP traffic.

## Steps Followed:
1. Captured network traffic using Wireshark on an HTTP connection.
2. Applied filters to focus specifically on HTTP packets.
3. Analyzed the captured HTTP requests and responses.

## Findings:
- During the capture, I noticed several unencrypted requests and responses (including potential sensitive data) transmitted over HTTP, which is a **security risk**.
- Websites using HTTP are vulnerable to **man-in-the-middle attacks** because the traffic is not encrypted.
- **Best Practice**: Websites should use HTTPS to ensure data encryption and secure communication between the client and the server.

## Screenshots:
Below is a screenshot demonstrating the captured HTTP traffic:

![HTTP Traffic Capture](file:///C:/Users/Shawn/Downloads/Screenshot%202024-12-01%20153318.png)

