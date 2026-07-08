# AI-DevPods

> **El sistema de registro del cambio de IA confiable.**

AI-DevPods pone a trabajar **pods** de desarrollo autónomos sobre tus repositorios
—revisando, corrigiendo y construyendo— y entrega cada cambio como un pull request
en el que podés confiar: revisado, testeado y respaldado por un rastro auditable de
*qué cambió, por qué y cómo se verificó*.

---

## Qué es

AI-DevPods se instala en tu organización de GitHub como una sola app y pone una
flota de pods de IA especializados a trabajar sobre tus repos. El control lo tenés
vos: los pods proponen, las personas aprueban, y nada sensible se publica sin pasar
por un gate de revisión. Cada resultado llega como un pull request normal —sin cajas
negras, sin magia.

## Cómo funciona

1. **Instalás** la GitHub App en los repositorios que quieras cubrir.
2. **Configurás** el comportamiento por repo con un simple `.aidevpods.yml`
   (runtime, comandos, rutas sensibles, presupuestos, reportes de ROI).
3. **Disparás** un pod desde un issue, un comentario o una mención — el pod hace el
   trabajo en un entorno aislado.
4. **Revisás** el pull request resultante, con su paquete de evidencia incluido.
   Aprobás, pedís cambios, o dejás que los cambios confiables se mergeen solos.

## Los pods

Un conjunto de pods enfocados, cada uno con una tarea acotada y su propia vara de
calidad — desde **revisión de código** y **corrección de bugs** hasta el **armado de
producto nuevo**. Los pods branchean desde una base compartida, abren pull requests
con código real y funcionando, y entregan con evidencia completa.

## Hecho para la confianza, no solo para la velocidad

La parte difícil del código generado por IA no es escribirlo — es *confiar* en él.
Ese es el corazón de AI-DevPods:

- 🧪 **Calidad demostrable** — gates de revisión adversarial, criterios de aceptación
  configurables y chequeos end-to-end opcionales antes de que algo se mergee.
- 🧾 **Paquetes de evidencia** — cada pull request lleva el registro de qué se testeó,
  qué pasó y cómo se validó el cambio.
- 🔐 **Gobierno humano** — las rutas sensibles requieren una aprobación humana
  explícita, pedida y otorgada a través del propio GitHub.
- 📊 **Reporte de ROI** — tasa de acierto en la primera pasada, time-to-green y señales
  de costo, para que el valor sea medible y no una suposición.

## Configuración

Todo lo que un pod tiene permitido hacer se declara por repo en `.aidevpods.yml` —
runtime y comandos, rutas sensibles que fuerzan aprobación humana, topes de
presupuesto y reportes. Explícito por diseño.

---

<sub>AI-DevPods — pods de desarrollo autónomos con un rastro de confianza verificable.</sub>
