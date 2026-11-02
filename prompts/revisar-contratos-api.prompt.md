---
name: revisar-contratos-api
description: Revisión semántica de un contrato OpenAPI con el skill revisar-contratos-api, siempre con GPT-5.6 Terra.
argument-hint: "[ruta del contrato] [rama base opcional] [códigos opcionales, p. ej. R-DATM01, R-GENM02]"
agent: agent
model: GPT-5.6 Terra
tools: ['execute/runInTerminal', 'execute/getTerminalOutput', 'read/readFile']
---
Sigue al pie de la letra las instrucciones de [revisar-contratos-api](../skills/
revisar-contratos-api/SKILL.md) con el contrato, la rama base y los códigos que indique el usuario en este mensaje (si no indica contrato, usa el archivo abierto). Si no indica rama, analiza todo el contrato.