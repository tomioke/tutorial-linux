1. install and initialize the mail server

 Open Appstore, search mail server
![mail server](https://user-images.githubusercontent.com/40717020/184825433-bf276fd1-a940-45b2-b709-de950150b0e6.png)

2. Resolve your A record at the DNS service provider

For example, my email domain is youtubad.com, I want to use mail.youtubad.com as the A record

Log in to your dns provider console, I am using CloudFlare

Add the following records, note that your mail server A record cannot use proxy
![5f2a7d27cde41](https://user-images.githubusercontent.com/40717020/184826345-546b83eb-cc6a-4734-a7be-4741938f9734.png)
![5f2a7ce5f17dc](https://user-images.githubusercontent.com/40717020/184826524-a932d9c8-a135-4749-a193-f870f0022872.png)

3. Add the domain name and A record you just set to the mail server
![mail](https://user-images.githubusercontent.com/40717020/184826761-d8895a00-fae3-47ec-9cce-e541c03d4976.png)

4. Follow the prompts to add related records
![mx_record](https://user-images.githubusercontent.com/40717020/184827166-5d1e47ee-3b64-4f74-ab55-a70a6accb719.png)

5. Add MX record
![mx_record1](https://user-images.githubusercontent.com/40717020/184827437-c8a39cca-9fda-4fe4-8866-c16e8316d1e3.png)

6. Add the remaining TXT records (used to prevent mail from being sent to the spam mailbox)
![mailserver1](https://user-images.githubusercontent.com/40717020/184827852-af754239-a1d3-43bd-82b9-8f0cced3e520.png)
![mailserver2](https://user-images.githubusercontent.com/40717020/184827875-8d568afd-c2c4-45e8-b818-66d119fc049c.png)
![mailserver3](https://user-images.githubusercontent.com/40717020/184827907-ba4a8c61-5809-4f3b-9f46-a435fdaf1ae7.png)
![mailserver4](https://user-images.githubusercontent.com/40717020/184827931-057a04cf-263b-44cc-bd0e-857793136186.png)
![save_change](https://user-images.githubusercontent.com/40717020/184828001-db34f9e2-376e-424d-a0b2-d0505840ef0c.png)

After all records turn into green tick, you can send email.

7. Set up an SSL certificate for the domain name

After setting the certificate for the domain name, you can send emails through the encrypted port connection

Set up your A record domain name to apply for a certificate

Create a website use your domain name
![ssl1](https://user-images.githubusercontent.com/40717020/184828797-3d417848-de1b-4dc2-b455-963823e3f9a8.png)

8. Apply for a pan-domain name certificate for the domain name
![ssl2](https://user-images.githubusercontent.com/40717020/184828829-e57d9d3a-b432-48aa-bfc6-52683f56202c.png)

9. Copy the applied certificate to the domain name of the mail server
![ssl3](https://user-images.githubusercontent.com/40717020/184828854-5e0a35b2-e8a6-48de-a8c9-f7278a46b9b2.png)
