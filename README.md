# KigenOggly

**Investigación y preparación de la evolución de un sistema de tarjetas QR, enlaces y analítica que ya está en construcción.**

KigenOggly utiliza el marco de trabajo [Kigen](https://github.com/leoleguizamonpy/Kigen) para entender el producto existente, identificar necesidades y respaldar decisiones sobre su continuidad. El sistema de referencia es [QR](https://github.com/leoleguizamonpy/QR); su implementación sigue siendo independiente y no se duplica en este repositorio.

## Propósito

Analizar el propósito comercial, los actores, los flujos operativos, las fuentes de datos, la medición de interacciones, las políticas de acceso, la privacidad, la arquitectura y los riesgos de QR. Valorar la continuidad, mejoras de procesos, reutilización de herramientas o cambios de software sin seleccionar una alternativa antes de investigarla.

## Estado

El proyecto inicia en **Investigación y diagnóstico**, primer bloque funcional de Kigen. Su expediente canónico se conserva en `data/intake.json` y su resultado en `data/diagnosis.json`, con vistas derivadas en `docs/diagnosis/` una vez generado por Kigen. Las evidencias se vinculan a fuentes versionadas; no se consideran verificadas por el mero hecho de estar citadas.

QR se examina sobre `develop` en el commit `8e628c3484de31a1e88ab3b6e75cb2e25e371f32`, que permite reproducir la base de análisis sin alterar el código de origen.

## Autoridades

**Kigen** aporta los contratos y el proceso de diagnóstico. **KigenOggly** conserva el expediente y sus decisiones documentadas. **QR** mantiene la autoridad exclusiva sobre su código y funcionamiento. La investigación puede aportar hallazgos, pero el cierre y el cambio de etapa requieren aprobación humana y evidencias suficientes.

No se presupone que QR deba reconstruirse ni que todas sus funciones estén terminadas; ambas posibilidades deben determinarse a partir de la evidencia.
