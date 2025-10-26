# LGPD  

## Contextualização  

A **Lei Geral de Proteção de Dados (LGPD – Lei nº 13.709/2018)** é um pilar essencial na concepção do **Lar Justo**, garantindo que a inovação tecnológica e o uso de **Inteligência Artificial** ocorram de forma **ética, segura e respeitosa à privacidade dos cidadãos**.  
No contexto do **Hackathon Devs de Impacto 2025**, a aplicação da LGPD reforça o compromisso do projeto com a **confiança digital** e com a **inclusão social sem violação de direitos fundamentais**, especialmente no tratamento de dados sensíveis de populações em situação de vulnerabilidade.  

A proposta central do hackathon é **reimaginar o acesso a serviços públicos e direitos sociais** com o auxílio da IA. No entanto, qualquer tecnologia que envolva informações pessoais deve adotar **mecanismos robustos de proteção de dados**.  
Por isso, o **Lar Justo** foi projetado desde o início sob o princípio de **“Privacy by Design”**, ou seja, a proteção de dados é incorporada à arquitetura da solução, não apenas adicionada como camada posterior.  

---

## Princípios Fundamentais Aplicados  

O **Lar Justo** segue todos os princípios da LGPD, com destaque para:  

| **Princípio** | **Descrição** | **Como é Aplicado no Lar Justo** |
|----------------|----------------|----------------------------------|
| **Finalidade** | O tratamento de dados deve ter propósitos legítimos, específicos e informados ao titular. | Os dados são utilizados **apenas** para acompanhamento de casos habitacionais e envio de notificações relacionadas. |
| **Necessidade** | Coleta limitada ao mínimo necessário para a prestação do serviço. | O usuário pode **abrir e acompanhar casos anonimamente**, sem CPF, RG ou endereço pessoal. |
| **Transparência** | O cidadão deve ser informado sobre o uso dos dados. | O sistema exibe **termos de uso e política de privacidade simplificados**, escritos em linguagem acessível. |
| **Segurança** | Proteção contra acesso não autorizado, perda ou vazamento de dados. | Todos os dados são **criptografados** e armazenados em **servidores seguros (Neon + Vercel)**. |
| **Prevenção** | Adoção de medidas para evitar danos ou uso indevido dos dados. | Logs de auditoria e controles internos garantem rastreabilidade e bloqueiam uso indevido. |
| **Não Discriminação** | Nenhum tratamento pode ser utilizado para fins discriminatórios. | A IA é treinada com **prompts éticos e imparciais**, sem inferências sobre gênero, etnia ou renda. |
| **Responsabilização e Prestação de Contas** | O controlador deve comprovar conformidade com a LGPD. | Toda manipulação de dados é **documentada e rastreável**, permitindo auditoria por órgãos parceiros. |

---

## Mecanismos de Segurança e Conformidade  

A arquitetura do **Lar Justo** incorpora múltiplos mecanismos de **proteção de dados e anonimização**, conforme as melhores práticas da LGPD:  

### 🔐 **Proteção e Criptografia de Dados**
- Todos os dados armazenados são **criptografados em repouso e em trânsito (TLS 1.3)**.  
- Nenhum dado sensível (CPF, endereço completo, renda) é obrigatório para uso do sistema.  
- O banco de dados Neon é configurado com **camadas de acesso restrito e controle de logs**.  

### 🕵️ **Anonimização e Minimização**
- Cada caso é identificado por um **ID anônimo gerado automaticamente**, desvinculado de informações pessoais.  
- O sistema coleta apenas o que é **estritamente necessário** para o funcionamento do caso.  

### 🧭 **Consentimento Informado**
- Antes de iniciar o atendimento, o cidadão tem acesso a um **termo de consentimento claro e resumido**, redigido em **linguagem simples e inclusiva (nível A2)**.  
- O consentimento pode ser **revogado a qualquer momento**, conforme o art. 8º da LGPD.  

### 🧠 **Governança Ética de IA**
- A IA opera com **prompts revisados por critérios éticos e sociais**, impedindo interpretações discriminatórias ou sensíveis.  
- Todos os modelos de IA utilizados (GPT-4o e GPT-4o-mini) são **controlados via API**, sem armazenamento permanente de dados pessoais.  

### 🧾 **Registro e Auditoria**
- O sistema mantém **logs auditáveis e protegidos**, permitindo rastrear quem acessou ou modificou qualquer dado.  
- O acesso administrativo é controlado por **autenticação multifator e perfis hierarquizados**.  

---

## Direitos do Usuário Garantidos  

O **Lar Justo** assegura que cada cidadão, enquanto titular de dados, tenha pleno exercício dos seus direitos previstos na LGPD:  

| **Direito** | **Descrição** | **Como é Assegurado** |
|--------------|----------------|-----------------------|
| **Acesso** | O usuário pode consultar quais informações estão armazenadas. | Disponibilização de painel simplificado com histórico e dados básicos. |
| **Correção** | Permite atualizar ou ajustar dados incorretos. | O usuário pode solicitar revisão via canal de suporte. |
| **Anonimização e Exclusão** | Remoção de dados pessoais mediante solicitação. | O sistema possui botão de **“Excluir meus dados”** direto no painel. |
| **Revogação do Consentimento** | Interromper o uso dos dados a qualquer momento. | Processo automático via interface, sem necessidade de contato humano. |

---

## Conformidade Legal e Ética  

O **Lar Justo** não apenas cumpre a LGPD, como adota práticas de **governança ética da IA**, alinhadas a diretrizes internacionais de proteção de dados e direitos humanos digitais (como a OCDE e a União Europeia – GDPR).  

- **Privacidade desde a concepção (Privacy by Design)**: todos os fluxos são criados com segurança integrada.  
- **Privacidade por padrão (Privacy by Default)**: o sistema sempre opta pela coleta mínima de dados.  
- **Acesso restrito e transparente**: apenas agentes autorizados (instituições parceiras) podem visualizar casos específicos.  
- **Política de uso ético da IA**: a IA é projetada para **não tomar decisões autônomas críticas**, mas sim **assistir e orientar o cidadão**.  

---

> **Em essência, o Lar Justo entende que proteger dados é proteger pessoas.**  
A LGPD não é apenas uma exigência legal, mas um **compromisso ético e social** com os cidadãos atendidos — garantindo que cada interação digital preserve a **dignidade, privacidade e segurança** de quem mais precisa.
