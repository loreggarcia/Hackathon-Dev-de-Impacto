# Inteligência Artificial  

## Contextualização  

A **Inteligência Artificial (IA)** é o núcleo estratégico do projeto **Lar Justo**, atuando como o elo entre o cidadão e os serviços públicos de forma **acessível, empática e orientada por dados**.  
No contexto do **Hackathon Devs de Impacto 2025**, a utilização da IA vai além da inovação tecnológica — ela é uma **ferramenta de justiça social**, voltada a **reimaginar o acesso aos direitos habitacionais** e **reduzir barreiras de exclusão digital e burocrática**.  

O desafio central do hackathon é **“traduzir a complexidade do sistema de assistência social em uma ferramenta simples e digna”**, e é exatamente nesse ponto que a IA se torna essencial: ela **interpreta, simplifica e acompanha** cada caso de forma personalizada, transformando processos frios e técnicos em **experiências humanas e compreensíveis**.  

A IA do **Lar Justo** foi desenhada sob três princípios fundamentais:  
1. **Empatia Digital** – a tecnologia deve acolher e não afastar.  
2. **Transparência e Ética** – decisões explicáveis e baseadas em dados abertos e auditáveis.  
3. **Acompanhamento Contínuo** – a IA não apenas responde, mas **caminha junto** com o cidadão até o desfecho do caso.  

---

### O Papel da IA no Projeto  

A IA é responsável por **traduzir, classificar e orientar** o cidadão em todas as etapas do processo habitacional.  
Ela funciona como um **representante digital de direitos**, integrando visão computacional, processamento de linguagem natural (NLP) e aprendizado contextual.  

| **Função da IA** | **Descrição** | **Impacto Social** |
|------------------|----------------|--------------------|
| **OCR (Reconhecimento Óptico de Caracteres)** | Lê documentos e notificações, convertendo imagens em texto legível. | Permite que cidadãos sem letramento jurídico entendam o conteúdo de notificações oficiais. |
| **Classificação de Casos** | Identifica automaticamente o tipo de problema (despejo, área de risco, regularização). | Reduz a dependência de conhecimento técnico e direciona o cidadão ao fluxo correto. |
| **Geração de Documentos Automáticos** | Cria cartas, requerimentos e petições personalizadas. | Garante autonomia e agilidade ao cidadão para agir. |
| **Chat Multiagente Empático** | Quatro agentes (jurídico, social, provas e acompanhamento) com perfis distintos orientam o usuário. | Cria um diálogo humanizado, que substitui a linguagem fria da burocracia. |
| **RAG (Retrieval-Augmented Generation)** | Usa vetores e contexto local (leis, programas e políticas públicas) para respostas precisas. | Evita erros e oferece informações contextualizadas para cada município. |
| **TTS/STT (Texto e Fala)** | Transforma voz em texto e texto em fala. | Inclui pessoas com baixa alfabetização ou deficiência visual. |
| **Acompanhamento Ativo** | A IA monitora prazos, status e ações pendentes. | Evita o abandono do processo e promove continuidade no atendimento. |

---

### Tecnologias Empregadas  

O sistema de IA do **Lar Justo** é composto por tecnologias modernas e integradas, com arquitetura modular e responsiva:  

| **Camada** | **Tecnologia** | **Função Principal** |
|-------------|----------------|----------------------|
| **IA Central (NLP e Visão)** | OpenAI GPT-4o / GPT-4o-mini | OCR, geração de texto, análise e respostas empáticas. |
| **Vetorização** | pgvector (PostgreSQL extension) | Busca semântica e contextualização via RAG. |
| **Banco de Dados** | PostgreSQL (Neon) + Prisma ORM | Armazenamento estruturado e vetorizado de informações. |
| **Backend de Integração** | Next.js API Routes + Server Actions | Conexão entre IA, banco de dados e frontend. |
| **Frontend Acessível** | Next.js 15 + React + Tailwind + shadcn/ui | Interface inclusiva com suporte a voz e mobile. |
| **Áudio (voz)** | Web Speech API (STT) + OpenAI TTS | Entrada e saída de voz com empatia e acessibilidade. |
| **Deploy / Infraestrutura** | Vercel + Neon Cloud | Execução serverless, CI/CD e alta disponibilidade. |

---

### Inteligência Artificial com Propósito Social  

Diferente de aplicações comerciais, a IA do **Lar Justo** tem como objetivo principal **gerar dignidade e acesso**, não apenas eficiência.  
Ela representa uma **ponte entre o cidadão vulnerável e os serviços públicos**, atuando em três dimensões de impacto:  

1. **Cognitiva** – traduz documentos e leis em linguagem compreensível.  
2. **Operacional** – guia o usuário passo a passo até o fim do processo.  
3. **Emocional** – comunica-se com empatia, transmitindo acolhimento e segurança.  

A IA aprende e se adapta às **condições sociais, linguísticas e regionais** do usuário, tornando-se mais sensível a contextos reais como sotaques, expressões populares e limitações de leitura.  

---

### Futuro da IA no Lar Justo  

A evolução da IA no **Lar Justo** seguirá um caminho de **humanização e ampliação de alcance**, com as seguintes metas:  

- **Interação Multimodal Completa:** inclusão de **vídeo chamada com IA**, capaz de interpretar expressões e gestos para aumentar a inclusão comunicacional.  
- **IA Preditiva e Proativa:** antecipar prazos e sugerir soluções antes que o problema se agrave.  
- **IA Cívica e Comunitária:** integração com dados abertos de políticas públicas e mapeamento de vulnerabilidades habitacionais.  
- **Aprendizado Ético e Local:** personalização da IA para cada região, respeitando costumes, idioma e contexto social.  

---

> **Em essência, a IA do Lar Justo é mais do que uma tecnologia — é uma extensão da empatia humana no mundo digital.**  
Ela democratiza o acesso à moradia, converte complexidade em clareza e transforma a inteligência artificial em uma **inteligência socialmente justa**.  
