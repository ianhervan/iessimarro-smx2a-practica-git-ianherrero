## Configuració del servidor DHCP

**1. Activació del servei DHCP**

S'ha instal·lat i activat el servei DHCP al servidor. Aquest servei permet assignar automàticament adreces IP als equips connectats a la xarxa.

**2. Configuració del rang d'adreces IP**

S'ha configurat el rang d'adreces dinàmiques des de `192.168.1.10` fins a `192.168.1.50`, perquè els equips clients puguen obtindre una adreça IP automàticament.

**3. Configuració de la porta d'enllaç**

S'ha configurat la porta d'enllaç perquè els equips puguen comunicar-se amb altres xarxes. S'ha indicat l'adreça IP del router de la xarxa.

**4. Configuració del servidor DNS**

S'ha configurat l'adreça del servidor DNS perquè els equips puguen resoldre noms de domini, com ara els d'una pàgina web, i accedir als serveis de xarxa corresponents.

**5. Verificació amb tres equips de prova**

S'ha comprovat la configuració connectant tres equips clients a la xarxa. En cada equip s'ha verificat que:
- Rep automàticament una adreça IP dins del rang `192.168.1.10–192.168.1.50`.
- Té configurada correctament la porta d'enllaç.
- Rep el servidor DNS indicat.
- Pot comunicar-se amb la xarxa segons la configuració establida.

**Conclusió**

La configuració es considera correcta si els tres equips reben els paràmetres de xarxa esperats i poden comunicar-se adequadament.
