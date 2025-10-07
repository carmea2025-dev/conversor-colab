# 🧩 Conversor BPA – Google Colab

Este projeto realiza a conversão automática do arquivo **“PLANO DE AÇÃO - BPA.xlsx”** para o formato final **“PLANO DE AÇÃO - BPA - FINAL.xlsx”**, seguindo as regras definidas em **“Mapeamento_Colunas.xlsx”**.

O notebook foi otimizado para rodar no **Google Colab**, com **interface interativa** (botões para upload, conversão e reinício).

---

## 🚀 Como usar no Google Colab

### 1️⃣ Acesse o notebook
Abra o notebook diretamente pelo Colab:  
👉 [Abrir no Google Colab](https://colab.research.google.com/github/carmea2025-dev/conversor-colab/blob/main/Conversor_BPA_Com_Botoes.ipynb)

---

### 2️⃣ Faça o upload dos arquivos necessários
Na interface do notebook, use o **botão “📂 Upload de Arquivos”** e envie:

- `PLANO DE AÇÃO - BPA.xlsx` → Arquivo original a ser convertido  
- `Mapeamento_Colunas.xlsx` → Contém o mapeamento entre colunas de entrada e saída  

> 💡 Ambos os arquivos já estão disponíveis no repositório. Caso queira testar localmente, basta baixá-los e reenviá-los pelo botão.

---

### 3️⃣ Clique em **“⚙️ Converter Arquivo”**
O script irá:
- Ler o arquivo `PLANO DE AÇÃO - BPA.xlsx`;
- Aplicar as regras de conversão com base no `Mapeamento_Colunas.xlsx`;
- Gerar automaticamente o arquivo final `PLANO DE AÇÃO - BPA - FINAL.xlsx`.

---

### 4️⃣ Baixe o resultado
Após o processamento, será exibido automaticamente o **botão de download**  
para baixar o arquivo convertido.

---

### 5️⃣ (Opcional) Clique em **“🔄 Reiniciar”**
Use este botão para limpar tudo e iniciar um novo processo de conversão.

---

## 📂 Estrutura do repositório

```
conversor-colab/
│
├── Conversor_BPA_Com_Botoes.ipynb   # Notebook principal com interface interativa
├── Mapeamento_Colunas.xlsx          # Regras de mapeamento entre colunas
├── PLANO DE AÇÃO - BPA.xlsx         # Arquivo de entrada (modelo)
├── PLANO DE AÇÃO - BPA - FINAL.xlsx # Arquivo de saída (modelo)
└── README.md                        # Este guia
```

---

## ⚙️ Tecnologias utilizadas
- **Python 3**
- **Pandas**
- **IPython Widgets (interatividade no Colab)**
- **Google Colab**

---

## 🧠 Observação
O notebook foi projetado para uso direto no Google Colab, sem necessidade de instalação local.  
A conversão é automática e o processo é totalmente visual e intuitivo.
