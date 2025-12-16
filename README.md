# 🛡️ Cybersecurity & Penetration Testing Portfolio

Bu depo (repository), siber güvenlik alanında gerçekleştirdiğim laboratuvar çalışmalarını, sızma testi (pentest) simülasyonlarını ve teknik raporlarımı içermektedir.

## 📂 Projeler ve Raporlar

### 1. Rejetto HFS Sızma ve Kalıcılık (Persistence) Testi
Bu çalışmada, zafiyetli bir Windows sunucusu üzerinde yetki yükseltme ve kalıcılık sağlama adımları simüle edilmiştir.

* **Hedef Sistem:** Windows Server (Virtual Lab Environment)
* **Zafiyet:** Rejetto HTTP File Server (HFS) - Remote Code Execution
* **Kullanılan Araçlar:**
    * Kali Linux
    * Metasploit Framework (`exploit/windows/http/rejetto_hfs_exec`)
    * Meterpreter
* **Uygulanan Teknikler:**
    * Uzaktan Kod Yürütme (RCE) ile sisteme ilk erişim (Initial Access).
    * `persistence_service` modülü kullanılarak, sistem yeniden başlatılsa bile erişimin devam etmesini sağlayan kalıcı servis ("ASEL") oluşturma.
    * Oturum yönetimi ve süreç (process) takibi.

📄 **Rapor Dosyası:** Depodaki PDF dosyasını inceleyebilirsiniz.

[Metasploit_Persistence_Report.pdf](https://github.com/user-attachments/files/24189232/Metasploit_Persistence_Report.pdf)


### ⚠️ Yasal Uyarı (Disclaimer)
Bu depodaki tüm çalışmalar tamamen **eğitim ve araştırma amaçlıdır**. Çalışmalar, izole edilmiş sanal laboratuvar ortamlarında (VMware/VirtualBox) gerçekleştirilmiştir.
