# 创建单个设备

产品完成创建后，需要进行设备创建。创建设备有单个创建和批量创建2种方式。本文为您介绍的是单个设备的创建方式。

**操作步骤**

1. 登入[物联网引擎控制台](https://iot-console.jdcloud.com/core/)
2. 选择左侧导航栏中 **管理** -> **设备**
3. 点击页面上方的 **添加设备**
4. 在添加设备的对话框中，输入设备的相关信息，点击 **确认** 

![CreateSingleDevice](../../../../../image/IoT/IoT-Engine/CreateSingleDevice.png)

**页面参数设置如下：**

| 参数                  | 描述                 |
| :-------------------: | :------------------- |
|选择产品  | 选择已创建的产品。新创建的设备将继承该产品定义好的功能和特性。如果没有创建产品，点击 **创建新产品** |
|设备名称  | 设备的名称，用来为设备命名，支持英文字母、数字、下划线“_”及中划线“-”，必须英文字母及数字开头结尾，3-30个字符。必填！产品下唯一。不可修改。 | 
|设备厂家  | 设备厂家名称，用来填写设备的厂家信息，支持汉字、英文字母、数字、下划线“_”及中划线“-”，必须以汉字、英文字母及数字开头结尾，0-30个字符。非必填！ | 
|设备型号  | 设备的型号，用来填写设备的型号信息，支持汉字、英文字母、数字、下划线“_”及中划线“-”，必须以汉字、英文字母及数字开头结尾，0-30个字符。非必填！ | 
|设备描述  | 设备的描述，用来描述设备信息。无输入字符类型限制，长度限制为0-80个字符。非必填！| 

**设备证书信息：**

设备创建成功后，将自动弹出查看设备证书弹框。您可以查看、复制设备证书信息。设备证书由设备 productKey、identifier、和 secret组成，是设备与物联网引擎进行通信的重要身份认证，建议您妥善保管。

| 参数                  | 描述                 |
| :-------------------: | :------------------- |
|productKey  | 设备所对应产品的Key，产品的全局唯一标识符。 | 
|identifier  | 设备在产品内的唯一标识符。identifier与设备所属产品的productKey组合，作为设备标识，用来进行设备连接认证和通信。 | 
|secret  | 设备的秘钥，用于认证加密。需与identifier成对使用。 | 


之后，您也可以在设备列表中，单击 设备名称，进入设备详情页查看设备信息。