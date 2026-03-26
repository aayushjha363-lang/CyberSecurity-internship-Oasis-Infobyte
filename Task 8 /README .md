
# Task 8: Wireshark Network Traffic Capture

## Objective

To capture and analyze network traffic using Wireshark.

## Tools Used

* Wireshark

## Steps Performed

1. Installed Wireshark and Npcap.
2. Selected active network interface (Wi-Fi/Ethernet).
3. Started packet capture.
4. Generated traffic by browsing websites.
5. Stopped capture after a few minutes.
6. Applied HTTP filter (`http`) to view relevant packets.

## Packet Analysis

* Observed HTTP GET and POST requests.
* Identified source and destination IP addresses.
* Analyzed headers such as:

  * Host
  * User-Agent
  * Status Codes (200 OK, etc.)
* Noted that most traffic is HTTPS (encrypted), limiting visibility.


## Files Included

* wireshark_capture.pcap
  

## Conclusion

Wireshark helps in analyzing network traffic and understanding how data flows across networks. HTTP packets reveal request-response communication, but HTTPS encrypts most modern traffic.


