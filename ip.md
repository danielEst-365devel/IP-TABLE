
---
### Private IP Address Table

| Device and Interface         | Network Address | First Usable IP Address | Last Usable IP Address | Broadcast Address | Subnet Mask       | Notes                                                                                       |
|------------------------------|-----------------|--------------------------|-------------------------|-------------------|-------------------|---------------------------------------------------------------------------------------------|
| **CEU 3rd Floor, GIG2/0**    | 172.16.10.0     | 172.16.10.1             | 172.16.10.30           | 172.16.10.31      | 255.255.255.224   | Use last usable IP address                                                                  |
| **CEU 3rd Floor, GIG3/0**    | 172.16.10.32    | 172.16.10.33            | 172.16.10.62           | 172.16.10.63      | 255.255.255.224   | Use last usable IP address                                                                  |
| **CEU 1st Floor, GIG0/0**    | 172.16.10.64    | 172.16.10.65            | 172.16.10.94           | 172.16.10.95      | 255.255.255.224   | Use last usable IP address                                                                  |
| **CEU 1st Floor, GIG2/0**    | 172.16.10.96    | 172.16.10.97            | 172.16.10.126          | 172.16.10.127     | 255.255.255.224   | Use last usable IP address                                                                  |
| **CEU 1st Floor, GIG1/0 to CEU 3rd Floor, GIG1/0** | 172.16.10.128   | 172.16.10.129          | 172.16.10.130          | 172.16.10.131     | 255.255.255.252   | Use first usable IP address on CEU 3rd Floor Router side and second usable on CEU 1st Floor Router side |
---
### Public IP Address Table

| Device and Interface         | Network Address | First Usable IP Address | Last Usable IP Address | Broadcast Address | Subnet Mask       | Notes                                                                                       |
|------------------------------|-----------------|--------------------------|-------------------------|-------------------|-------------------|---------------------------------------------------------------------------------------------|
| **ISP, GIG0/0 to CEU 3rd Floor, GIG0/0** | 203.102.98.0  | 203.102.98.1           | 203.102.98.62          | 203.102.98.63     | 255.255.255.224   | Use first usable IP address on ISP Router side and second usable IP address on CEU 3rd Floor Router side |
| **ISP, GIG1/0**              | 203.102.98.64   | 203.102 98.65            | 203.102.98.78           | 203.102.98.79      | 255.255.255.240   | Use last usable IP address                                                                  |
| **ISP, GIG2/0**              | 203.102.98.80   | 203.102.98.81            | 203.102.98.94           | 203.102.98.95      | 255.255.255.240   | Use last usable IP address                                                                  |
---

