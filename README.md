Linux Firewall Configuration using UFW

- Objective
      - Configure and test firewall rules using UFW to allow or block traffic.

**Steps Performed**

**1. Enabled UFW:
**
![UFW is enabled](https://github.com/user-attachments/assets/506779f0-74ba-4344-9dbe-4f8510c7717e)

**2. Listed current rules:
**
![View Current Firewalls](https://github.com/user-attachments/assets/d93ed1e3-b956-4fc9-baad-301d343f3093)

**3. Blocked inbound traffic on port 23 (Telnet):
**
![Block Inbound Traffic on Port 23 (Telnet)](https://github.com/user-attachments/assets/06ec3da3-fcfb-4b3f-9523-d6ccbd374c3d)

**4. Tested with telnet:
**
![Connection refused](https://github.com/user-attachments/assets/8543c9e4-e224-4d1b-940a-67b86d9e85a3)

**5. Allowed SSH (port 22):
**
![Allowed SSH](https://github.com/user-attachments/assets/75796f7c-cf63-462e-b79f-a859b4a0eae9)

**6. Removed Telnet block rule:
**
![Rule Deleted](https://github.com/user-attachments/assets/b4b14d39-9818-4522-bf1d-b45642175923)

**7. Listed final firewall rules:
** 
![Final Rules](https://github.com/user-attachments/assets/95237990-1d0c-4e17-b3d3-ba92972843dc)
