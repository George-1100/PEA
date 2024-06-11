# Phishing Email Analysis -1
# Description
Investigate the phishing email and attachment to collect useful artifacts using Firefox thunderbird, whois and URL2PNG
# Prof of Concept
* Open the email in firfox thunderbird 
1. Who is the primary recipient of this email?
   kinnar1975@yahoo.co.uk
   
   ![PEA 1 1](https://github.com/George-1100/PEA/assets/76154087/59ea048a-8fee-483a-9423-17913e1f40f8)

2. What is the subject of this email?
   Undeliverable: Website contact form submission
   
   ![PEA 1 2](https://github.com/George-1100/PEA/assets/76154087/00e5189c-4427-4484-9455-460c9df3fef7)

3. What is the date and time the email was sent?
   
   ![PEA 1 3](https://github.com/George-1100/PEA/assets/76154087/41777947-ae4e-40af-b34d-3cf4db49cfd9)

4. What is the Originating IP?

   ![PEA 1 4](https://github.com/George-1100/PEA/assets/76154087/d5926107-c394-43d2-be19-fe506ed01be3)

   * Using Thunderbird source to identify the origiinated IP

5. Perform reverse DNS on this IP address, what is the resolved host? (whois.domaintools.com)

   ![PEA 1 5](https://github.com/George-1100/PEA/assets/76154087/3b5dbe10-2dbc-4160-8569-060196d8ab59)

6. What is the name of the attached file?

   ![PEA 1 6](https://github.com/George-1100/PEA/assets/76154087/1ac23416-9854-4a97-b989-3df491d66240)

7. What is the URL found inside the attachment?

   ![PEA 1 7](https://github.com/George-1100/PEA/assets/76154087/395cef8d-9b0f-4e1f-b3be-2916df92f37d)

8. What service is this webpage hosted on?

   ![PEA 1 8](https://github.com/George-1100/PEA/assets/76154087/cd135879-68d0-42d2-8279-1c13a671f1bb)

9. Using URL2PNG (Or open link in browser), what is the heading text on this page?

   ![PEA 1 10](https://github.com/George-1100/PEA/assets/76154087/dee85b72-3561-4e42-b4d6-9bd8e985e98e)

# Phishing Email Analysis -2

1. What is the sending email address?
   amazon@zyevantoby.cn
   
2.What is the recipient email address?
  saintington73@outlook.com
  
3. What is the subject line of the email?
   Your Account has been locked
   
4. What company is the attacker trying to imitate?
   Amazon
   
5. What is the date and time the email was sent? (As copied from a text editor)
   Wed, 14 Jul 2021 01:40:32 +0900

   ![image](https://github.com/George-1100/PEA/assets/76154087/ff557255-5acb-4b7a-b3ee-64106547e041)

7. What is the URL of the main call-to-action button?
   https://emea01.safelinks.protection.outlook.com/? 
url=https%3A%2F%2Famaozn.zzyuchengzhika.cn%2F%3Fmailtoken%3Dsaintington73%40outlook.com&data=04%7C01%7C%7C70072381ba6e49d1d12d08d94632811e%7C84df9e7fe9f640afb435aaaaaaaaaaaa%7C1%7C0%7C637618004988892053%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&sdata=oPvTW08ASiViZTLfMECsvwDvguT6ODYKPQZNK3203m0%3D&reserved=0

8. Look at the URL using URL2PNG. What is the first sentence (heading) displayed on this site? (regardless of whether you think the site is malicious or not)
   The page that you are trying to acces cannot be loaded

   ![image](https://github.com/George-1100/PEA/assets/76154087/60f965ac-5405-4444-b302-67a4fb27d868)

9 . When looking at the main body content in a text editor, what encoding scheme is being used?
   base64

  ![image](https://github.com/George-1100/PEA/assets/76154087/5b07917a-707d-4d2d-826f-4af9a19d1dae)


10. What is the URL used to retrieve the company’s logo in the email?
   https://images.squarespace-cdn.com/content/52e2b6d3e4b06446e8bf13ed/1500584238342-OX2L298XVSKF8AO6I3SV/amazon-logo?format=750w&amp;content-type=image%2Fpng

11. For some unknown reason one of the URLs contains a Facebook profile URL. What is the username (not necessarily the display name) of this account, based on the URL?
    amir.boyka.7

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Phishing Email - Letsdefend

 # Your email address has been leaked and you receive an email from Paypal in German. Try to analyze the suspicious email.

1. What is the return path of the email?

bounce@rjttznyzjjzydnillquh.designclub.uk.com

Check the "Return-Path" field. Remove the < > chars.


![image](https://github.com/George-1100/PEA/assets/76154087/81c21885-7132-4813-bd08-ff02804ecaa6)


2. What is the domain name of the url in this mail?
storage.googleapis.com

It is in the body


3. Is the domain mentioned in the previous question suspicious?
yes

4. What is the body SHA-256 of the domain?

13945ecc33afee74ac7f72e1d5bb73050894356c4bf63d02a1a53e76830567f5

In VirusTotal, scan the full domain (Question 2) and check the "Details" tab.


![image](https://github.com/George-1100/PEA/assets/76154087/57993362-7e94-43c6-a1a9-5037a24e5f2e)

5. Is this email a phishing email?
yes



 

   


