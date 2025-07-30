# Forest

<div style="display: flex; gap: 2rem; margin-bottom: 1rem;">
  <img src="../images/forest.png" alt="Forest" style="width: 250px; border-radius: 8px;" />
  <table>
    <tr><th>Nombre</th><td>Forest</td></tr>
    <tr><th>Dificultad</th><td>Media</td></tr>
    <tr><th>Sistema Operativo</th><td>Windows</td></tr>
    <tr><th>Categoría</th><td>Active Directory</td></tr>
    <tr><th>Fecha de resolución</th><td>Julio 2025</td></tr>
  </table>
</div>

---

## 🛰️ Escaneo

```bash
Get-Process

bash title="Shell de acceso"
nc -lvnp 4444
whoami

```

Resumen de puertos abiertos, servicios y versiones.

---

## ⚙️ Enumeración

- SMB
- LDAP
- RPC

---

## 💣 Explotación

Describe el exploit, herramienta o técnica utilizada.

---

## 🧬 Post-Explotación

- Enumeración de privilegios.
- Persistencia.
- Extracción de hashes.

---

## 🧠 Lecciones aprendidas

- Siempre revisar [Kerberoasting].
- Importancia del uso de `bloodhound` y `SharpHound`.

---

## 🛠️ Herramientas utilizadas

- `nmap`, `enum4linux`, `impacket`, `evil-winrm`, etc.

---

## 🔗 Referencias

- [HTB Writeups](https://example.com)
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
