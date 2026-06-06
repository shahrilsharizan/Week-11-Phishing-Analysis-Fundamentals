# Week-11-Phishing-Analysis-Fundamentals


## 1. The Email Address
<img width="920" height="818" alt="image" src="https://github.com/user-attachments/assets/66c5fa12-c24f-4c3f-9d43-a44347e6a0f0" />

- Answer: tryhatme.com

<img width="470" height="209" alt="image" src="https://github.com/user-attachments/assets/82ed5cab-88c7-41c5-8b58-db4cd0a32bdd" />


## 2. Email Delivery
<img width="540" height="507" alt="image" src="https://github.com/user-attachments/assets/2035d470-8b65-41c6-a8ab-01d881f0f0ac" />

### Which protocol is responsible for sending an email from a client to a mail server?
- Answer: SMTP

<img width="526" height="194" alt="image" src="https://github.com/user-attachments/assets/bb59ab2b-f0d8-4c04-a45d-5cc1d9c69cc4" />

### Which Service is used to look up the recipient domain's mail server?
- Answer: DNS

<img width="436" height="139" alt="image" src="https://github.com/user-attachments/assets/9a96e371-c203-4fd5-a49e-35a676b99500" />

### Bob wants to access his email from multiple devices, including his phone and laptop. Which protocol should he use?
- Answer: IMAP

<img width="542" height="163" alt="image" src="https://github.com/user-attachments/assets/a1ebee79-1b77-4645-afd0-2110a1666875" />


## 3. Email Headers
<img width="471" height="187" alt="image" src="https://github.com/user-attachments/assets/39b61fe8-e60f-4234-84a5-39ab3c748e3e" />

- Open `email1.eml`

<img width="545" height="216" alt="image" src="https://github.com/user-attachments/assets/6f71e703-6631-4393-a267-b679d30e1492" />

- Answer: Help protect your budget by protecting your home

<img width="450" height="171" alt="image" src="https://github.com/user-attachments/assets/ed15f96a-683d-4175-b7d6-6fec465eb331" />
<br>
<br>
<img width="547" height="169" alt="image" src="https://github.com/user-attachments/assets/04d4b22f-3fcb-45ca-8871-9578434c8338" />

- View message source of `email1.eml`

<img width="447" height="113" alt="image" src="https://github.com/user-attachments/assets/e0a24008-4a22-4752-bbf1-acee8cb142f4" />

- Answer: 43.255.56.161

<img width="459" height="171" alt="image" src="https://github.com/user-attachments/assets/b68bc5d4-cdcc-403a-a86c-66d11eb2b518" />


## 4. Email Body
<img width="498" height="214" alt="image" src="https://github.com/user-attachments/assets/bf1c5561-47b4-4855-9f60-7cbc41de8e42" />

- View `email2.txt`

<img width="449" height="122" alt="image" src="https://github.com/user-attachments/assets/8b7d1842-1672-4bca-9cba-b16db60a9fbd" />

- Answer: application/pdf

<img width="433" height="199" alt="image" src="https://github.com/user-attachments/assets/76df9bec-47b8-4a14-85b7-4c3cc6467a10" />
<br>
<br>
<img width="433" height="141" alt="image" src="https://github.com/user-attachments/assets/b533d330-b629-460d-a34c-b9295a10d419" />
<br>
<br>
<img width="175" height="21" alt="image" src="https://github.com/user-attachments/assets/71436c52-16ec-4cce-8abc-7e82c6222076" />

- Answer: zmqpalgh.pdf

<img width="420" height="146" alt="image" src="https://github.com/user-attachments/assets/13022b4b-974f-4727-b824-8b5b3de384b5" />
<br>
<br>
<img width="686" height="164" alt="image" src="https://github.com/user-attachments/assets/7b7f0f12-41cc-4383-8944-fd836a50f5da" />

- Copy the base64 string in `email2.txt`
- Used https://www.apivoid.com/tools/base64-to-pdf/

<img width="1123" height="715" alt="image" src="https://github.com/user-attachments/assets/c5fed479-0669-423f-8393-259f820e0421" />

- Answer: THM{BENIGN_PDF_ATTACHMENT}

<img width="652" height="166" alt="image" src="https://github.com/user-attachments/assets/3173f5a5-dd1e-4d8c-b048-b54ce7f8dc0c" />


## 5. Types of Phishing
<img width="580" height="189" alt="image" src="https://github.com/user-attachments/assets/323bf1c4-43ce-421e-91d1-1a5c716cfce9" />

- Open `email3.eml`
<img width="761" height="347" alt="image" src="https://github.com/user-attachments/assets/b015614c-2713-4b69-bfa2-338239df249e" />

- Answer: Home Depot

<img width="471" height="136" alt="image" src="https://github.com/user-attachments/assets/88603176-2aa0-49d4-8f19-eecc89db3082" />
<br>
<br>
<img width="289" height="133" alt="image" src="https://github.com/user-attachments/assets/d1b38010-36f7-4186-81b6-8e147302fd28" />

- Answer: support@teckbe.com

<img width="398" height="141" alt="image" src="https://github.com/user-attachments/assets/0ee7e1fb-6a8d-4517-9654-069a219eb341" />
<br>
<br>
<img width="429" height="164" alt="image" src="https://github.com/user-attachments/assets/86ea48ec-d030-4ba8-9f27-62a32672bfb7" />
<br>
<br>
<img width="561" height="113" alt="image" src="https://github.com/user-attachments/assets/44a03ec0-6d3a-40e1-8dd8-cab8b6b10b87" />

- `X-Originating-IP` is 103.234.236.83
- Go to CyberChef to defang

<img width="967" height="631" alt="image" src="https://github.com/user-attachments/assets/b62b7d16-0887-4cdf-872a-4a17aa25ca61" />

- Answer: 103[.]234[.]236[.]83

<img width="425" height="167" alt="image" src="https://github.com/user-attachments/assets/88a7177f-a67d-4fb0-978f-10bfb77de32b" />
<br>
<br>
<img width="510" height="165" alt="image" src="https://github.com/user-attachments/assets/9b054884-2f6d-4491-81f1-130359d6eb21" />
<br>
<img width="378" height="23" alt="image" src="https://github.com/user-attachments/assets/5ac669a0-1423-4d11-bace-fc969e35f9ec" />

- Answer: atlas102@free.mail.gql.yahoo.com

<img width="451" height="171" alt="image" src="https://github.com/user-attachments/assets/18a0db3b-7bc1-43d8-a61c-21aaf2634c6c" />


## 6. Conclusion 
<img width="642" height="209" alt="image" src="https://github.com/user-attachments/assets/69f4b926-5c6a-4bd2-8ffd-6358d3637f2a" />
<br>
<br>
<img width="879" height="65" alt="image" src="https://github.com/user-attachments/assets/e911ab54-f642-4b0c-b99d-659a9df42b70" />

- Answer: Business Email Compromise

<img width="710" height="182" alt="image" src="https://github.com/user-attachments/assets/a352e18f-cb9a-4a26-9926-859688b13fb0" />


## Finish 
<img width="1012" height="563" alt="image" src="https://github.com/user-attachments/assets/1929d732-c6d4-41ad-b687-8c5a3fd2c4a2" />
