# HMENS — Atendimento Integrado (protótipo UX/UI)

## Executar
Requisitos: Node.js 20+ e npm.

```bash
npm install
npm run dev
```

Abra o endereço local indicado pelo Vite (normalmente http://localhost:5173).

Para validar a compilação: `npm run build`.

## Incluído
- Painel operacional e fila priorizada por classificação de risco
- Recepção e abertura de atendimento
- Cadastro e pesquisa de pacientes
- Triagem com sinais vitais e classificação de risco
- Evolução médica e prescrição
- Enfermagem, registro de medicação e desfecho
- Histórico/prontuário e relatórios demonstrativos

## Limitações e segurança
Protótipo de UX/UI com dados fictícios mantidos somente em memória no navegador. Não possui banco de dados, autenticação real, controle de acesso, auditoria, criptografia, assinatura digital, integração, sincronização offline ou backup. Não usar em atendimento real nem inserir dados pessoais ou clínicos reais. Antes de produção, validar protocolos clínicos, segurança, LGPD, requisitos regulatórios, interoperabilidade e continuidade operacional.
