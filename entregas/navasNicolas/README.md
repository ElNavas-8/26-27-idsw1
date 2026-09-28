# Propuestas de Modelo de Dominio

A continuación, se presentan los modelos para dos de los escenarios propuestos, basados en los diagramas UML diseñados.

---

## Escenario 1: Farmear Aura

![Logotipo de Markdown](/entregas/navasNicolas/docs/MDM_Famear_Aura.jpg)

### Glosario
*   **Persona:** Individuo base que actúa en el entorno.
*   **Aura:** Representación abstracta del carisma o "vibra" de la persona. Posee atributos medibles como *flow* y *non-chalance*.
*   **Espectador:** Tercero que observa y valida las acciones de la persona.
*   **Farmear Aura (AuraRelationship):** Evento o interacción donde el nivel de aura de una persona aumenta (o disminuye) ante los ojos de un espectador.

### Supuestos
1.  El "aura" no es estática; es un recurso cuantificable y volátil.
2.  El acto de "farmear" requiere validación externa; no se puede farmear aura en total aislamiento (se necesita al menos un *Espectador*).

### Decisiones Discutibles
*   **Modelar el "Farmeo" como una clase intermedia:** En lugar de ser un simple método dentro de `Persona`, se modeló como una entidad/relación (`AuraRelationship`) porque involucra un evento temporal que requiere la participación obligatoria de un `Espectador` para afectar el `Aura`.

---

## Escenario 2: Una Sombra

![Logotipo de Markdown](/entregas/navasNicolas/docs/MDM_Sombra.jpg)

### Glosario
*   **Fuente de Luz:** Entidad que emite fotones en el entorno.
*   **Cuerpo Opaco:** Objeto físico que se interpone en la trayectoria de la luz.
*   **Sombra:** Fenómeno óptico proyectado por el cuerpo opaco.
*   **Umbra:** Región de la sombra donde la luz es bloqueada totalmente.
*   **Penumbra:** Región de la sombra donde la luz es bloqueada parcialmente.

### Supuestos
1.  Se asume un entorno físico euclidiano simple con una única fuente de luz principal para evitar solapamientos complejos de múltiples sombras.
2.  Todo cuerpo opaco iluminado proyecta incondicionalmente una sombra.

### Decisiones Discutibles
*   **Relación entre Sombra, Umbra y Penumbra:** El diagrama original sugería "es parte de" (composición), pero la representación gráfica usaba flechas de generalización. Se justifica considerarlos como subtipos (Herencia) si asumimos que un píxel/punto específico en el espacio es "una Umbra" o "una Penumbra", siendo ambos tipos específicos de "Sombra". Sin embargo, si hablamos de la sombra como un todo geométrico, la *composición* hubiera sido más precisa semánticamente.