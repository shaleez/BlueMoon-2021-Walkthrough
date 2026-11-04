# threats-vs-vulnerabilities

A simple guide to understanding how a threat is different from a vulnerability in cybersecurity.

---

## Overview & Definitions

| Term              | Definition                                                                                                      | Simple Analogy                                              |
|:------------------|:----------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------|
| **Threat**        | Any person, event or action that could harm an asset if it finds a way in, such as an attacker or malware.      | The burglar who is trying to break into the house.          |
| **Vulnerability** | A flaw or gap in a system, process or person that gives a threat the chance to cause damage.                    | The window that was left open, which lets the burglar in.   |

---

## Analysis Table

| No     | Scenario                                                                                              | Category          | Reasoning                                                                                       |
|:------:|:------------------------------------------------------------------------------------------------------|:-----------------:|:------------------------------------------------------------------------------------------------|
| **1**  | A USB drive carrying hidden malware is left in a company car park, hoping a staff member plugs it in. | **Threat**        | USB drop attack, a deliberate external attempt to infect the network through curiosity.         |
| **2**  | A home router is still using the default admin username and password from the factory.                | **Vulnerability** | Default credentials are publicly known, so anyone can log in and take control of the device.    |
| **3**  | An attacker runs a tool that tries thousands of password combinations on a login page.                | **Threat**        | Brute-force attack, an active attempt to guess credentials and break into an account.           |
| **4**  | Customer database backups are saved on a shared drive without any encryption.                         | **Vulnerability** | Unprotected data can be read by anyone who gains access to the drive.                           |
| **5**  | Staff receive an SMS saying their parcel is delayed, with a link to a fake payment page.              | **Threat**        | Smishing, a social engineering attack that uses text messages to steal personal information.    |
| **6**  | A website login page allows unlimited failed login attempts without locking the account.             | **Vulnerability** | Missing protection makes it easy for attackers to guess passwords without being stopped.        |
| **7**  | A staff member resigned six months ago, but their company account is still active.                    | **Vulnerability** | Unused accounts with valid access can be abused and are rarely monitored.                       |
| **8**  | A hacker sits on a public cafe Wi-Fi and secretly captures the data other customers send.             | **Threat**        | Man-in-the-middle attack, where an outsider intercepts communication to steal information.      |
| **9**  | New employees join the company and are never given any cybersecurity awareness training.              | **Vulnerability** | Untrained users are more likely to click harmful links or share sensitive information by mistake. |
| **10** | Pirated software is shared online, but it secretly steals saved passwords from the user's computer.   | **Threat**        | Information-stealing malware, disguised as free software to trick victims into installing it.   |
