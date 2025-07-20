
# 📁 Automação de Downloads por E-mail – Rovema Energia

### 🛠 Projeto real desenvolvido para automatizar processos internos da empresa Rovema Energia.

---

## 🔍 Descrição

Este sistema realiza o download automático de **boletos bancários, notas fiscais (PDF)** e **arquivos XML** diretamente da caixa de entrada do e-mail da empresa, filtrando os arquivos por **data selecionada**, separando por tipo e armazenando em **pastas específicas**, com compactação em arquivos `.zip`.

A ferramenta foi construída com **Python**, utilizando `imaplib` para conexão segura ao e-mail via IMAP, e possui uma **interface HTML amigável** integrada ao **Google Colab**, permitindo que qualquer usuário com permissão consiga interagir de forma simples.

---

## 🚀 Funcionalidades

- 🔐 Login automático em servidor IMAP
- 📅 Filtro por data (busca e-mails recebidos em uma data específica)
- 📎 Download de anexos PDF e XML
- 📂 Organização automática em pastas:
  - /Boletos
  - /Notas Fiscais
  - /XMLs
- ?? Compressão dos arquivos em ZIP para download
- 🖥 Interface HTML responsiva (Google Colab)

---

## 💻 Tecnologias utilizadas

- Python 3
- imaplib, email, zipfile, datetime
- Google Colab
- HTML + CSS + JavaScript (frontend leve embutido)
- Google Colab Callback API

---

## 📦 Estrutura de pastas geradas

```
📁 Boletos/
📁 Notas Fiscais/
📁 XMLs/
📦 Boletos.zip
📦 Notas Fiscais.zip
📦 XMLs.zip
```

---

## 📈 Impacto

✅ Reduziu drasticamente o tempo de operação manual do setor administrativo  
✅ Garantiu padronização na organização de documentos  
✅ Eliminou erros humanos no manuseio de boletos e notas fiscais  
✅ Interface simples que exige **zero conhecimento técnico**

---

## 📸 Interface


---

## 👤 Desenvolvedor

**DARLLAN BARBA**  
🐱 [GitHub](https://github.com/darllanbn)  
📧 Email: darllanbarba15@gmail.com

---

## 📄 Licença

Este projeto foi desenvolvido como ferramenta interna da empresa **Rovema Energia**, com autorização para ser demonstrado como parte do portfólio do autor.

