# Shadowrocket个人用规则

## 黑名单

除了GFW以外，都直连。

* GitHub
  - https://raw.githubusercontent.com/thttg/Shadowrocket-Rules/refs/heads/main/gfw_only.conf
<br/>![image](https://github.com/user-attachments/assets/40bd92cc-73ab-47c0-8ee7-b3691b0c36b4)

* jsDelivr (Fastly)	***[fastly / originfastly / quantil]***
  - https://fastly.jsdelivr.net/gh/thttg/Shadowrocket-Rules@main/gfw_only.conf
<br/>![image](https://github.com/user-attachments/assets/201b70b9-ee91-4a9e-ae23-83c95f74aabb)

* jsDelivr (Cloudflare)	***[testingcf / gcore]***
  - https://testingcf.jsdelivr.net/gh/thttg/Shadowrocket-Rules@main/gfw_only.conf
<br/>![image](https://github.com/user-attachments/assets/c26eb692-c129-4477-8507-765470a9b724)

* jsDelivr (Bunny)
  - https://jsdelivr.b-cdn.net/gh/thttg/Shadowrocket-Rules@main/gfw_only.conf
<br/>![image](https://github.com/user-attachments/assets/a60e2922-9fbc-41b5-9022-6f5817465e54)


## 白名单

除了中国的域名和IP以外，都走代理。

* GitHub
  - https://raw.githubusercontent.com/thttg/Shadowrocket-Rules/refs/heads/main/non_cn.conf
<br/>![image](https://github.com/user-attachments/assets/d3aadd8b-9c83-4d3e-9f18-8d6257698dcf)

* jsDelivr (Fastly)	***[fastly / originfastly / quantil]***
  - https://fastly.jsdelivr.net/gh/thttg/Shadowrocket-Rules@main/non_cn.conf
<br/>![image](https://github.com/user-attachments/assets/7ba6e6b9-f607-4ae8-8227-466ea1c950b6)

* jsDelivr (Cloudflare)	***[testingcf / gcore]***
  - https://testingcf.jsdelivr.net/gh/thttg/Shadowrocket-Rules@main/non_cn.conf
<br/>![image](https://github.com/user-attachments/assets/bef14489-7f16-4874-9729-8fe6192882c0)

* jsDelivr (Bunny)
  - https://jsdelivr.b-cdn.net/gh/thttg/Shadowrocket-Rules@main/non_cn.conf
<br/>![image](https://github.com/user-attachments/assets/dd56ca17-34df-444b-9626-457351652eae)


## 仅限代理AI (ChatGPT、Claude、Gemini、grok/x.ai)

* GitHub
  - https://raw.githubusercontent.com/thttg/Shadowrocket-Rules/refs/heads/main/chatgpt.conf
<br/>![image](https://github.com/user-attachments/assets/12ce7393-4c76-4507-ab32-0010695cdd6c)

* jsDelivr (Fastly)	***[fastly / originfastly / quantil]***
  - https://fastly.jsdelivr.net/gh/thttg/Shadowrocket-Rules@main/chatgpt.conf
<br/>![image](https://github.com/user-attachments/assets/f1e36867-3398-4060-8a19-e91c9a63bc23)

* jsDelivr (Cloudflare)	***[testingcf / gcore]***
  - https://testingcf.jsdelivr.net/gh/thttg/Shadowrocket-Rules@main/chatgpt.conf
<br/>![image](https://github.com/user-attachments/assets/128272f6-ab3f-4d77-b0f5-38c3cd2ff516)

* jsDelivr (Bunny)
  - https://jsdelivr.b-cdn.net/gh/thttg/Shadowrocket-Rules@main/chatgpt.conf
<br/>![image](https://github.com/user-attachments/assets/fb177f1d-fc3e-4851-9722-bb8982e681bd)

## GeoLite2
* Country国家数据库 (Fastly)
  - https://fastly.jsdelivr.net/gh/Loyalsoldier/geoip@release/Country-without-asn.mmdb
* Country国家数据库 (Cloudflare)
  - https://testingcf.jsdelivr.net/gh/Loyalsoldier/geoip@release/Country-without-asn.mmdb

* ASN数据库 (Fastly)
  - https://fastly.jsdelivr.net/gh/Loyalsoldier/geoip@release/Country-asn.mmdb
* ASN数据库 (Cloudflare)
  - https://testingcf.jsdelivr.net/gh/Loyalsoldier/geoip@release/Country-asn.mmdb
  - 
### 本项目引用：  
[Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)
[Loyalsoldier/surge-rules](https://github.com/Loyalsoldier/surge-rules)
[blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)  
[Johnshall/Shadowrocket-ADBlock-Rules-Forever](https://github.com/Johnshall/Shadowrocket-ADBlock-Rules-Forever)  
