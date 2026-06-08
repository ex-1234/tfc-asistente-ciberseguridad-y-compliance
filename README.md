# Auditor de Compliance IA

## Estructura del Repositorio

El proyecto se organiza de la siguiente manera:

* `documentacion/`: Contiene la documentación técnica y de soporte, incluyendo el Trabajo de Fin de Curso (TFC).
* `flujos/`: Definiciones en formato JSON de los flujos de trabajo para los agentes de auditoría.
* `normativa/`: Archivos de normativa para alimentar el agente.
* `prompts/`: Biblioteca de prompts optimizados para los distintos roles del sistema.

## Descripción de Componentes

### Flujos (Workflows)
Los archivos en `flujos/` definen la lógica de interacción de los agentes:
* `chatbot-auditor-compliance-agente.json`: Lógica del agente de auditoría principal.
* `chatbot-auditor-compliance-rag.json`: Flujo diseñado para la recuperación y aumento de información (RAG).

### Biblioteca de Prompts
Los archivos en `prompts/` contienen las instrucciones de sistema y usuario:
* **Roles:** `agentecompliance.md`, `agentecompliance_user.md`, `agentepr.md`.
* **Utilidades:** `clasificador.md` (clasificador de documentos), `cortesia.md` (saludos, despedidas y agradecimientos), `portero.md` (filtrado de intencionalidad).
