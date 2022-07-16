<h1 align="center"> Sui Devnet Node Kurulumu </h1> 

Not: Türkçeye çevrilmiştir, alıntıdır.
![image](https://user-images.githubusercontent.com/101149671/178116806-26715fca-3ff8-43d5-ae1e-cee3926828de.png)

# Telegram kanalı: https://t.me/SuiTurkish

# Gereksinimler (minimum) (ekip tavsiyesi 8 ram):
```
2 CPU
4 RAM
50 SSD
```
Node kurduktan sonra sonda söyleyeceğim işlemleri yapmayı unutmayın!!

# Bir screen oluşturalım:
```
screen -S sui
```

# Full nodeumuzu yükleyelim:
```
wget -O sui.sh https://raw.githubusercontent.com/kj89/testnet_manuals/main/sui/sui.sh && chmod +x sui.sh && ./sui.sh
```

# Node başarılı çalıştıktan sonra karşınıza şu şekilde bir görsel çıkacak:

![image](https://user-images.githubusercontent.com/101149671/178935325-ba533e58-5cfa-4d9d-81f2-d7d595009b3b.png)

# Logları kontrol:
```
docker logs -f sui-fullnode-1 --tail 50
```

![image](https://user-images.githubusercontent.com/101149671/178935450-5928a3f9-e493-49f7-b235-913a56e7abc7.png)

# Şimdi Sui Wallet'ı kullanacağız.

* Telegram kanalı: https://t.me/SuiTurkish

* Sui Wallet'ı buradan indiriyoruz: [Wallet Linki](https://chrome.google.com/webstore/detail/sui-wallet/opcgpfmipidbgpenhmajoajpbobppdil/related)

* Daha sonra discorda girip: [Discord](https://discord.gg/8G2SQvwA) #devnet-faucet kanalından oluşturduğumuz cüzdan adresıne token alalım.

* DİKKAT ÇOK HIZLIDIR :)

* Daha sonra Twiter'da paylaşacağım yorumların altında birbirinize Yorumlarda SUİ adresi paylaşarak token gönderin.

* Benim adresim: 0x5c774c3e401f2c3a22dadb8014f843849d053fa1

* Ek olarak NFT 'de gönderelim: Ayarlar kısmından mint NFT demo diyerek mintliyoruz.

* Daha sonra buradan: http://sui-wallet-demo.s3-website-us-east-1.amazonaws.com/ bir NFT oluşturalım ve bunu birbirimize gönderelim.

* Explorer https://explorer.devnet.sui.io/

# Daha sonra discorda giriyoruz ve şu şekilde mesaj atıyoruz #node-ip-application kanalına: https://discord.gg/GUeN8TY7xD

* DAHA ÖNCE ATTIYSANIZ BİR DAHA GEREKLİ DEĞİL ATMANIZ İÇİN

![image](https://user-images.githubusercontent.com/101149671/178118265-a2463048-f656-4382-87cf-faaef1d032d0.png)

Not: #pick-a-role role kanalından da rol alabilirsiniz isterseniz emojilere tıklayarak.

# Nodeunuzu kontrol etmek için: https://node.sui.zvalid.com/

![image](https://user-images.githubusercontent.com/101149671/178118300-29d6bf7e-c78a-40b0-97fd-26bd89d22b05.png)

<h1 align="center"> Yararlı komutlar </h1> 

# Loglar: 
```
journalctl -u suid -f -o cat
```

# Node silmek için:
```
sudo systemctl stop suid
sudo systemctl disable suid
sudo rm -rf ~/sui /var/sui/
sudo rm /etc/systemd/system/suid.service
```

# Node durumunu kontrol:
```
service docker status
```
![image](https://user-images.githubusercontent.com/101149671/178118339-82da6b52-bdb9-425a-af8d-832a671141aa.png)

# Node reset atma:
```
sudo systemctl restart suid
```

# Node durdurma: 
```
sudo systemctl stop suid
```

# Sorun yaşarsanız beni Telegram kanalı: https://t.me/SuiTurkish üzerinden etiketleyin . @Ruesandora kullanıcı adım.

# Hesaplar:

[<img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" width="16px"> Twitter   ](https://twitter.com/Ruesandora0) 

[<img src="https://cdn-icons-png.flaticon.com/512/1336/1336494.png" width="16px"> Forum   ](https://forum.rues.info/index.php)

[<img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="16px"> Telegram Announcement   ](https://t.me/RuesAnnouncement)

[<img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="16px"> Telegram Chat   ](https://t.me/RuesChat)

[Discord](https://discord.gg/ruescommunity)



