@EnableOAuth2Client 例子
https://stackoverflow.com/questions/29696671/how-to-overwrite-spring-cloud-oauth2-client-autoconfiguration
https://stackoverflow.com/questions/27864295/how-to-use-oauth2resttemplate
https://www.cnblogs.com/softidea/p/7045809.html
https://www.liangzl.com/get-article-detail-28562.html

@EnableOauth2sso 例子
https://www.jianshu.com/p/2d344075d395
https://www.cnblogs.com/cjsblog/p/9296361.html
https://blog.csdn.net/qq_28379809/article/details/102734384
client.autoApprove(true)则不需要用户手工授权，或者client.autoApprove(等于client的scope)也不需要用户手工手授权。


@EnableOauth2sso和@EnableOAuth2Client的区别，理解为@EnableOauth2sso是@EnableOAuth2Client自动配置。@EnableOAuth2Client为手动定义的oauth客户端，
而@EnableOauth2sso会自动生成@EnableOAuth2Client相关的bean。
