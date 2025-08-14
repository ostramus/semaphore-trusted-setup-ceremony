# semaphore-trusted-setup-ceremony

## Gerekenler ;

• Sunucu yada Windows WSL - Açık kalması önemli. Ben normal 4 CPU 8 Ram'li diğer nodelerin bulunduğu serverda başlattım.

•İnternet hızınız iyi olmalı birazda disk alanınız olsun.



## GitHub hesabınız aşağıdaki kriterleri karşılamalıdır:

• En az bir aylık

• En az bir genel repo

• En az 5 GitHub hesabı takip ve en az 1 takipçisi olmalıdı

• Ceremony araçlarının hesabınızdaki GitHub Gist'lerini okumasına ve yazmasına izin vermelidir.

## Sistem Güncelleme

```bash
sudo apt update -y && sudo apt upgrade -y
```

## Gerekli Paketlerin Kurulumu

```sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen file unzip lz4 -y```