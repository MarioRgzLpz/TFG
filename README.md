# Criptografía Basada en Retículos: Implementación de CrystalKyber

## Introducción

Este repositorio está dedicado al estudio y desarrollo de la **criptografía basada en retículos**, un enfoque moderno que promete resistencia a los ataques cuánticos. El proyecto incluye:

1. Una base teórica completa sobre criptografía en retículos escrita en LaTeX.
2. Una implementación práctica del criptosistema **CrystalKyber**, elegido 2022 en el proceso de estandarización de criptografía post-cuántica de NIST como el estándar para criptografía post-cuántica.

---

## Funcionalidades

- **Fundamento Teórico**:
  - Un documento en LaTeX que explica los fundamentos matemáticos de la criptografía en retículos.
  - Conceptos clave como el **Aprendizaje con Errores (LWE)**, el **Aprendizaje con Errores en Módulos (MLWE)** y cómo estos sustentan la seguridad de CrystalKyber.

- **Implementación**:
  - Una implementación en Ruby del criptosistema CrystalKyber con explicaciones paso a paso.
  - Soporte para **generación de claves**, **cifrado**, **descifrado** y el **mecanismo de encapsulación de claves (KEM)**.

---

## Estructura del Proyecto

```plaintext
📂 criptografia-reticulos-crystalkyber/
├── 📂 docs/
│   ├── 📂 latex/
│   ├── gestor-dependencias.md
│   ├── gestor-tareas.md
│   ├── criptografia_reticulos_teoria.pdf
├── README.md
├── LICENSE
