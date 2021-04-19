事情的經過:微軟Exchange Server的Mail Server產品近期被「 Hafnium」 的駭客集團攻擊了四個零時差漏洞，存在於Exchange Server 的安全漏洞，編號命名為「CVE-2021-26855 」及「CVE-2021-27065」（稱其為「ProxyLogon」）。

ProxyLogon為什麼這麼嚴重:「 ProxyLogon」為重大的「無需驗證的遠端程式碼執行（Pre-Auth Remote Code Execution； Pre-Auth RCE）零日漏洞，駭客利用這些漏洞來存取企業內的 Exchange 伺服器，駭入使用者的電子郵件帳號，並且安裝其他惡意程式包含Web Shell、DearCry(勒索軟體)、Black Kingdom(勒索軟體)、DLTMiner(挖礦程式)等等的嚴重影響各個公司、國家機密資料與一般電腦使用者的安全。

判斷自己是否受到影響?

1.使用 Microsoft 偵測工具來掃描您的 Exchange Server 記錄檔，看看是否曾經遭到入侵。 

2.使用 Trend Micro Vision One 對您的環境進行清查，看看是否有這波攻擊的入侵指標 (IoC)

漏洞緩解措施

1.Exchange修補程式KB5000871 

2.安裝緩解工具Exchange On-Premises Mitigation Tool（EOMT）