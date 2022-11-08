# OSI 模型與TCP/IP protocal suite

## OSI有七層?簡述其功能
實體層:定義網路裝置之間的位元資料傳輸
資料連結層:在網路之間建立邏輯連結
網路層:通訊協定是網際網路協定
傳輸層:負責電腦整體的資料傳輸及控制
會議層:負責建立網路連線
展示層:應用層收到資料後透過展示層可轉換表達方式
應用層:處理應用程式進而提供使用者網路應用服務
## 底下網路設備在哪一級？集線器、交換機、路由器、L4 交換機、代理
hub:實體層
switch:資料連結層
router: 網路層
L4-switch:
proxy:
## TCP/IP有那些層？寫出與OSI七層模型的對應！
應用層:實體層,應用層,會議層
傳輸層:傳輸層
網路層:網路層
網路存取層:展示層,資料連結層
## 簡述底下應用層協定(英文全名與簡單功能說明):
- HTTP vs HTTPs
  - HTTP
    - HyperText Transfer Protocol 超文本傳輸協定
    - HTTP是一種用於分佈式、協作式和超媒體訊息系統的應用層協定
    - HTTP是全球資訊網的數據通信的基礎。
  - HTTPS
    - 超文本傳輸安全協定（HyperText Transfer Protocol Secure，HTTPS；
    - 常稱為HTTP over TLS、HTTP over SSL或HTTP Secure
    - HTTPS是一種透過計算機網路進行安全通訊的傳輸協定。
    - HTTPS經由HTTP進行通訊，但利用SSL/TLS來加密封包。
    - HTTPS開發的主要目的，是提供對網站伺服器的身分認證，保護交換資料的隱私與完整性。
     
- DNS vs DNSsec
- DNS
  - Domain Name System 網域名稱系統
  - DNS是網際網路的一項服務
- DNSsec
  - 域名系統安全擴充（Domain Name System Security Extensions
  - 
- telnet vs ssh
- ftp vs sftp
- smtp, pop3
- SNMP

## 簡述底下傳輸層協定(英文全名與簡單功能說明):TCP vs UDP
- TCP
  - reliable(可靠的) vs unreliable(不可靠的)
  - TCP three-way handshaking(三項交握)  
  - TCP syn flood attack

## 簡述底下網路層協定(英文全名與簡單功能說明): IP   ICMP
- IP
- ICMP
