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
   **由下而上排序
   1. Link(Physical Layer、Data Link Layer) 
   2. Internet
   3. Transport
   4. Application(Seesion、Presentation、Application)
   **Another version of TCP/IP
   1. Physical Layer
   2. Data Link Layer
   3. Internet
   4. Transport
   5. Application(Seesion、Presentation、Application)
## 簡述底下應用層協定(英文全名與簡單功能說明):
   # HTTP
     -HyperText Transfer Protocol 超文本傳輸協定
     -HTTP是一種用於分佈式、協作式和超媒體訊息系統的應用層協定
     -HTTP是全球資訊網的數據通信的基礎。
     -HTTP最初目的是為了提供一種發布和接收HTML頁面的方法
     -透過HTTP或者HTTPS協定請求的資源由URI來標識。
   # HTTPS
     -Hypertext Transfer Protocol Secure安全超文本傳輸協議。
     -HTTPS是HTTP的擴展。
     -HTTPS用於計算機網絡上的ˋ安全通信ˋ。
     -HTTPS目的是提供對網站伺服器的身份認證，保護交換資料的私隱與完整性。
     -HTTPS在Internet上，被廣泛使用。
   # DNS 
     -Domain Name System 域名系統。
     -將域名和IP位址相互對映的一個分散式資料庫。
     -DNS使用TCP和UDP埠53。
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
     -Telnet使用於ˋ網際網路ˋ及ˋ區域網ˋ中。
     -Telnet提供ˋ雙向ˋ、以ˋ文字字串ˋ為主ˋ的命令列介面ˋ互動功能。
     -Telnet使用ˋ虛擬終端機ˋ的形式。
     -屬於TCP/IP協議族的其中之一。
   # ssh
     -Secure Shell Protocol安全外殼協議。
     -SSH是一種ˋ加密ˋ的ˋ網路協議ˋ。
     -在不安全的網路中提供安全的傳輸環境。
     -常見用途是遠端登入系統。
     -保證非安全網路環境中資訊加密完整可靠。
   # ftp 
     -File Transfer Protocol 檔案傳輸協議。
     -用於在ˋ客戶端ˋ和ˋ伺服器ˋ之間進行檔案傳輸。
     -有極高的延時。
     -是一個8位元的客戶端-伺服器協定。
     -有兩種使用模式：主動和被動
   # sftp
     -Secure File Transfer Protocol安全文件傳輸協議。
     -SFTP是SSH 的ˋ2.0 版ˋ
     -SFTP可以通過可靠的ˋ數據流ˋ提供檔案的ˋ訪問、ˋ傳輸ˋ和ˋ管理ˋ。
     -SFTP提供ˋ安全ˋ的ˋ文件傳輸ˋ功能。
     -利用 SSH，故也稱為 安全殼檔案傳輸協定。
   # smtp
     -Simple Mail Transfer Protocol 簡單郵件傳輸協議 
     -SMTP通常用作傳送電子郵件資訊。
     -是一個「推播」協定。
     -不允許從遠端伺服器上接收訊息。
   # pop3
     -POP是TCP/IP協定族中的一員
     -POP用於管理在伺服器上的電子郵件。
     -最新版本為POP3。
   # SNMP
     - Simple Network Management Protocol簡單網路管理協議。
     -
     -
     -
     -
## 簡述底下傳輸層協定(英文全名與簡單功能說明):
   # TCP
     -Transmission Control Protocol傳輸控制協議
     -連接導向的、可靠的、基於位元組流的協定。
     -TCP層是位於IP層之上，應用層之下。
     -資料稱為流。
     -資料分組稱為分段。
   # UDP
     -User Datagram Protocol 用戶數據報協議
     -提供資料的不可靠傳遞。
     -簡單的面向資料包的通信協議
     -為網絡層和應用層提供接口。
   # reliable(可靠的) vs unreliable(不可靠的)
   # TCP three-way handshaking(三項交握)
   # TCP syn flood attack
## 簡述底下網路層協定(英文全名與簡單功能說明):
   # IP
   # ICMP
