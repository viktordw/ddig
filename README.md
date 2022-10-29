# ddig

Alat za brzu proveru DNS zapisa.

Preporučeni način instalacije (MobaXTerm):

```
wget https://raw.githubusercontent.com/viktordw/ddig/master/ddig
mkdir -p custom && mv ddig custom && chmod +x custom/ddig
ln -s ~/custom/ddig /bin/ddig
```

Upotreba:

```
ddig asdf.com
==================================================
Results for domain: asdf.com
==================================================
IP address: 64.90.40.65
Hostname: apache2-jolly.fairview.dreamhost.com

WWW Type: A
WWW IP: 64.90.40.65
WWW Hostname: apache2-jolly.fairview.dreamhost.com.

MX Data:
  mx10.asdf.com
MX IP: 54.152.40.166
MX Hostname: mx10.asdf.com.

DNS Servers: 
  ns3.dreamhost.com
  ns2.dreamhost.com
  ns1.dreamhost.com
==================================================
```
