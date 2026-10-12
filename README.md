# Homelab de Ciberseguridad

Laboratorio casero orientado a formación como Analista de Ciberseguridad (SOC).
De la teoría (Network+, Security+) a la práctica demostrable.

## Arquitectura

Mini-empresa simulada con 3 segmentos aislados detrás de un firewall virtual (pfSense):

| Segmento | Red | Función |
|---|---|---|
| LAN Corp | 10.10.10.0/24 | Active Directory, endpoints Windows |
| Red SOC | 10.10.20.0/24 | SIEM Wazuh, monitoreo |
| Red Team | 10.10.30.0/24 | Kali Linux (atacante), víctimas controladas |

## Fases

- [ ] Fase 0: Preparación del host
- [ ] Fase 1: Red y firewall
- [ ] Fase 2: Infraestructura tipo empresa (AD)
- [ ] Fase 3: SOC, detección y monitoreo
- [ ] Fase 4: Ataque controlado y detección (MITRE ATT&CK)
- [ ] Fase 5: Portfolio y salida laboral

## Reglas del lab

- Todo ataque se ejecuta únicamente contra mis propias VMs, en red aislada.
- Snapshot antes de cada práctica destructiva.
- Las credenciales del lab son únicas y distintas de mis cuentas reales.
