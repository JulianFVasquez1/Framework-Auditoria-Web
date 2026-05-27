# Framework de Auditoría Web

Framework metodológico de auditoría web orientado a la evaluación de seguridad sobre el sistema LatinoamericaComparte.

Proyecto académico desarrollado para la Universidad Santo Tomás — Facultad de Ingeniería de Sistemas.

---

## Objetivo

Definir un proceso estructurado para:

- Reconocimiento pasivo y activo
- Análisis HTTP
- Escaneo de puertos y servicios
- Evaluación DAST
- Identificación de vulnerabilidades web
- Documentación de hallazgos

---

## Herramientas utilizadas

- OWASP ZAP
- BurpSuite
- Nmap
- HTTrack
- Maltego
- dig / nslookup
- Kali Linux

---

## Metodología

El framework implementa las siguientes fases:

1. Reconocimiento pasivo (OSINT)
2. Reconocimiento activo
3. Análisis de tráfico HTTP
4. Escaneo de puertos y servicios
5. Análisis estático del frontend
6. Escaneo dinámico DAST
7. Clasificación de hallazgos
8. Recomendaciones técnicas

---

## Hallazgos identificados

- Ausencia de cabeceras CSP
- HSTS no implementado
- Configuración CORS insegura
- Firma Apache expuesta
- Recursos externos sin SRI
- Ausencia de controles Anti-CSRF

---

## Estructura del repositorio

```bash
Framework-Auditoria-Web/
│
├── docs/
├── commands/
├── reports/
├── README.md
└── LICENSE
```

---

## Documento principal

El framework completo se encuentra en:

```txt
docs/Framework_Auditoria_Web_ZAP_Corporativo_v3.docx
```

---

## Referencias

- OWASP Testing Guide v4
- OWASP ZAP
- NIST AI RMF
- BurpSuite Documentation
- Nmap Reference Guide

---

## Autor

- Julian Felipe Vásquez Ojeda
- David Leonardo Álvarez Porras
- Joseph Camilo Sáenz Rodríguez

Universidad Santo Tomás — 2026
