#  Extensible Storage Engine

Link: [維基百科](https://zh.wikipedia.org/wiki/可扩展存储引擎)

**可延伸儲存引擎**（**Extensible Storage Engine**，縮寫**ESE**）也稱**JET Blue**，它是[微軟](https://zh.wikipedia.org/wiki/%E5%BE%AE%E8%BD%AF "微軟")的一個[ISAM](https://zh.wikipedia.org/wiki/ISAM "ISAM")（有索引順序存取方法）資料儲存技術。ESE是[Microsoft Exchange Server](https://zh.wikipedia.org/wiki/Microsoft_Exchange_Server "Microsoft Exchange Server")、[Active Directory](https://zh.wikipedia.org/wiki/Active_Directory)、[Branch Cache](https://zh.wikipedia.org/w/index.php?title=Branch_Cache&action=edit&redlink=1)和[Windows搜尋](https://zh.wikipedia.org/wiki/Windows%E6%90%9C%E7%B4%A2 "磁碟磁區")的核心組件。它也被眾多Windows組件使用，包括[Windows Update](https://zh.wikipedia.org/wiki/Windows_Update "Windows Update")客戶端和[幫助和支援中心](https://zh.wikipedia.org/wiki/Windows_%E7%BB%84%E4%BB%B6%E5%88%97%E8%A1%A8 "Windows 組件列表")。它的目的是允許應用程式通過索引和順序存取來儲存和檢索資料。

SE提供[事務型](https://zh.wikipedia.org/wiki/%E6%95%B0%E6%8D%AE%E5%BA%93%E4%BA%8B%E5%8A%A1 "Microsoft Exchange Server")資料更新和恢復。它包含一種崩潰恢復機制，因此能保證系統崩潰下的[資料一致性](https://zh.wikipedia.org/w/index.php?title=%E6%95%B0%E6%8D%AE%E4%B8%80%E8%87%B4%E6%80%A7&action=edit&redlink=1)。ESE中的事務高度並行的，因此ESE適合於伺服器應用程式。ESE會智慧型快取資料，從而確保對資料的高效能存取。此外，ESE很輕便，適用用於輔助應用程式。

ESE執行時（ESENT.DLL）自[Windows 2000](https://zh.wikipedia.org/wiki/Windows_2000 "Windows 2000")起預裝在每個[Windows](https://zh.wikipedia.org/wiki/Microsoft_Windows "Microsoft Windows")版本中。自[Windows XP](https://zh.wikipedia.org/wiki/Windows_XP "Windows XP")和[Windows Server 2003](https://zh.wikipedia.org/wiki/Windows_Server_2003 "Windows Server 2003")的64位元版本開始，ESE執行時擁有原生64位元版本。[Microsoft Exchange](https://zh.wikipedia.org/wiki/Microsoft_Exchange_Server)截至[Exchange 2003](https://zh.wikipedia.org/wiki/Microsoft_Exchange_Server "Microsoft Exchange Server")時僅包含32位元版本。在[Exchange 2007](https://zh.wikipedia.org/w/index.php?title=Exchange_2007&action=edit&redlink=1)中，它開始搭載64位元版本。

###### tags: #wiki #database 