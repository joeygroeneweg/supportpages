# SSL certificates

Recently we've introduced SSL certificates in PowerPanel. We understand this process is new, and can be confusing. That's why we made a short tutorial explaining the order and validation process. 



When you click on the SSL certificates tab in PowerPanel, you'll be brought to the SSL dashboard. Here you can see the number of active and pending SSL certificates, as well as a pie-graph which shows the different types of certificates in your portfolio. 




We've also included several SSL tools, you can check the security of a website, or decode a CSR key. 




And lastly, you can order a new SSL certificate. You can do this from the SSL tab, or directly from the website.




During the first step of the order process, you have three options. If you've already generated a CSR on your own server, you can choose to use this CSR to request an SSL certificate, or you can choose to generate a new CSR through PowerPanel. 

We recommend to request an SSL for a domain that already exists within PowerPanel, and has a server attached to it. In this case PowerPanel will not only order, but also validate and install the SSL certificate completely automatically. This includes renewals. 

Order once, and never worry about your site-security again!




During the second step you choose the domain you want a certificate for. 




During the third step, you choose the type of certificate you'd like. 




After choosing the certificate that you'd like to order, you'll see a pop-up menu in which you have to agree to the charges. 




After the certificate is requested, you will be forwarded to the SSL detail screen in which you can see the status of the certificate itself, and if applicable, of the current request. 




During the request, it is important to set the validation method. You can choose the validation method in the SSL detail screen. 




You have a three options to validate the certificate, DNS, email validation and HTTP validation




DNS validation is done by adding a specific CNAME to a specific subdomain. The CA will check if this CNAME exists, and validate the certificate accordingly. 

Email validation is done by sending a validation email to the email of the domain owner, admin contact, or the technical contact of the domain. The CA also allows the selection of domain related email addresses. These are the standard domain aliases, such as admin, administrator, hostmaster and postmaster@domainname.com. The email needs to be confirmed, after which the CA will validate the certificate. 

HTTP validation is done by placing file with a specific name and content on a specific path on the website. The CA will check for this file and validate the certificate. 


Once the validation has been completed, you will find all necessary files to install the certificate  in the SSL detail page. If PowerPanel has access to the domain and server, you will not need these files, PowerPanel will install the certificate for you. 




After installation, you can always check the status, or manually renew the certificate from the SSL panel. 

















 
