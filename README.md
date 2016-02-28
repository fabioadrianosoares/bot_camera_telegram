Bot Telegram Monitor de Cameras
=======

Bot para monitorar as cameras de seguranca do condominio onde moro.

Utilizei:
* [mojolicious](http://mojolicious.org/) - v6.48, perl 5.22.1
* [mango](https://metacpan.org/pod/Mango) - v1.26
* https://mongolab.com

-----

Para ligar o webHook
```bash
curl -v -H "Content-Type: application/json" -d '{"url": "https://<-- servidor do bot -->/camera/<-- bot key -->"}' "https://api.telegram.org/<-- bot key -->/setWebhook"
```