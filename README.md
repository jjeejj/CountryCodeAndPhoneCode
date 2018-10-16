# CountryCodeAndPhoneCode
国家或地区 区号对应的电话区号

|英文名称|中文名称|国家区域Code|电话区号|
|:---:|:----:|:------:|:------:|
|english_name|chinese_name|country_code|phone_code|

### 腾讯国际短信 支持的 地区和对应的电话区号

加上 `中国` 一个支持  **217** 个国家或地区 [Tencnet SMS CountryCodeAndPhoneCode](./tencentSms/countryCodeAndPhoneCode.json)

> 数据文件 是以 **country_code** 字段进行排序的

### 阿里国际短信 支持的 地区和对应的电话区号

加上 `中国` 一个支持  **216** 个国家或地区 [Ali SMS CountryCodeAndPhoneCode](./aliSms/countryCodeAndPhoneCode.json)

> 数据文件 是以 **english_name** 字段进行排序的

### 全部的 地区和对应的电话区号

一共有 **233** 个国家或地区 [All CountryCodeAndPhoneCode](./all/countryCodeAndPhoneCode.json)

> 数据文件 是以 **english_name** 字段进行排序的 , 若认为数据不全，可以提 ISSUE 或者 PR 

> 有的地区有两个 电话区号 ,会以这样的格式书写 ： `"phone_code":"0061 9164"`
