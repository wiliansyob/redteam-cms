# Forest - HTB

**Dificultad:** Media  
**Sistema operativo:** Windows  
**Categoría:** Active Directory

## 🧠 Enumeración

```bash
nmap -sC -sV -p- -T4 10.10.10.161
Descubrimos varios servicios relacionados con Active Directory: LDAP, SMB, Kerberos.

🔍 Enumeración de usuarios
Utilizando herramientas como rpcclient, enum4linux, o ldapsearch.

🎯 Ataque
Kerberos AS-REP roasting con GetNPUsers.py.

🪜 Escalada
Abuso de privilegios delegados en Active Directory.

🔚 Root
Obtenido acceso como Administrator mediante un ataque DCSync.

Notas:

Utiliza Impacket, BloodHound, evil-winrm.

Revisa el grupo Exchange Trusted Subsystem si aparece.