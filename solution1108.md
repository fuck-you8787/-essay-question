## OSI有七層?簡述其功能
   # Physical Layer
     -Physical Layer在區域網路上傳送ˋ資料框ˋ。
     -Physical Layer負責管理ˋ電腦通訊裝置ˋ和ˋ網路媒體ˋ之間的ˋ互通ˋ。
   # Data Link  Layer
     -Data Link Layer負責ˋ網路尋址ˋ、ˋ錯誤偵測ˋ和ˋ改錯ˋ。
   # Network Layer     
     -Network Layer決定數據的ˋ路徑選擇ˋ和ˋ轉寄ˋ。
   # Transport Layer
     -Transport Layer把ˋ傳輸表頭（TH）ˋ加至ˋ資料ˋ形成ˋ封包ˋ。
   # Session Layer
     -Session Layer負責在數據傳輸中ˋ設定ˋ和ˋ維護ˋ兩台電腦之間的ˋ通訊連接ˋ。
   # Presentation Layer
     -Presentation Layer把ˋ數據轉換為ˋ能與接收者的系統格式ˋ相容並適合ˋ傳輸ˋ的格式ˋ。
   # Application Layer
     -Application Layerˋ提供ˋ為應用軟體而設計的ˋ介面ˋ。
## 底下網路設備運作在哪一層? Hub, switch,router, L4-switch, proxy
   # Hub
     -Physical Layer
   # switch
     -Data Link  Layer
   # router
     -Network Layer
   # L4-switch
     -Transport Layer
   # proxy
     -Application Layer
## TCP/IP有那些層?寫出與OSI七層模型的對應!
   **由最底層往上排序
   1. Link(Physical Layer、Data Link Layer) 
   2. Internet
   3. Transport
   4. Application(Seesion、Presentation、Application)
   
  Another version of TCP/IP
   1. Physical Layer
   2. Data Link Layer
   3. Internet
   4. Transport
   5. Application(Seesion、Presentation、Application)
## 簡述底下應用層協定(英文全名與簡單功能說明):
   # HTTP
     -HyperText Transfer Protocol 超文本傳輸協定
     -一種用於分佈式、協作式和超媒體訊息系統。
     -是全球資訊網的數據通信的基礎。
     -最初目的是為了提供一種發布和接收HTML頁面的方法。
     -透過HTTP或者HTTPS請求的資源由URI標識。
   # HTTPS
     -Hypertext Transfer Protocol Secure安全超文本傳輸協議。
     -是HTTP的擴展。
     -用於計算機網絡上的ˋ安全通信ˋ。
     -目的是提供對網站伺服器的身份認證，保護交換資料的隱私與完整性。
     -在Internet上，被廣泛使用。
   # DNS 
     -Domain Name System 域名系統。
     -將域名和IP位址相互對映的分散式資料庫。
     -使用TCP和UDP埠53。
     -域名長度的限制是63個字元。
     -域名總長度則不能超過253個字元。
   # DNSsec
     -Domain Name System Security Extensions域名系统安全擴展。
     -對DNS資料來源進行認證。
     -不提供機密性和可用性。
     -驗證不存在性和校驗資料完整性。
     -保護應用程式免受不當操縱的DNS數據所造成的影響。
   # Telnet 
     -Telnet 遠程登入協定。
     -使用於ˋ網際網路ˋ及ˋ區域網ˋ中。
     -提供ˋ雙向ˋ且以ˋ文字字串ˋ為主的ˋ命令列介面ˋ互動功能。
     -使用ˋ虛擬終端機ˋ的形式。
     -屬於TCP/IP協議族。
   # ssh
     -Secure Shell Protocol安全外殼協議。
     -一種ˋ加密ˋ的ˋ網路協議ˋ。
     -在不安全的網路中提供安全的傳輸環境。
     -常見用途是遠端登入系統。
     -保證非安全網路環境中資訊是加密完整可靠。
   # ftp 
     -File Transfer Protocol 檔案傳輸協議。
     -用於在ˋ客戶端ˋ和ˋ伺服器ˋ之間進行檔案傳輸。
     -有極高的延時。
     -是一個8位元的客戶端-伺服器協定。
     -有主動和被動模式。
   # sftp
     -Secure File Transfer Protocol安全文件傳輸協議。
     -是SSH 的ˋ2.0 版ˋ
     -可以通過可靠的ˋ數據流ˋ提供檔案的ˋ訪問、ˋ傳輸ˋ和ˋ管理ˋ。
     -提供ˋ安全ˋ的ˋ文件傳輸ˋ功能。
     -利用 SSH，故也稱為 安全殼檔案傳輸協定。
   # smtp
     -Simple Mail Transfer Protocol 簡單郵件傳輸協議 
     -通常用作傳送電子郵件資訊。
     -是一個「推播」協定。
     -不允許從遠端伺服器上接收訊息。
   # pop3
     -Post Office Protocol - Version 3 郵局協議
     -用於管理在伺服器上的電子郵件。
     -是TCP/IP協定族中的一員。
     -最新版本為POP3。
     -POP3只下載郵件，伺服器端不刪除。
   # SNMP
     - Simple Network Management Protocol簡單網路管理協議。
     -可以支援網路管理系統。
     -由一組網路管理的標準組成。
     -含一個應用層協定、資料庫模式，和一組資料物件。
     -監測連接到網路上的裝置是否有引起管理上關注的情況。
## 簡述底下傳輸層協定(英文全名與簡單功能說明):
   # TCP
     -Transmission Control Protocol傳輸控制協議
     -連接導向的、可靠的、基於位元組流的協定。
     -位於IP層之上，應用層之下。
     -資料稱為流;資料分組稱為分段。
     -用一個校驗和函式來檢驗資料。
   # UDP
     -User Datagram Protocol 用戶數據報協議
     -提供資料的不可靠傳遞。
     -簡單的面向資料包的通信協議
     -為網絡層和應用層提供接口。
     -適用於不必執行錯誤檢查和糾正的應用程式。
   # reliable(可靠的) vs unreliable(不可靠的)
     -TCP 有錯誤檢查和壅塞控制，UDP則無。
     -reliable:TCP
     -unreliable:UDP
   # TCP three-way handshaking(三項交握)
     1.syn(client-server) 
     2.syn、ack(server-client) 
     3. ack(client-server)
   # TCP syn flood attack
     -SYN洪水攻擊。
     -分佈式拒絕服務的攻擊。
     -利用正常 TCP 三向交握的一部分 來消耗服務器的資源並使其無響應。
## 簡述底下網路層協定(英文全名與簡單功能說明):
   # IP
     -Internet Protocol Address網際網路協定位址
     -由一串數字組成。
     -用於標識位置。
     -包含傳送主機的IP位址。
     -包含目的主機的IP位址。
   # ICMP
     -Internet Control Message Protocol網際網路控制訊息協定
     -用於在IP中傳送控制訊息。
     -是IP的主要部分。
     -ICMP依靠IP來完成任務。
     -提供可能發生各種問題的回饋。
