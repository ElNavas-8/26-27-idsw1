# Propuesta de Modelo de Dominio

## Escenario 1: Famear (Diagrama de Estados)

Para este escenario se optó por un diagrama de estados. Esto refleja fielmente la dinámica de cómo cambia la percepción relativa ("Aura") de una persona al interactuar y tratar de destacar ("Famear") dentro de un grupo social o contexto (el "chat" o el "lobby").

![DDE_Farmear_Aura](/entregas/navasNicolas/diagramas_UML/DDE_Farmear_Aura_2.png)

### Glosario (Lenguaje del Dominio)

* **Bro / Persona:** El individuo que inicia la interacción buscando validación.
* **Farmeando:** Estado activo donde el sujeto intenta hacer algo destacable (ponerse *tryhard*).
* **Modo_Prime (+Aura):** Estado de alta validación social. Se alcanza cuando el contexto aprueba la acción (*W*, *Basado*).
* **Flop (-Aura):** Estado de pérdida de estatus. Ocurre cuando la acción genera rechazo o vergüenza ajena (*L*, *Cringe*).
* **Chat / Lobby:** Referencias implícitas al contexto social o grupo de espectadores que actúa como juez de las acciones.

### Supuestos

1. El nivel inicial de "aura" de la persona no es necesario aclararlo ni cuantificarlo. Lo relevante es meramente la observación de su variación (sube o baja) como una hipérbole cuantitativa.
2. El entorno ("chat") juzga de forma binaria en la mayoría de los casos: o es una victoria (W) o es una derrota (L).

### Decisiones de modelado discutibles

* **Uso de diagrama de estados en lugar de clases:** Se descartó el modelo de dominio estructural tradicional porque "Famear" es fundamentalmente un comportamiento y una fluctuación de estatus, no una entidad estática. El diagrama de estados captura de forma precisa la volatilidad de la validación social.
* **Adopción de Lenguaje Ubicuo (Jerga de internet):** Se decidió utilizar términos como "Modo_Prime", "Flop" o "Cringe" en lugar de "Aumento de percepción positiva" o "Rechazo del contexto". En el Diseño Guiado por el Dominio (DDD), el modelo debe hablar el mismo idioma que los expertos del negocio (en este caso, los jóvenes de 15 años), evitando traducciones formales que pierdan la intención original.