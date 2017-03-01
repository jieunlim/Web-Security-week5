
# Project 5 - Encryption

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is completed:

1\. Symmetric Encrypt/Decrypt
  * [x]  Required: Repair the symmetric encrypt and decrypt code

2\. Encrypted Message 1
  * [x]  Required: Decrypt the government message
  * [x]  Required: Encrypt a response and include in this README
  * Answer: I heard about your current situation. Do you know who hacked APEX? -- The Chairman

3\. Generate Public-Private Keys
  * [x]  Required: Repair the key generator code
  * [x]  Required: Generate keys for "johnsteed" and add him to the Agent Directory

4\. Asymmetric Encrypt/Decrypt
  * [x]  Required: Repair the asymmetric encrypt and decrypt code

5\. Create/Verify Signature
  * [x]  Required: Repair the create and verify signature code
  
6\. Encrypted Message 2
  * [x]  Required: Decrypt the message
  * Message : Cannot access APEX from this location. Send new agent codename and public key so I can contact. Encrypt response to protect codename. Include signature to verify identity and message integrity. -- sydneybristow
  * [x]  Required: Verify the message
  * 1) make signature using agent99 provided private key
  * 2) varify signature with public key from agent99 public key in Apex
  * [x]  Required: Include a response message in this README
  * New agent Code name : (Encrypted with Sydneybristow's puclic key)<br /> 
  ogneEnW3aKFhsaKhqsKyr1Q2csqHpuDS9R/0h9egTbFKVCH4XueeDjQIDIOT1246IPHQSHuXF+5OB8kNvF/P4mvEowkvUF9FBL7IrI0sc2LgM19LIk8SKjuSx/xyS9nDkN11moGmfVd2qjA6klWznIdfENm8xCH84Gm1ZSAJvfxNjGyWIn3P9TgktRPEF3UVdkAUuubf2g/eS6P/N+XYTRonE5KMo81dDY/4DT9mo2n3HBPip8rYYD1vRSTNxMGcibSKK/goPIyN6U7Jpjn5VbItNLCaD73KDg4uAthlfHl2tD3zOU2Pwgn+jzO4kwvGv/3lqL//Q0uPerv29XT4qQ==
  
  3Pn9te/TBvTgCY2/U1W82XMmX4nxw4sNQf9JUaiowFe<br />
  TJf9PA7z2o41/kUxkCKhfV2gUkIAR/aV++lkU7wJXuM2G<br />
  gPOSRwBqE40ofMJQikti84rw8hlNQLR5xTwI29mC/4g0L<br />
  z/oxX20y5utMwbMLyXdibto00JNLZ0gslMKCrANJHbj0e<br />
  YTVKQmXcq0jirav9yIPUdtkyvzFiP4HCd3gphUk6z/ta4or<br />
  uNWa3wi+lVS2UbuugJk2sjJ0XjHxA4vS8VoE2GdM6HzK<br />
  /FjukxK/DKskWgfIG1h2rrBJgtKuqAGn7IZd+0UrAijylDU/<br />
  8IaQA0d6XsJmj+bvgPX6f9x1Q==
  * New agent Puclic key :<br />
-----BEGIN PUBLIC KEY-----<br />
MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEApSBMVYp5hl5u/JHQM1Pj<br />
5nK+XtRRolE2NdaUhF7auLyFEZcZVyYimQ9ZGQ6tkjPzO44gBD17A+MU8s1+g3LY<br />
1nyTa6PF/71W3wvsw4lt/T1qZgwew4kye0zPAVUaKaBLAJb+w5OdT/19nVDuwgWN<br />
FURwZwyp8w3moC/1BqXC6r5D+1OMv9GEOLvaJG7++u7rGT9ed6mh6Vg4aRzP5Sqc<br />
WO7b2ozymGERouVr2oeY2vGiwW2ZIUlPkLGuX/6mjJd/I6qzZaLNRUXhPM1PyhkX<br />
TRV0PqIjKPjYkCIdKdhFjqeT7mpm93/duTNtIeLEdLQMJAn9j/pThhn+LCPDA2cI<br />
9QIDAQAB<br />
-----END PUBLIC KEY-----<br />
  * Signiture : (made by my [agent99] private key)<br />
  L8R8mn80Gckq3aRl9JuwT/8/ubc65VS5WTazup5ToO39FtUIr9DrWrxGS8AhPBLyB5ESTxMNh/meb1p/PMHn+uoV75h1AIpSfVZNiGRCWy2yr6LvIiCF8g73ygzm5C7/fuX29CfZtQ3J5VHrHIksyOmK53vDK1a8429dM7HIWPOc05uuDawnsOJMByKacODKoBRHWKM5xP1rmiHO/8a0wPspzkQAt+YbukuLe66b7Msvvlgcjn8sJUHQuQGD5Cw/deGLGw/Mem6EWCJpea+5adzn/zmdUbmjUNttTvHM08hdHt2P+Rw+8LlGmIXeTnkmmmUP3NYbliIbyeqn+BHylQ==
  
  <br />
  
  
  ufsJoUH/YnZ198mj33rzkCV4jFXDanuPuE+96Tbo6mhLupbU1ixm+9tnHZsHP+bbFRWZ1jTUz3RtRa/TOFP5BP+GzwOcypAD40R1Ws79RHoLfJ5cXp+NXl2xaP1BXvkqkomugkzBfwAHmWKULrGQ/tve9WXHxPnUA/cIil1oh6UV1q6V1p83AMpCVzGUo2T91nP8quSZ9UWoDk1kC7IuevLexwZGTy+sbWNIJjPrGzBlWUz+GSkNgBahkRSOvRdfyBzd9ZMJ1v/RXdUMes8axpkjUQ6bP60lirwMhakbGAIfWxmzpavYRgpHUl24RzN1akRru4UReP1GYmLmrbNPXA==

7\. Agent Messages
  * [ ]  Required: Repair the dropbox code
  * [ ]  Required: Repair the messages area
  * [ ]  Required: Display encrypted messages for all agents
  * [ ]  Required: Messages indicate whether the message signature is valid
  * [ ]  Required: Your messages are automatically decrypted

8\. Identify the Double Agent
  * [ ]  Required: Decrypt as many email messages as possible
  * [ ]  Required: Identify the double agent: ____________________

The following objectives are **optional**:

* Bonus Objective 1\.
  * [ ]  Track down the bugs in the code and fix them.

* Bonus Objective 2\.
  * [ ]  Write a report of your discoveries (longer than 300 characters).
  * [ ]  Compose a secure email for sending over an insecure network.
  * [ ]  Include the email with your encrypted report in this README.

* Bonus Objective 3\.
  * [ ]  Add a "Create/Verify Checksum" section to the Encryption Tools area.

* Advanced Objective 1\.
  * [ ]  Add support for other symmetric algorithms.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## License

    Copyright [2017] [Jieun Lim]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
