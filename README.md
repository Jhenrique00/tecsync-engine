# Tecsync Engine

Um projeto em desenvolvimento para conectar processos e transformar tarefas repetitivas em operações mais simples. Novos detalhes serão apresentados conforme a evolução do produto.

## Direção técnica

Aplicação full-stack com **React, TypeScript, Node.js, Express e PostgreSQL**. A implementação reúne edição visual de fluxos, execução de tarefas e acompanhamento de resultados em ambiente local.

O projeto demonstra trabalho em interfaces, APIs, persistência, autenticação, controle de acesso e testes automatizados. Desenvolvido por [João Henrique](https://github.com/Jhenrique00); a evolução pode ser acompanhada no histórico deste repositório.

## Estado atual

Em desenvolvimento. Há implementação para execução local; hospedagem em produção e validação de integrações externas permanecem pendentes. Os testes presentes no código não representam certificação de segurança ou disponibilidade em produção.

Detalhes em desenvolvimento. Mais informações em breve.

## Executar e verificar

Requer Node.js >= 22.13.

```bash
git clone https://github.com/Jhenrique00/tecsync-engine.git
cd tecsync-engine
npm run setup
npm run build
npm start
```

Acesso local: http://127.0.0.1:8000. Testes: `npm run test:unit` e `npm test` (este último utiliza PostgreSQL local).

Consulte o [guia local](docs/USAGE.md) e os [cuidados de atualização](ATUALIZAR-SEM-PERDER-DADOS.txt). Não inclua bancos, contas, credenciais ou arquivos `.env` em publicações.
