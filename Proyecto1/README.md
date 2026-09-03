## Fase 2: Configuración Capa 2 (VTP, VLANs, STP y Trunks)

### Parámetros VTP
- **Dominio:** CHAPIN_RED
- **Contraseña:** usac2026
- **Versión:** 2
- **Modo Servidor:** MSW-BB-SUPERIOR
- **Modo Cliente:** Todos los demás switches

### VLANs Creadas
| ID | Nombre | Estado |
|----|--------|--------|
| 10 | VLAN_Naranja_EdificioIZQ_201901108 | Active |
| 20 | VLAN_Verde_EdificioIZQ_201901108 | Active |
| 30 | VLAN_Naranja_EdificioDER_201901108 | Active |
| 40 | VLAN_Verde_EdificioDER_201901108 | Active |
| 99 | VLAN_ADMIN_201901108 | Active |

### Verificación de Sincronización
- Revision Number sincronizada: 21
- MD5 Digest coincidente en Server y Clientes
- Rapid-PVST+ habilitado en todos los dispositivos