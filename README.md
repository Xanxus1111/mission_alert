# mission_alert
Remind that the task on the server has been completed

```
pip install mission_alert
```

```
import mission_alert
mission_alert.sendEmail(smtp_host = ,smtp_user  = ,smtp_pwd = ,smtp_port = ,subject = ,body = )
```


需要从邮箱服务商设置里面申请smtp服务密码。
Need to apply for smtp service password from email service provider

smtp_host: 
发送邮件的smtp服务器  
Smtp server sending mail

smtp_user: 
用于登录smtp服务器的用户名，也就是发送者的邮箱 
The user name used to log in to the smtp server, that is, the sender's mailbox

smtp_pwd: 
授权码，和用户名user一起，用于登录smtp， 非邮箱密码 
Authorization code, together with the user name user, used to log in to smtp, non-mailbox password

smtp_port: 
smtp服务器SSL端口号 
Smtp server SSL port number

subject: 
邮件标题 
mail title

body: 
邮件内容 
content of email






