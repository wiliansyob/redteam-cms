

# Voleur - HTB

**Dificultad:** Media  
**Sistema operativo:** Windows  
**Categoría:** Web / Reversing

## 🧠 Enumeración

Escaneo de puertos y búsqueda de rutas web ocultas con `ffuf` revelan una aplicación web vulnerable.

## 🔓 Explotación

Deserialización insegura en .NET → `ysoserial.net` para generar el payload.

## 🛠 Post-Explotación

- Enumeración con `winPEAS`
- Extracción de credenciales desde memoria

## 🔚 Root

Escalada a SYSTEM mediante servicio vulnerable con permisos modificables por el usuario comprometido.
