<h1 align="center">Rafael Camillo</h1>

<p align="center">
  <b>Engenheiro de Software Full Stack</b> · React, Node.js e TypeScript · IA em produção
</p>

<p align="center">
  <a href="https://rafaelcamillo.com.br"><img alt="Site" src="https://img.shields.io/badge/rafaelcamillo.com.br-D9480F?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/rf-camillo"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:eurafaelcamillo@gmail.com"><img alt="E-mail" src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://rafaelcamillo.com.br/curriculo-rafael-camillo.pdf"><img alt="Currículo" src="https://img.shields.io/badge/Currículo_(PDF)-10B3B0?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"></a>
</p>

---

## Sobre mim

Há 8 anos construo produto de ponta a ponta, do banco de dados à interface. Entrei como desenvolvedor pleno na [Clarice.ai](https://clarice.ai), uma das primeiras plataformas brasileiras de escrita com IA, e cresci junto com o produto até CTO. Hoje construo a Doclin e a Vassis, dois produtos de IA para saúde em produção.

- 🧠 IA aplicada em produção: LLMs, RAG, function calling, avaliação automatizada e guards contra alucinação
- ⚙️ Full stack com TypeScript: React e Next.js no front, Node.js e NestJS no back
- ☁️ Infraestrutura enxuta no Google Cloud: Cloud Run, Firestore e deploy por GitHub Actions
- 🧪 Qualidade medida: testes em todas as camadas e avaliação automatizada dos agentes de IA

## Experiência

### [Clarice.ai](https://rafaelcamillo.com.br/#case-clarice)

**Pleno → Sênior → Tech Lead → CTO** · 2021 a 2025

Uma das primeiras plataformas brasileiras de revisão e escrita com IA. Entrei como desenvolvedor pleno e cresci junto com o produto até CTO.

- Revisão incremental: só os parágrafos alterados voltam a ser processados, com queda drástica de requisições, custo e latência
- Adoção de LLMs logo no início e criação dos módulos de geração de texto (IA Escritora e IA Editora)
- Revisão híbrida: regras com regex, spaCy e UDPipe trabalhando junto com LLMs
- Liderança do time de engenharia

### [Doclin](https://rafaelcamillo.com.br/#case-doclin)

**Fundador e Engenheiro Full Stack** · 2026

Documentação clínica com IA: escuta a consulta, transcreve em tempo real e gera a documentação, que o médico revisa antes de usar, sem guardar o áudio.

- Transcrição em tempo real por WebSocket, com reconexão e buffer de replay
- Filtro de confiança contra alucinação: trecho duvidoso sai do texto final
- Retenção zero de áudio e arquitetura orientada à LGPD
- Extensão para o Chrome publicada na Web Store

### [Vassis](https://rafaelcamillo.com.br/#case-vassis)

**Fundador e Engenheiro Full Stack** · 2026

Secretária de IA no WhatsApp para clínicas: responde 24 horas, agenda, remarca e cancela conforme a agenda de cada médico, e passa para um humano quando precisa.

- Agente com function calling para agendar, remarcar e cancelar consultas
- Guards, verificação de groundedness e avaliação automatizada com LLM-judge
- WhatsApp Cloud API oficial, Cloud Run e Firestore

## Código aberto

### [brain-mcp](https://github.com/rf-camillo/brain-mcp)

Servidor MCP que dá a agentes de IA acesso seguro a um cofre do Obsidian: o agente consulta o índice antes de abrir as notas, registra decisões no diário e nunca toca nas pastas bloqueadas. As regras ficam no código, não no prompt.

- Oito ferramentas com esquemas de entrada e saída, CLI em JSON e API para uso como biblioteca
- Guardas contra leitura de pastas bloqueadas, escrita fora do permitido, fuga de caminho e gravação de segredos
- TypeScript estrito, 174 testes, camadas garantidas no build e CI em Node 20, 22 e 24

## Stack

**Linguagens e front-end**

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,python,react,nextjs,vite,materialui,html,css" alt="TypeScript, JavaScript, Python, React, Next.js, Vite, MUI, HTML, CSS" />
</p>

**Back-end e bancos**

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,mongodb,postgres,mysql,firebase" alt="Node.js, NestJS, MongoDB, PostgreSQL, MySQL, Firebase" />
</p>

**Cloud e DevOps**

<p>
  <img src="https://skillicons.dev/icons?i=gcp,aws,docker,kubernetes,githubactions,linux,git" alt="Google Cloud, AWS, Docker, Kubernetes, GitHub Actions, Linux, Git" />
</p>

**IA e integrações**

<p>
  <img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge">
  <img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white">
  <img alt="Pinecone" src="https://img.shields.io/badge/Pinecone-1C17FF?style=for-the-badge">
  <img alt="spaCy" src="https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white">
  <img alt="WhatsApp Cloud API" src="https://img.shields.io/badge/WhatsApp_Cloud_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white">
  <img alt="Stripe" src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white">
</p>

**Também já usei**

<p>
  <img alt="Electron" src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white">
  <img alt="React Native" src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img alt="Extensões do Chrome" src="https://img.shields.io/badge/Extensões_do_Chrome-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white">
</p>

---

<p align="center">
  O código da Clarice.ai, da Doclin e da Vassis é privado. Os detalhes de cada projeto estão em <a href="https://rafaelcamillo.com.br">rafaelcamillo.com.br</a>.
</p>
