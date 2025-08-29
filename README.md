# ft_irc

Bu proje, 42 Network kapsamında geliştirilen bir **IRC sunucusu** uygulamasıdır.  
C++ dilinde socket programlama, client-server mantığı, protokol işleme ve temel ağ yönetimi gibi konuların uygulamalı olarak öğrenilmesi amaçlanmıştır.

---

## 🚀 Amaç

- C++ ile socket programlama pratiği
- Select tabanlı çoklu istemci desteği
- Basit bir IRC protokolünün yeniden inşası
- Client, Server ve Channel sınıflarının nesne yönelimli tasarımı

---

## 📁 Proje Dosya Yapısı

irc/
├── main.cpp
├── Makefile
├── client/
│ └── Client.hpp
│ └── Client.cpp
├── server/
│ └── Server.hpp
│ └── Server.cpp
├── channel/
│ └── Channel.hpp
│ └── Channel.cpp

yaml
Kodu kopyala

---

## ⚙️ Derleme

```bash
make
./ircserv <port> <password>
nc localhost <port>
