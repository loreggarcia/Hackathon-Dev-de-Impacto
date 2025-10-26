# Arquitetura da Solução  

## Contexto  

A arquitetura do **Lar Justo** foi projetada para unir **eficiência técnica**, **simplicidade operacional** e **acessibilidade social**, permitindo o desenvolvimento rápido de um **MVP funcional em 12 horas**, com capacidade de expansão e manutenção a longo prazo.  
A estrutura prioriza o uso de **tecnologias open source**, **IA integrada** e **design inclusivo**, garantindo um sistema robusto, escalável e ético.  

A solução foi construída como um **monólito inteligente** (full-stack), que integra frontend, backend e lógica de IA em um único código-base. Essa decisão acelera o desenvolvimento, reduz custos e facilita a interoperabilidade entre os componentes, mantendo **baixa complexidade e alta consistência**.  

---

## Arquitetura Geral  

A arquitetura do **Lar Justo** segue o modelo **serverless modular**, com foco em:  

- **Baixo custo operacional** (deploy automático em nuvem);  
- **Integração nativa com IA (OCR, RAG, TTS, STT)**;  
- **Persistência segura e vetorizada de dados**;  
- **Interface responsiva e inclusiva**;  
- **Escalabilidade horizontal** para múltiplos municípios.  

---

## Stack Tecnológica  

| **Camada** | **Tecnologia** | **Função Principal** |
|-------------|----------------|----------------------|
| **Frontend** | Next.js 15 + React + Tailwind + shadcn/ui | Interface responsiva, acessível e mobile-first. |
| **Backend** | Next.js API Routes + Server Actions | Processamento da lógica de negócios e integração de IA. |
| **Banco de Dados** | PostgreSQL (Neon) + Prisma ORM | Armazenamento estruturado de dados e vetores semânticos. |
| **IA (NLP e Visão)** | OpenAI GPT-4o / GPT-4o-mini | OCR, classificação de documentos, geração de texto e voz. |
| **Vetorização** | pgvector (Postgres extension) | Busca semântica e contextualização via RAG. |
| **Deploy / Infra** | Vercel (frontend e backend) + Neon Cloud | Ambiente serverless com CI/CD automático. |
| **Autenticação** | ID de caso anônimo / NextAuth (futuro) | Identificação segura e simples do cidadão. |
| **Áudio (voz)** | Web Speech API (STT) + OpenAI TTS | Entrada e saída de voz para acessibilidade. |
| **Notificações** | Webhooks + Telegram / e-mail | Lembretes automáticos e acompanhamento de prazos. |
---


