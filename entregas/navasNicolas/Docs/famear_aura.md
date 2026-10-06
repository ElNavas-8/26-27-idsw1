# Propuesta de Modelo de Dominio

## Escenario 1: Famear (Diagrama de Estados)

Para este escenario se optó por un diagrama de estados. Esto refleja fielmente la dinámica de cómo cambia la percepción relativa ("Aura") de una persona al interactuar y tratar de destacar ("Famear") dentro de un ámbito o contexto determinado.

```plantuml
@startuml
hide empty description

state Persona
state Farmea
state Aura_sube
state Aura_baja

Persona --> Farmea : Realiza acción llamativa

Farmea --> Aura_sube : Contexto valida (Aumenta Aura)
Farmea --> Aura_baja : Contexto rechaza o es Indiferente(Pierde Aura)

Aura_sube --> Farmea : Arriesga para ganar más
Aura_sube --> Aura_baja : Error grave en el contexto
Aura_sube --> [*] : Sale del Contexto

Aura_baja --> Farmea : Intento de redención
Aura_baja --> [*] : Sale del Contexto (Retirada)
@enduml
```

### Glosario

* **Contexto:** El entorno social o situacional que evalúa y reacciona a las acciones del individuo.
* **Farmea:** Estado activo en el que la persona ejecuta una acción buscando elevar su validación dentro del contexto.
* **Aura_sube / Aura_baja:** Estados relativos de la percepción social que indican la dirección (positiva o negativa) en la que se mueve el estatus tras una acción.

### Supuestos

1. El nivel inicial de "aura" de la persona no es necesario aclararlo ni cuantificarlo. Lo relevante es meramente la observación de su variación (sube o baja) como una hipérbole cuantitativa.
2. La indiferencia del contexto castiga al individuo de la misma forma que el rechazo directo.

### Decisiones de modelado discutibles

* **Uso de diagrama de estados en lugar de clases:** Se descartó el modelo de dominio estructural tradicional porque "Famear" es fundamentalmente un comportamiento y una fluctuación de estatus, no una entidad estática. El diagrama de estados captura de forma precisa la volatilidad de la validación social.