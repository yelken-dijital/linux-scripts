
# 🌊 Yelken Dijital – Linux Scripts

__  __     ____                 ____  _   _ _ __        __            __  ______ 
\ \/ /__  / / /_____  ____     / __ \(_) (_|_) /_____ _/ /            \ \/ / __ \
 \  / _ \/ / //_/ _ \/ __ \   / / / / / / / / __/ __ `/ /  ______      \  / / / /
 / /  __/ / ,< /  __/ / / /  / /_/ / / / / / /_/ /_/ / /  /_____/      / / /_/ / 
/_/\___/_/_/|_|\___/_/ /_/  /_____/_/_/ /_/\__/\__,_/_/               /_/_____/  
                                   /___/                                         

Yelken Dijital tarafından geliştirilen otomasyon ve sunucu yönetim scriptlerinin toplu deposu.  
Bu scriptler; Proxmox, Docker, sanallaştırma ve sistem kurulumlarını hızlı, güvenli ve standart hâle getirmek için hazırlanmıştır.

----------

## 🐳 Docker VM Kurulumu

Proxmox üzerinde otomatik Docker VM oluşturur.  
Tüm yapılandırmalar (VM, ağ, depolama, paket kurulumları vb.) script tarafından yapılır.

### 📥 Kurulum

Terminalde aşağıdaki komutu çalıştırmanız yeterlidir:

```sh
bash -c "$(curl -fsSL https://raw.githubusercontent.com/yelken-dijital/linux-scripts/refs/heads/main/docker-vm.sh)"
``` 

### 🔑 Varsayılan Bilgiler

-   **Kullanıcı:**  `root` 
-   **Şifre:**  `docker`  

> İlk girişte şifreyi değiştirmeniz tavsiye edilir.

## 🐧 Ubuntu 2504 VM Kurulumu

Proxmox üzerinde otomatik Ubuntu VM oluşturur.  
Tüm yapılandırmalar (VM, ağ, depolama, paket kurulumları vb.) script tarafından yapılır.

### 📥 Kurulum

Terminalde aşağıdaki komutu çalıştırmanız yeterlidir:

```sh
bash -c "$(curl -fsSL https://raw.githubusercontent.com/yelken-dijital/linux-scripts/refs/heads/main/ubuntu-vm.sh)"
``` 

----------

## 📘 Notlar

-   Scriptler yalnızca Linux ortamları için optimize edilmiştir.
-   Proxmox VE 9.0+ sürümleriyle uyumludur.  
-   Her script düzenli olarak güncellenir.
