# Levantamiento de Requerimientos
- Que tipo de laboratorios? (los que no son de informatica)
- Cuanto personal administrativo hay?
- Cual es el numero aproximado de alumnos?
- Que nivel de seguridad se desea implementar?
- Los profesores y administrativos necesitan comunicacion voz sobre ip?
- Consideraron un lugar para el site?
- Se desea un servicio de CCTV?
- Numero de equipos en el laboratorio de informatica?
- Medidas en el mapa
# Propuesta de diseno de Red
![](https://user-images.githubusercontent.com/14984859/58755078-ecdcb880-84a1-11e9-94de-a031b998abc1.gif)
# VLAN'S
## Alumnos
## Docente
## Administrativos
# Propuesta de ACL
1. Prohibir a la VLAN de alumnos el acceso a las VLAN de docentes y administrativos.
2. Permitir a la VLAN de Docentes la VLAN de Alumnos y prohibir la VLAN de administrativos.
3. Permitir todos los HOST a la VLAN de administrativos.
# Propuesta de VPN
Solo la VLAN de Administrativos contara con un VPN con un canal de acceso