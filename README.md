# EmailDjangoconfig
Email SMTP(Simple Mail Transfer Protocol) Django configuration Files for the settings.py file

As Follows:
EMAIL_BACKEND= 'django.core.mail.backends.smtp.EmailBackend'
EMAIL_HOST = 'smtp.gmail.com' # or any other mail service that one wishes to use for their web application
EMAIL_POST= '587' # for TLS
EMAIL_USE_TLS= True
EMAIL_HOST_USE = 'myemailaddress@gmail.com' # email address that is to be the host emailing address
EMAIL_HOST_PASSWORD= 'app password' # uniquely generated by the mail service for development purposes
