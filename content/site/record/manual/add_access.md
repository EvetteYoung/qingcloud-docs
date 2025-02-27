---
title: "新增接入"
description: test
weight: 5
---



新增接入，也称接入备案，指主体和域名已在其他接入商备案过，现需将顶级域名或其子域名解析在青云，应申请新增接入备案，即变更或增加接入商。

说明：

- 新增接入不会影响您在其他接入商的网站备案信息，一个网站可备案在多家接入商。
- 接入备案期间，如原备案的IP资源有效可继续解析访问，不会影响原业务的正常使用。接入备案成功后，即可解析到青云对应IP。
- 接入备案是完整接入该网站原备案的所有域名，如个别域名已过期，需续费或先注销后才能申请接入。
- 同网站的接入备案与变更备案不能同步进行。如网站备案信息有更新，在当地管局允许时，可先接入后变更，否则需在原接入商处变更成功后再在新接入商申请接入。

#### 前提条件

- 请先确定主体证件号、网站备案号、青云公网 IP、域名。

- 准备好备案主体证件材料（原件拍照/扫描）彩色电子版（电子版证件资料要求）。

  - 企业：营业执照、法定代表人/网站负责身份证、域名证书（视管局要求，域名证书请联系域名服务商提供）。
  - 个人：身份证或护照
  
- 其他表格类备案材料，可在青云备案系统对应项下查看样例、下载模板。


#### 操作步骤

1. 登录 QingCloud 管理控制台。

2. 点击右上角的**备案**，进入 ICP 备案管理系统。

   ![](../../_images/icp_management.png)

3. 在左侧导航栏中点击**备案信息**，显示备案列表页面。

4. 点击需要变更的主体备案号，显示备案主体信息和网站信息。

5. 点击**新增接入网站**，进入备案申请填写页面。

6. 填写接入备案信息。

   - 网站名称：个人网站、企业网站名称的具体要求，请参见[网站名称命名规则](../../intro/limit/)。

   - IP 地址：备案服务器的公网IP地址。点击**选择IP**，选择已创建的云服务IP。

   - 网站服务内容：网站内容必须与主办单位性质相符。

   - 应用服务类型：各服务类型参数说明如下表所示。

| 参数           | 说明                                                 |
| -------------- | ------------------------------------------- |
| 网站应用服务   | 通常指官网类或电商网站选择网站应用服务等。        |
| 邮件应用服务   | 通常指电子邮件服务，搭建邮箱等。                    |
| 文件应用服务   | 通常指存文件数据，支持多种上传文件格式，如服务器内存储图片、代码、音乐，一般用作调用接口使用等。 |
| 数据应用服务   | 通常指存储某种格式编程代码文件数据，一般用作调用接口使用等。|
| APP应用服务    | 通常指手机、平台电脑上的APP等。             |
| 微信号应用服务 | 通常指微信订阅号、公众号、服务号等。          |

   - 网站语言：指网站内容使用的主要语言。请根据实际情况进行选择，不建议多选。

     示例：网站内容的主要语言为中文，部分插件为英文，此时“网站语言”选择“中文”。

- 前置审批类型：网站若包含[前置审批内容类型](../../prepare/pre_approval/)中的项目，请上传相关许可证件或咨询备案所在省主管部门。

- 网站负责人信息：

  如果网站负责人和主体负责人是同一个人，可在下拉列表中选择。否则，点击**新增网站负责人**，并填写网站负责人信息，此时网站负责人和主体负责人的电话、邮箱不能相同。

  > 说明：  
  > 如需添加多个网站，当一个网站信息填写完后，点击**继续添加网站**。

4. 提交初审。

   青云会在1-2个工作日内对用户提交的备案信息进行初审，初审通过后，用户可上传资料图片（域名证书、授权书、承诺书，前置审批证书等），并扫描二维码进行真实性核验。

5. 提交复审。

   青云会在1-2个工作日内对用户提交的备案信息及资料进行复审，复审通过后提交至管局。

6. [短信核验](../filing_sm_check/)。

   青云将备案申请提交至管局后，用户会收到工信部下发的[短信核验](../filing_sm_check/)，用户需要在24小时内完成全部短信核验，短信核验完成后该备案申请才能进入管局系统等待最终审核。

7. 管局审核。

   各省管局审核时间不一致，一般管局审核时间为1-20个工作日。

8. 备案通过。

   备案通过后，用户需要按照工信部要求建设网站，并且在网站首页下方中央放置对应的网站备案号，备案号需要添加超链接至[工信部官网](https://beian.miit.gov.cn/) ；江苏省用户需要注意网页下方还需添加版权所有，版权所有单位要与备案主办单位名称保持一致。

#### 后续处理


> 提示：  
> 1. 工信部备案成功后，网站开通之日起30日内，用户需自行登录[全国互联网安全管理服务平台](http://www.beian.gov.cn/portal/index.do)。在下载中心下载《互联网站安全服务平台操作指南》和《安全评估使用手册》，了解公安备案操作流程，进行公安备案及网站安全评估。详细信息可参见[公安备案](../../filing/public_filing/)。  
> 2. 如果用户网站涉及经营性互联网信息服务，需自行申办经营性 ICP 许可证。详细信息可参见[经营性备案](../../filing/operational_filing/)。  
> 3. 备案成功后，请保持负责人联系电话畅通，以便接收备案相关的通知与提醒，若备案相关信息发生变化，请及时联系青云变更备案信息，避免因未及时收到通知信息而影响网站正常使用。变更备案可参考变更备案流程。

- 对于新增接入备案的用户，备案通过青云初审后就可以解析访问。如何配置网站解析，请参见[配置域名解析记录](/network/dns/quickstart/creatrecordset/)。

- 如需取消在原接入商处的网站备案信息，请务必先在青云完成新增接入备案，成功后再申请取消。取消后不会影响网站的正常使用。

  如果未成功新增接入就取消在原接入商的备案信息，取消之后可能会变成空壳网站而被通信管理局注销备案，影响业务。