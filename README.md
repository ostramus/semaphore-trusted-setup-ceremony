# semaphore-trusted-setup-ceremony

## Gerekenler ;

• Sunucu yada Windows WSL - Açık kalması önemli. Ben normal 4 CPU 8 Ram'li diğer nodelerin bulunduğu serverda başlattım.

•İnternet hızınız iyi olmalı birazda disk alanınız olsun.



## GitHub hesabınız aşağıdaki kriterleri karşılamalıdır:

• En az bir aylık

• En az bir genel repo

• En az 5 GitHub hesabı takip ve en az 1 takipçisi olmalıdı

• Ceremony araçlarının hesabınızdaki GitHub Gist'lerini okumasına ve yazmasına izin vermelidir.

## 1- Sistem Güncelleme

```bash
sudo apt update -y && sudo apt upgrade -y
```

## 2- Gerekli Paketlerin Kurulumu

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen file unzip lz4 -y
```

## 3- NVM
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
source .bashrc
````

```bash
nvm install 18 
nvm use 18
```

```bash
source ~/.bashrc
```


## Ceremony Adımları

• Dosya Oluşturma ;
```bash
mkdir ~/trusted-setup && cd ~/trusted-setup
```

•CLI İndirme
```bash
npm install -g @p0tion/phase2cli
```

•Githup Auth;
```bash
phase2cli auth
```

•Başladıktan Sonra Size Kod Vericek Github Auth ile bağlanmamız lazım 15 Dakika içinde.

•Link : https://github.com/login/device


