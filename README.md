# João Carneiro

Desenvolvo APIs, automações, scrapers e agentes de IA em Python e TypeScript.

Gosto de tirar dados de lugares difíceis e colocar LLMs em sistemas reais, com
as regras críticas no código e não no prompt.

## Projetos

### [atendente-ai](https://github.com/saskuati-dev/atendente-ai)

Agente de atendimento para uma loja de música. Responde sobre catálogo, pedidos
e políticas, e roda com Anthropic, Gemini, OpenAI ou DeepSeek usando a chave de
quem chama.

- Consultas via tools tipadas com SQL parametrizado e conexão somente leitura; o modelo não escreve SQL.
- Regras de negócio (preço promocional, desconto PIX, parcelas, verificação de identidade) no código.
- Loop e adapters próprios, sem framework de agentes.
- Histórico no servidor para o cliente não conseguir forjar resultados de tools.

`Python` · `FastAPI` · `SQLite` · `pytest`

### [Scraping-Nest](https://github.com/saskuati-dev/Scraping-Nest)

Coleta vagas do RemoteOK e do We Work Remotely e expõe numa API autenticada com
interface web para consulta.

- Scraping com Playwright, execuções agendadas pelo n8n.
- Autenticação JWT e controle de acesso por perfil (user e admin).
- Listagem paginada e filtros sobre os dados coletados.
- Ambiente completo em Docker Compose.

`NestJS` · `Playwright` · `PostgreSQL` · `Next.js` · `n8n` · `Docker`

### [bolao-copa-2026](https://github.com/saskuati-dev/bolao-copa-2026)

Bolão da Copa do Mundo com palpites até 20 minutos antes de cada jogo, ranking
e atualização em tempo real.

- Jogos sincronizados a cada 6 horas via GitHub Action (football-data.org).
- Pontuação: 5 pontos pelo placar exato, 3 pelo resultado certo.
- Atualização ao vivo com Supabase Realtime.

`Next.js` · `Supabase` · `TypeScript` · `GitHub Actions` · `Vercel`

## Contato

[LinkedIn](https://www.linkedin.com/in/saskuati/) · [E-mail](mailto:jvferreiracarneiro@gmail.com)
