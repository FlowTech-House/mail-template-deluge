# Introduction

This is Zoho script that defines an email template in HTML with inline styles, to send to your users or customers script also includes placeholders that are later replaced with specific values, the values in it is example of mercedes sending email to info user he won car.

for more information go to repository of template

```
https://github.com/Marconoyet/mail-template.git
```

# How it work

**1- HTML Email Template**: The mailContent variable holds a long string containing an HTML email template. The template is styled with inline CSS to ensure consistent rendering across different email clients.

**2- Placeholders**: The HTML template contains several placeholder strings like `__companySite__`, `__logoURL__`, `__altLogo__`, etc. These placeholders act as markers for specific content that needs to be dynamically replaced.

**3- Replace Function**: The script utilizes a custom `replaceAll` function (is a function in zoho deluge) to replace each occurrence of the placeholders with actual values. For example, `__companySite__` will be replaced with the URL of the Mercedes-Benz website, and so on.

**4- Email Content Customization**: After the replaceAll function is called for each placeholder, the email content becomes personalized with specific details like the recipient's name, the date, the body text of the email, a list of reasons why the recipient won, and a call-to-action button.

**5- Sending Email**: At the end of the script, there is a sendmail function that sends the personalized email to the recipient's email address.

# How to customize template

- Clone this repository to your local machine

```
git clone https://github.com/FlowTech-House/mail-template-deluge
```

- Adjust the template to design you need template.html
- go to visual studio select `"` and press `ctrl+shift+l` put \ before each double qoute to be like this `\"`
- after doing this copy the HTML template and compress it using this site

```
https://www.textfixer.com/html/compress-html-compression.php
```

- replace values using the following

```
mailContent.replaceAll(mailContent, "__placeholder__", "value");
```

- after doing this steps your email ready to be sent 🥳.

# Contact

If you have any questions or need further assistance, feel free to contact me:

- Name: Ahmed El-sharawy
- E-mail: ahmed123mah@yahoo.com
- GitHub: https://github.com/Marconoyet
- Linkedin: https://www.linkedin.com/in/marconoyet/

feel free to contribute to this repository by submitting pull requests or suggesting improvements. Happy mailing! 📧
