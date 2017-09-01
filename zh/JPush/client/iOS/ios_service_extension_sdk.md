# iOS Notification Service Extension SDK
使用Notification Service Extension SDK上报您的APNS消息
## 使用方法

1. 将jpush-extension-ios-xxx.a和JPushNotificationExtensionService.h两个文件引入到您的Service Extentsion工程中
2. 调用jpushSetAppkey:]方法设置您的appkey，请注意这里的appkey应该和您JPush的appkey相同
3. 调用[jpushReceiveNotificationRequest:]方法上报您的apns消息，完成送达统计；在该方法的block回调中进行apns的显示


Note：请参考demo进行集成使用

