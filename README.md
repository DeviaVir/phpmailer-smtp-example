# PHPMailer + SMTP + DualDev Example

This small repo shows how you can send an e-mail using (DualDev's/) any mail server.

## Usage

First get the required packages:

```
composer install
```

Now simply run cli.php like this:

```
SMTP_USERNAME=email@domain.ext SMTP_PASSWORD=yourpassword SMTP_TO_ADDRESS=test@domain.ext php cli.php
```