<h1 align="center">Gabriel Ribeiro de França</h1>

<p align="center">
  <b>Desenvolvedor full-stack</b> · Aplicativos para desktop, mobile e web
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron" />
  <img src="https://img.shields.io/badge/Tauri-24C8DB?style=for-the-badge&logo=tauri&logoColor=black" alt="Tauri" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=black" alt="Supabase" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API" />
</p>

---

## 🚀 Sobre

Cresci dentro de uma hamburgueria. Desde os 10 anos trabalho na **Lau Burguer**,
o negócio da minha família, e aos 12 comecei a programar — as duas coisas nunca
andaram separadas. Três dos projetos aqui nasceram de problemas que eu via
acontecer no balcão: a planilha de 488 abas do fechamento de caixa, os três
painéis de delivery abertos ao mesmo tempo, o bolão anotado no papel.

Entrego o produto inteiro — interface, banco de dados, regras de acesso,
integração com API externa e o empacotamento final, seja um `.exe`, um APK ou um
site no ar. TypeScript na maior parte, com Electron, Tauri e Capacitor quando
precisa sair do navegador.

O resto nasce de curiosidade mesmo — uma assistente de IA que roda na minha
própria máquina, um jogo multiplayer de dedução. Aprendo em público: todo
repositório aqui é um projeto que eu uso ou usei de verdade.

Ainda não trabalhei como desenvolvedor: cada projeto aqui nasceu de uma
necessidade minha ou de uma vontade de construir. **Busco a primeira
oportunidade na área.**

---

## 🤖 Engenharia de agentes

Não é só pedir código para a IA. Construo os sistemas que fazem um agente
funcionar: definição de ferramentas, laço de orquestração, memória e limite de
ação.

<p align="center">
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/ChatGPT-412991?style=for-the-badge&logo=openai&logoColor=white" alt="ChatGPT" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini" />
  <img src="https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge&logo=deepseek&logoColor=white" alt="DeepSeek" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/LM_Studio-4A29B8?style=for-the-badge" alt="LM Studio" />
</p>

