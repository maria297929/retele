## Intrebari

172.20.0.255 este un IP **e.private** de tipul 20-bit, din clasa B
Tipologia retelelor de calculatoare: point-to-point, daisy chain, bus, star, mesh, ring
un hub copiaza informatia de pe un port pe toate celelalte porturi -> afirmatie e **true**
Securitatea in retelele wireless nu se poate asigura prin **d.DNS**
netstat afiseaza conexiunile **d.ingoing si outgoing pe protocolul TCP**
SMTP (simple mail transfer protocol) este un protocol pentru **a.transmitere de emailuri**
alocarea automata de IP uri o face serverul de **c.DHCP**
OSI model contine standardul pt arhitectura de layers: **j.fizic, b.data, i.network, g.transport, e.session, h.prezentare, c.Aplicatie**
Adresele de tip IPv4 de clasa B merg pana la **c.65 536 de adrese**
MD5 (checksum) e **c.un protocol de asigurare a integritatii datelor (nu mesajelor)** si e plin de vulnerabilitati
In header de la un pachet IP contine 13 fields (al 14-lea optional). Din lista, doar **b.TTL** si **d.TOS** ar fi corecte, ca source address si destination address nu e totuna cu port. Mai multe info se pot citi pe [wiki](https://en.wikipedia.org/wiki/IPv4#Header)
Transfer de date se poate face prin **HTTP** si **FTP**
DNS server **d.face asocierea intre URL si IP**
In OSI bits se gasesc la **d.nivelul fizic**
Addressing se face la nivelul **b.network**
**b.Firewall** nu e un tip de atac si un fel de a controla conexiunile la nivel de porturi
UDP e un protocol **d.rapid** si **e.nesigur**
**c.LAN sunt localizate intr-o singura cladire sau distante de cativa km**

TCP/IP model contine nivelele: network, internet, transport, application (e mai concis ca si OSI model) -> eventual **d. application, transport, internet**
Pentru o retea de 483 de calculatoare subnet mask este ---------- cat zice sys adminul...
TCP **este** un protocol orientat spre conexiune
UDP **nu este** un protocol orientat pe conexiune (connectionless)
protocolul **c.DNS** este utilizat pt determinarea IP in fct de domain name
Router poate functiona ca un switch, **d. indiferent de componenta hardware**
RSA e un sistem de **a. criptare simetrica**
TTL (time-to-live) e in header ul de la IP packet si contine **e. timpul cat poate exista un pachet IP, inainte de a fi distrus** (si trimis inapoi la sursa)
Protocolul pt asocierea addresei de MAC pe baza de IP **nu exita** dar poti sa afli IP pe baza la MAC prin protocolul **b. ARP** (link discovery (MAC address) si asocierea lor cu internet link (IP address) - conform TCP/IP model)
Pentru o retea de 83 de calculatoare subnet mask este ------------
`ipconfig /all` afiseaza **a.adresa IP a host PC** si **b. adresa IP a gateway**
La configurarea de IP static e nevoie sa configurezi **a.netmask**,**d. gateway**, **e.IP**, optional DNS si second DNS
Bandwitdh este **a.cantitatea de info care poate fi trasnferata intr-un interval de timp** intr-o retea de calculatoare



## CANBus vs etherCAT
many devices that support this protocol available on market
easier to implement if the device is found
no master slave, just matrix layout
no talker listener, no deterministic, bedingtgeeignet