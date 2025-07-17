## 🔄 Diagrama del Flujo

```mermaid
graph TD

Start([Inicio del workflow])
Start --> Clonar[Clonar repositorio]
Clonar --> Modificar[Modificar archivo de fecha]
Modificar --> Commit[Hacer commit]
Commit --> Push[Hacer push al repositorio]
Push --> Fin([Fin del workflow])
```
