# 🧠 Assistente de Finanças – Criptomoedas & Forex

Um assistente financeiro inteligente criado com **n8n**, **LangChain**, **Groq Llama-4**, e integrações de dados em tempo real para **criptomoedas** e **Forex**.

Este projeto entrega um agente capaz de:

- Fornecer análises de mercado atualizadas  
- Consultar preços de criptomoedas via API  
- Buscar cotações de moedas (USD/BRL, EUR/BRL, GBP/BRL)  
- Interpretar contexto macroeconômico  
- Explicar cenários prováveis com base em dados reais  
- Manter memória de curto prazo durante a conversa  

Ideal como base para **assistentes financeiros**, **consultorias automatizadas**, **bots de análise**, ou **ferramentas internas de estudo de mercado**.

---

## 🚀 Tecnologias Utilizadas

### **⚙️ Core**
- **n8n** — automação e orquestração do fluxo
- **LangChain Agent** — integração entre modelo e ferramentas
- **Groq Llama-4 Maverick 17B** — LLM utilizado para geração de respostas
- **Memory Buffer Window** — memória contextual de 20 mensagens

### **📡 APIs Integradas**
- **CoinGecko API** → preços de criptomoedas (BTC/USD e BTC/BRL)  
- **AwesomeAPI (Economia)** → cotações Forex em tempo real:  
  - USD/BRL  
  - EUR/BRL  
  - GBP/BRL  

---

## 🧩 Estrutura do Workflow

### **1. Chat Trigger**
Inicia a conversa e exibe a mensagem de boas-vindas da assistente:

> “Olá, aqui é a Tairine. Sou sua assistente financeira especialista, preparada para apoiar você com análises de criptomoedas, Forex e macroeconomia. Como posso te ajudar hoje?”

### **2. Agente de IA (LangChain Agent)**
Configuração avançada com instruções para:

- Análise de cripto, Forex, macroeconomia, volatilidade e liquidez  
- Interpretação de fundamentos e cenários probabilísticos  
- Avaliação de risco  
- Linguagem clara, estruturada e embasada  
- **Sem recomendações diretas de compra ou venda**  
- Aviso constante:  
  *“Isso não é aconselhamento financeiro profissional.”*

### **3. Modelo LLM (Groq)**
Processamento ultrarrápido usando **Llama-4 Maverick 17B** via Groq.

### **4. Memória**
Armazena as últimas 20 mensagens para manter contexto nas conversas.

### **5. Ferramentas API**
- **CoinGecko** → preços de BTC  
- **AwesomeAPI** → cotações de Forex em BRL  

---

## 📊 Funcionalidades

- 📈 **Preços instantâneos (Criptos & Forex)**  
- 🔍 **Análises probabilísticas e contextualizadas**  
- 🧭 **Interpretação macroeconômica**  
- 🧠 **Memória contextual inteligente**  
- 💬 **Respostas claras e educacionais**  
- 🛡️ **Orientação em gestão de risco**  

---

## 📁 Estrutura do Repositório


---

## 🛠️ Como usar este fluxo no n8n

1. Abra seu n8n  
2. Vá em **Workflows → Import**  
3. Cole o JSON deste repositório  
4. Configure suas credenciais:  
   - **Groq API Key**  
   - (Opcional) Ajuste de limites das APIs públicas  
5. Ative o workflow  
6. Acesse o Webhook gerado → seu assistente estará online 🚀

---

## 📝 Aviso Importante

Este projeto fornece **análises e interpretações de mercado**, mas **não substitui aconselhamento financeiro profissional**.  
Decisões financeiras devem ser tomadas com autonomia e cautela.

---

## 📬 Autor

**Fabricio Lopes**  
Desenvolvedor • IA • Automação • 

---
