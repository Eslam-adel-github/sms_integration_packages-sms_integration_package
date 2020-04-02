# sms_integration_packages-sms_integration_package

#installtion

`composer require sms_integration_packages\sms_integration_package `

#add in providers array in service provider this code

` Sms\Integration\Package\SmsProvider::class, `

#and add to aliase

` "SendSmsIntegration"=>Sms\Integration\Package\SendSms::class `
