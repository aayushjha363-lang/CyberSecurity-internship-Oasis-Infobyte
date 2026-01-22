

# Network Scanning with Nmap

## Project Objective

The purpose of this project was to perform a basic network scan on a local computer. The scan helps identify which ports are open, what services are running on those ports, and the possible security risks associated with them.

## Methodology

* **Tool Used:** Nmap 7.98
* **Target System:** Localhost (127.0.0.1)
* **Command Executed:** `nmap localhost`

## Scan Results Analysis

After running the Nmap scan, several open TCP ports were detected on the system. Each open port represents a service that is currently active and listening for connections.

| Port | State | Service      | Description                                                                                                     |
| ---- | ----- | ------------ | --------------------------------------------------------------------------------------------------------------- |
| 80   | Open  | HTTP         | Shows that a web server is running on the system, which may be used for hosting websites or local applications. |
| 135  | Open  | MSRPC        | Used by Windows for internal communication between system services and applications.                            |
| 445  | Open  | Microsoft-DS | Supports file and printer sharing in Windows systems and is a common target for cyber attacks if not secured.   |
| 1521 | Open  | Oracle       | Indicates that an Oracle database service is active on the system.                                              |
| 3306 | Open  | MySQL        | Confirms that a MySQL database service is running and accepting connections.                                    |
| 5500 | Open  | Hotline      | Generally linked to Oracle Enterprise Manager or related database management services.                          |

## Conclusion

The Nmap scan revealed that the system is running multiple services, including web, database, and Windows networking services. While some of these services are necessary, open ports such as **445, 3306, and 1521** can pose security risks if left unprotected. To improve system security, access to these ports should be limited to trusted users, and any unnecessary services should be disabled.

