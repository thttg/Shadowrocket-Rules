# Shadowrocket个人用规则

## 黑名单 + 广告过滤

除了GFW以外，都直连。

* GitHub
  - https://raw.githubusercontent.com/thttg/Shadowrocket-Rules/refs/heads/main/gfw_only.conf
<br/>![image](https://github.com/user-attachments/assets/2cdf5aa3-fcc2-456f-b31c-8509650bff8e)

* jsDelivr (Fastly)
  - https://fastly.jsdelivr.net/gh/thttg/Shadowrocket-Rules@main/gfw_only.conf
<br/>![image](https://github.com/user-attachments/assets/c6041546-a3d1-40e6-8f39-6e65d64f364f)

* jsDelivr (Bunny)
  - https://jsdelivr.b-cdn.net/gh/thttg/Shadowrocket-Rules@main/gfw_only.conf
<br/>![image](https://github.com/user-attachments/assets/d2b55d9d-98db-43df-b15f-fb793c8c0554)


## 白名单 + 广告过滤

除了中国的域名和IP以外，都走代理。

* GitHub
  - https://raw.githubusercontent.com/thttg/Shadowrocket-Rules/refs/heads/main/non_cn.conf
<br/>![image](https://github.com/user-attachments/assets/1498cda8-05a8-491d-9587-08c0c12064b7)

* jsDelivr (Fastly)
  - https://fastly.jsdelivr.net/gh/thttg/Shadowrocket-Rules@main/non_cn.conf
<br/>![image](https://github.com/user-attachments/assets/7328af4a-5c48-481c-951d-f9833c75c557)

* jsDelivr (Bunny)
  - https://jsdelivr.b-cdn.net/gh/thttg/Shadowrocket-Rules@main/non_cn.conf
<br/>![image](https://github.com/user-attachments/assets/47b97223-2243-4a7e-a991-e77d3e532bf6)


## 仅限代理AI (ChatGPT、Claude、Gemini)

* GitHub
  - https://raw.githubusercontent.com/thttg/Shadowrocket-Rules/refs/heads/main/chatgpt.conf
<br/>![image](https://github.com/user-attachments/assets/cd0cad8e-cebd-4d12-a93e-2d93f485ec5a)

* jsDelivr (Fastly)
  - https://fastly.jsdelivr.net/gh/thttg/Shadowrocket-Rules@main/chatgpt.conf
<br/>![image](https://github.com/user-attachments/assets/b12dca40-cadc-46b6-afe6-fda571860952)

* jsDelivr (Bunny)
  - https://jsdelivr.b-cdn.net/gh/thttg/Shadowrocket-Rules@main/chatgpt.conf
<br/>![image](https://github.com/user-attachments/assets/e6863060-4e59-4a1d-bacc-baee3bf0d59d)

## GeoLite2
* Country国家数据库
  - https://fastly.jsdelivr.net/gh/Loyalsoldier/geoip@release/Country-without-asn.mmdb

* ASN数据库
  - https://fastly.jsdelivr.net/gh/Loyalsoldier/geoip@release/Country-asn.mmdb

### 本项目引用：  
[Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)
[Loyalsoldier/surge-rules](https://github.com/Loyalsoldier/surge-rules)
[blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)  
[Johnshall/Shadowrocket-ADBlock-Rules-Forever](https://github.com/Johnshall/Shadowrocket-ADBlock-Rules-Forever)  
