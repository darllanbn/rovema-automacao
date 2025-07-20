# 📁 Automação de Processos com Python e Google Apps Script – Rovema Energia

### 🛠 Projetos reais desenvolvidos para automatizar tarefas administrativas e fiscais na Rovema Energia, integrando e-mails, arquivos XML e planilhas inteligentes.

---

## 🔍 Descrição Geral

Este repositório contém dois módulos principais de automação criados para a Rovema Energia:

1. **Automação de E-mails e Downloads de Arquivos com Python (Colab)**
2. **Leitura e Preenchimento Automático de Planilhas a partir de XMLs (Apps Script)**

Ambos os sistemas foram projetados para reduzir o trabalho manual, evitar erros humanos e padronizar a gestão de documentos fiscais.

---

## 📦 Módulo 1 – Automação de E-mails e Download de Anexos (Python)

### 🔧 O que faz:

- Conecta automaticamente à conta de e-mail institucional via IMAP
- Busca e-mails recebidos em uma data específica
- Baixa arquivos anexos PDF e XML
- Classifica por tipo (Boletos, Notas Fiscais, XMLs)
- Organiza os arquivos em pastas específicas
- Compacta os arquivos por tipo (ZIP)
- Permite download direto via interface HTML em Colab

### 🧪 Tecnologias usadas:

- Python 3
- imaplib, email, zipfile, datetime
- Google Colab
- HTML + JS (formulário dinâmico)
- Google Colab Callback API

---

## 🧩 Módulo 2 – Leitura de XMLs e Preenchimento de Planilhas (Apps Script)

### 🔧 O que faz:

- Acessa automaticamente uma pasta no Google Drive
- Lê arquivos XML e extrai dados fiscais com regex:
  - Número da Nota (nNF)
  - Data de Emissão (dhEmi ou dEmi)
  - Valor Total dos Produtos (vProd)
  - Quantidade (qCom)
  - Valor Unitário (vUnCom)
- Preenche dinamicamente uma planilha Google Sheets
- Formata os dados, ordena por data e aplica totais

### 🧪 Tecnologias usadas:

- Google Apps Script
- Google Drive API
- Google Sheets API
- Regex para XML

---

## 📈 Impacto

✅ Redução de mais de 90% do tempo de processamento manual de documentos  
✅ Eliminação de erros humanos na leitura e digitação de dados  
✅ Padronização e digitalização do processo de gestão fiscal  
✅ Ferramentas acessíveis para qualquer colaborador com acesso à conta Google da empresa

---

## 👨‍💻 Desenvolvedor

**Darllan Barba**  
🐱 [GitHub](https://github.com/darllanbn)  
📧 darllanbarba15@gmail.com

---

## 📝 Licença

Projeto desenvolvido para uso interno na Rovema Energia. Divulgado com fins de portfólio técnico com autorização do autor.
