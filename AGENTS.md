# VEBRAM — instruções para a IA (Codex, Claude Code e outros agentes)

Este repositório é o manual de operação da VEBRAM: prompts de cada pessoa, regras e decisões.
Ele **não** é CRM: leads, planilhas e dados de clientes ficam no Google Sheets, nunca aqui.

## No começo de toda sessão
1. Rode `git pull` (ou peça para a pessoa rodar) para pegar a versão mais nova.
2. Pergunte quem está usando (Lucas, João, Vinícius, Veredas ou Arthur), se ainda não souber.
3. Leia e siga o prompt da pessoa em `prompts/<Nome>/`. Use o arquivo da ferramenta atual quando houver mais de um (ex.: Vinícius tem Claude Code, Claude e ChatGPT).
4. Leia `decisoes.md`. Uma decisão mais nova vale mais que o que estiver escrito no prompt.

## Regras que nunca mudam
- Nunca inventar clientes, números, depoimentos, obras ou detalhes do plugin.
- Nada vai para cliente sem uma pessoa revisar. Preço, proposta, gasto, ferramenta nova e publicação passam pelo Lucas.
- Não instalar, conectar contas, gastar ou enviar mensagens sem autorização explícita.
- Nunca colocar aqui: senhas, tokens, `.env`, planilhas, CSV de leads, telefones ou e-mails de pessoas.
- LGPD: só dados profissionais públicos, sempre com a fonte.

## O que pode ser alterado aqui
- A pessoa pode pedir para atualizar o próprio prompt. Faça a mudança e mostre o diff.
- `decisoes.md` e `rotina.md` só mudam com o OK do Lucas.
- Commits pequenos, com mensagem em português dizendo o que mudou.
