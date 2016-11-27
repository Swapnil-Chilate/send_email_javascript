# send_email_javascript
Send email notifications from client side only. No smtp server required. Instead use online services e.g. emailjs, mailchimp, etc.

Steps
1. Create a free account at www.emailjs.com
2. Register a smtp service. This is the account emailjs will use to send out emails. For simplicity, I used my gmail account. 
3. Create a template
4. Boom, you are done. Replace the userid in emailjs.init() with yours and call emailjs.sendForm() 
5. Check your/receipient's inbox

