
# 🌊 Yelken Dijital – Linux Scripts

Yelken Dijital tarafından geliştirilen otomasyon ve sunucu yönetim scriptlerinin toplu deposu.  
Bu scriptler; Proxmox, Docker, sanallaştırma ve sistem kurulumlarını hızlı, güvenli ve standart hâle getirmek için hazırlanmıştır.

----------

## 🐳 Docker VM Kurulumu

Proxmox üzerinde otomatik Docker VM oluşturur.  
Tüm yapılandırmalar (VM, ağ, depolama, paket kurulumları vb.) script tarafından yapılır.

### 📥 Kurulum

Terminalde aşağıdaki komutu çalıştırmanız yeterlidir:

`bash -c "$(curl -fsSL https://raw.githubusercontent.com/yelken-dijital/linux-scripts/refs/heads/main/docker-vm.sh)"` 

### 🔑 Varsayılan Bilgiler

-   **Kullanıcı:**  `root`
    
-   **Şifre:**  `Docker`
    

> İlk girişte şifreyi değiştirmeniz tavsiye edilir.

----------

## 📘 Notlar

-   Scriptler yalnızca Linux ortamları için optimize edilmiştir.
    
-   Proxmox VE 9.0+ sürümleriyle uyumludur.
    
-   Her script düzenli olarak güncellenir.