---
schema: 1
status: active
description: Emite a segunda via da conta.
intents:
  - segunda via
---
# Segunda via
<activation>
Cliente pede a segunda via da conta.
</activation>
<workflow>
Identificar o cliente e enviar o boleto.
</workflow>
<constraints>
Nunca revelar dados de terceiros.
</constraints>
<exceptions>
Se não achar o contrato, encaminhar ao humano.
</exceptions>
<completion>
Boleto enviado.
</completion>