[**S.T.O.R.M.Y**](https://github.com/biielFranca/S.T.O.R.M.Y) é onde isso está por
inteiro — ~6.000 linhas de Python, sendo 1.025 só no laço de orquestração:

| | |
|---|---|
| 🧰 **16 ferramentas** | cada uma com `input_schema` JSON — controle do PC, leitura de tela, Spotify, WhatsApp, busca web, descoberta de API |
| 🔀 **Roteamento entre modelos** | um modelo local classifica a intenção e devolve JSON estruturado; só o que precisa de dado externo escala para a nuvem com ferramentas — latência e custo baixos no caso comum |
| 🧠 **Contexto gerenciado** | histórico podado por limite, resultados de ferramenta reinjetados no laço, memória persistida e sincronizada entre PC e celular |
| 🛡️ **Limite de ação** | ação destrutiva não executa direto: o agente propõe e só roda após confirmação explícita |


**A primeira vez foi fora de um cargo técnico.** Como jovem aprendiz de
administração, percebi uma etapa do processo que dava para conferir
automaticamente e escrevi agentes verificadores para o time. Ninguém pediu e não
era minha função — era um problema que estava na minha frente todo dia.

Também escrevi, por diversão, um harness em Python para orquestrar tarefas
diárias, sob medida para uma necessidade bem específica. O HD corrompeu e o
código se perdeu inteiro — não sobrou repositório para mostrar, mas foi onde eu
mexi pela primeira vez no laço de orquestração em vez de só chamar a API.

**No desenvolvimento**, agente é meu método principal — com biblioteca de prompts
por tipo de tarefa (hardening de segurança, testes, code review, migrations) e
documentação viva que o agente lê antes de escrever código.

E a revisão é minha: foi assim que encontrei e corrigi um RLS que liberava dado
que não devia. O agente acelera; entender o que entra no commit continua sendo
meu trabalho.

---

## 🏆 1º lugar — 2ª Hackathon da Mobilização Popular

<p align="center">
  <img src="https://img.shields.io/badge/1%C2%BA_lugar_geral-FFD700?style=for-the-badge&logoColor=black" alt="1º lugar geral" />
  <img src="https://img.shields.io/badge/junho_de_2026-24292F?style=for-the-badge" alt="junho de 2026" />
</p>

**[Veracity](https://github.com/cb-hackathon/CODEBOYS_VERACITY)** — plataforma
open source de combate à desinformação, construída em um fim de semana com a
equipe CodeBoys. **Fui responsável por toda a integração de IA com o site**,
atuei no front-end e apresentei o projeto à banca avaliadora.

Três pilares — detectar, educar e prevenir: hub de checagem que analisa links,
textos e imagens com IA a partir de fontes confiáveis; mapa de calor da
desinformação regionalizado por estado; quiz gamificado de letramento digital.

<img src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" /> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" /> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" /> <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />

<sub>Promovida pela UEE-SP e pelo Centro de Estudos da Mídia Alternativa Barão de Itararé.</sub>

---

## 💼 Projetos

### 💰 [Minhas Finanças](https://github.com/biielFranca/minhas-financas)
**Windows e Android com a mesma base de código.** Puxa extratos, cartões e
investimentos direto dos bancos pela API do Pluggy (Open Finance) e sincroniza
sozinho a cada 6 horas, com o aplicativo fechado.

O segredo do banco fica no Vault do Supabase e o app não consegue lê-lo de volta.
Regras por linha em 18 tabelas.

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" /> <img src="https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white" /> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black" /> <img src="https://img.shields.io/badge/Open_Finance-00A868?style=flat-square" />

### 🧾 [Fechamento de Caixa](https://github.com/biielFranca/caixa)
**Substituiu uma planilha de 488 abas.** Fechamento diário e folha de pagamento
da lanchonete, com os 10.570 lançamentos históricos migrados sem perder nada.

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black" />
&nbsp;[![Ao vivo](https://img.shields.io/badge/▶_ver_ao_vivo-0A66C2?style=flat-square)](https://caixa-lyart.vercel.app)

### 🍔 [Hamburgueria Dispatch](https://github.com/biielFranca/hamburgueria-dispatch)
**Um painel no lugar de três.** Junta os pedidos do iFood, Keeta e 99Food numa
tela só, classifica automaticamente, despacha os motoboys e mostra as entregas
no mapa. Aplicativo nativo de Windows via Tauri 2.

<img src="https://img.shields.io/badge/Tauri_2-24C8DB?style=flat-square&logo=tauri&logoColor=black" /> <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" /> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black" />

### 👕 [Thailândia Store](https://github.com/biielFranca/thailandia_store)
**Loja online completa** de camisas de futebol importadas: catálogo, carrinho,
checkout com PIX e cartão pelo Mercado Pago e e-mails transacionais.

<img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black" /> <img src="https://img.shields.io/badge/Mercado_Pago-00B1EA?style=flat-square&logo=mercadopago&logoColor=white" />
&nbsp;[![Ao vivo](https://img.shields.io/badge/▶_ver_ao_vivo-0A66C2?style=flat-square)](https://thailandia-store.vercel.app)

### ⚽ [Bolão da Copa](https://github.com/biielFranca/bolao-copa)
**Bolão da Copa do Mundo para a lanchonete.** Login por celular, palpites com
trava de horário, ranking automático e painel de administração.

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black" />
&nbsp;[![Ao vivo](https://img.shields.io/badge/▶_ver_ao_vivo-0A66C2?style=flat-square)](https://bolao-copa-six.vercel.app)

### ⛈️ [S.T.O.R.M.Y](https://github.com/biielFranca/S.T.O.R.M.Y)
**Assistente de IA híbrida, local e na nuvem.** Um classificador de três camadas
decide se a resposta vem do modelo na própria máquina ou da API da Claude.
Controla o PC, o Spotify, busca na web e analisa a tela.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" /> <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" /> <img src="https://img.shields.io/badge/LM_Studio-4A29B8?style=flat-square" />

---

<p align="center">
  <a href="mailto:biel.ribeirofranca@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://www.linkedin.com/in/gabriel-ribeiro-de-fran%C3%A7a/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>
