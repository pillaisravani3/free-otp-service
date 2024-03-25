# free-otp-service
# free-watsapp-campaign

Free OTP service so that you don't have to burn cash on OTP delivery and save huge money by sending the one time password (OTP) on watsapp and phone giving good experience to users and saving huge expenditure on supporting sms delivery of the one time password and without worrying about low balances.

Free campaign for watsapp aims to provide you a lifetime free service to send product ads , do marketing or political campaign using your favorite language and for local and national level without limit on words count.

## Contents
- [Signup](#signup)
- [Free OTP](#free-otp)
- [Add Device](#add-device)
- [Token](#token)
- [Sample Code](#sample-code)



### Signup

Goto DBuddyZ.com and signup for an account using the number you want to send the message from , this could be your personal number or a dedicated number for OTP delivery , one time password will be received on your watsapp , enter it and signup or login.

### Free OTP

After signup you will get a Token and Sample codes to send OTP to your users.

### Add Device

To use Bulk Messaging , Customised Message , Translated Message etc.. you need to add your Device from Dashboard. A QR code code will be generated which needs to be scanned on your phone where you have the watsapp to link it for sending messages.

### Token 

After adding the device you will get a token which will be used to send any kind of messages , one time password , bulk messages , ads , campaigns etc..

### Sample Code

Sample curl request to send an otp 

**For OTP**

```shell
  curl --location 'https://dbuddyz.com/send/' \
  --form 'token="[TOKEN]"' \
  --form 'otp="[OTP]"' \
  --form 'tonumber="+9190XXXXXXXX"'
```

**For Campaign**

```shell
  curl --location 'https://dbuddyz.com/send/' \
  --form 'token="[TOKEN]"' \
  --form 'body="My Campaign Message"' \
  --form 'fullmessage="1"' \
  --form 'tonumber="+9190XXXXXXXX"'
```

| Variable                                      | Description                                                                                                                                                           |
| -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [TOKEN] | Token displayed on your Dashboard under My Token  |
| [OTP]                          | The OTP to be sent using default Template by replacing [OTPNUMBER] string present at [dbuddyz.com/profile](https://dbuddyz.com/profile/) and prepending the App Name at [dbuddyz.com/profile](https://dbuddyz.com/profile/) page , if present.

**P.S - To send campaign messages you need to connect a watsapp number from your end which will be used to send the messages**

## Features

- **Free Political Campaign**
- **Free Bulk Messaging**
- **Free OTP verification**
- **Free Developer OTP API**
- **Free One Time Code Delivery**
- **Free One Time Code API**
- **Free Watsapp Campaigning**
- **Free Watsapp Messaging Online**
- **Free OTP Service**
- **Free OTP Online**
- **Free SMS to anywhere in the world on watsapp**
- **Use my number to send watsapp**
- **No cost OTP service**
- **Nodejs OTP**
- **Java OTP**
- **Curl OTP**
- **PHP OTP service**
- **Wordpress OTP plugin service**
- **Spam Checking**
- **Free International Message Sending**
- **Send Free Message to USA**
- **Send Free Message to Middle East**
- **Send Free Message to India**
- **Send Free Message to Africa**
- **Send Free Message to Europe**
- **Send Free Message to Australia**


**First of its kind service free sms and otp delivery and watsapp campaigning**


