# Tecsync Engine — guia local

Projeto em desenvolvimento com React, TypeScript, Node.js e PostgreSQL.

## Execução

Na raiz, execute `npm run setup`, `npm run build` e `npm start`. Requer Node.js >= 22.13. Abra http://127.0.0.1:8000. O servidor atende somente no computador local; tarefas dependem de o processo continuar em execução.

## Cuidados

- Use dados fictícios durante avaliações.
- Mantenha `.env`, dados locais e chaves fora do Git.
- Preserve `.local` e `.env` ao atualizar e mantenha backups protegidos. Perder a chave local impede recuperar as credenciais criptografadas.
- Cadastre credenciais no local dedicado da aplicação; não escreva segredos em campos livres, definições ou exportações de fluxos.
- Integrações externas exigem configuração própria e validação no ambiente de destino. Não exponha o serviço local à internet sem uma revisão de segurança e hospedagem.

## Verificação

`npm run test:unit` executa verificações unitárias; `npm test` utiliza banco local. Não direcione testes para bancos de produção.

Alguns identificadores técnicos anteriores foram preservados por compatibilidade com dados e integrações existentes. Não renomeie tabelas, cabeçalhos ou variáveis de configuração manualmente.

Mais informações em breve.
