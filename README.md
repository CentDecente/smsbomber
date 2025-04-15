# CentDecente-SmsBomber
_It's centdecente to make a man go crazy_
<br><br>
[![Hits](https://hits.sh/github.com/tingirifistik/Enough-Reborn.svg?label=views&color=007ec6)](https://hits.sh/github.com/tingirifistik/Enough-Reborn/)




<h2>Kurulum</h2>

```console
git clone https://github.com/CentDecente/smsbomber.git
cd smsbomber
pip3 install -r requirements.txt
python3 smsbomber.py
```


<h2>Discord Bot</h2>

Bot'un çalışabilmesi için 'Privileged Gateway Intents' seçeneklerinin hepsinin aktif olması gerekmektedir.

<h2>Discord Selfbot</h2>

**Token bulma:**

1- Tarayıcıdan bot olarak kullanacağınız Discord hesabına giriniz.<br>
2- Tarayıcı konsolunu açınız.<br>
3- Ağ trafiği izleme bölümüne geliniz.<br>
4- Konsolu kapatmadan, Discord'da bu oturum boyunca tıklamadığınız bir sohbete tıklayınız.<br>
5- Sonu *messages?limit=50* ile biten isteğe tıklayınız.<br>
6- İsteğin *Header* kısmındaki *Authorization* değeri sizin token'ınızdır.<br>
7- Bu token'ı *discord-selfbot-centdecente.py*'de *token* kısmına yazınız. (str olarak)<br>

**Chat Id Bulma:**

1- Bot hesabı ile mesajlaşacağınız kendi orijinal hesabınızdan bot'a bir tane mesaj atınız.<br>
2- Tarayıcıda Discord'u açın ve bot hesabına giriş yapınız, ardından gerçek hesabınızın üzerine tıklayın.<br>
3- Url'deki *@me*'den sonraki sayı sizin sohbet id'nizdir.<br>
4- Bu id'yi *discord-selfbot-centdecente.py*'de *chat_id* kısmına yazınız. (int olarak)<br><br>
**Not:** Eğer bot'u Discord sunucusunda kullanacaksanız, *channels*'dan sonra gelen, taksim ile ayrılmış iki sayıdan ikincisi sohbet id'nizdir.
<br><br>
<a href="https://github.com/CentDecente" target="_blank"><img src="https://img.shields.io/badge/Github-blue?style=for-the-badge&logo=github"></a>
