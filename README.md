## Diego de Moraes

Estudante de Análise e Desenvolvimento de Sistemas, com foco em **dados e automação**. Construo e mantenho em produção os sistemas da [Allaska](https://allaska.com.br), minha agência de software para negócios locais: pipelines de coleta e enriquecimento de dados, bots de WhatsApp, scraping com Playwright e sites com 3D em tempo real.

Gosto de problema concreto: dado que não tem API, processo manual que dá para automatizar, página que precisa carregar rápido no celular de quem vai comprar.

### Dados e automação

| Projeto | O que resolve | Stack |
|---|---|---|
| [radar-dt](https://github.com/euudm/radar-dt) · [demo](https://radar-dt-matriz-avisos.netlify.app) | Painel de priorização de cargas paradas num centro de fulfillment: cruza tempo de retenção (dwell time) com horário de saída do caminhão (CPT) e classifica cada unidade em 4 níveis de urgência | HTML, JavaScript |
| [Allaska](https://github.com/euudm/Allaska) | Pipeline de prospecção: busca empresas no Google Maps e na biblioteca de anúncios da Meta, enriquece com site, Instagram e contato, deduplica entre operadores e dispara mensagens agendadas | Python, Flask, Playwright |
| [rastreamento-concorrentes](https://github.com/euudm/rastreamento-concorrentes) | Coleta semanal de dados de concorrentes (Maps, site, Instagram), compara com a semana anterior e alerta só quando algo muda | Node.js, Playwright, Apify |
| [leads-b2b](https://github.com/euudm/leads-b2b) | Qualifica empresas por CNPJ na API pública da Receita, filtra por capital social e exporta para Excel | Python, pandas, rich |
| [crm-allaska](https://github.com/euudm/crm-allaska) | Kanban de vendas que recebe sozinho os leads que responderam no WhatsApp, sem duplicar nem desfazer o que foi movido à mão, e abre as outras ferramentas da agência | Node.js, Express |
| [avaliabot](https://github.com/euudm/avaliabot) | Bot de WhatsApp que pede nota após o atendimento e só envia o link de avaliação do Google para quem deu 4 ou 5 | Node.js, Express, Baileys |

### Front-end e 3D

| Projeto | O que resolve | Stack |
|---|---|---|
| [fabrica-nicho](https://github.com/euudm/fabrica-nicho) · [exemplo](https://zangief-team.tayson-team.workers.dev) | Gerador de landing pages a partir de config por cliente, com conferência automática em Chrome headless; **20 sites de academias no ar** | JavaScript, Node.js, GSAP, Pillow |
| [allaska-site](https://github.com/euudm/allaska-site) · [no ar](https://allaska.com.br) | Site da agência: o logo vira um prisma de vidro 3D que divide a luz nas 6 soluções, com versão de celular própria (giroscópio, snap por seção) | React, TypeScript, React Three Fiber |
| [ferrum-serralheria](https://github.com/euudm/ferrum-serralheria) · [no ar](https://ferrum-serralheria.netlify.app) | One-page com portão 3D procedural montado pelo scroll, com gerenciador de renderização para manter a performance | React, TypeScript, Three.js |
| [systema-araujo](https://github.com/euudm/systema-araujo) | Redesign de site de instrutor usando o material dele: medalhão em WebGL, anel que respira com a rolagem e questionário em 7 etapas | JavaScript, Three.js, GSAP |
| [nacar-atelier](https://github.com/euudm/nacar-atelier) | Site de clínica odontológica com dente 3D em camadas, gerado a partir de um JSON por clínica | JavaScript, Three.js, Vite |

### Ferramentas

**Dados e back-end:** Python, pandas, Node.js, Express, Flask, APIs REST
**Automação e coleta:** Playwright, Apify, WhatsApp Web (Baileys), Chrome DevTools Protocol, agendamento com cron e Task Scheduler
**Front-end:** JavaScript, TypeScript, React, Three.js, React Three Fiber, GSAP, Tailwind, Vite
**Infra:** Git, Netlify, Cloudflare Workers, Railway, Supabase

### Agora

Estudando engenharia de dados: modelagem, SQL e pipelines (exercícios em [estudos-python-logica](https://github.com/euudm/estudos-python-logica)).

[LinkedIn](https://www.linkedin.com/in/euudm) · São Paulo, Brasil
