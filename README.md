# 🖋️ Microserviço Java para Assinatura Digital (PAdES)

Microserviço RESTful em **Java + Spring Boot**, utilizando a biblioteca open-source **DSS (Demselle)** para realizar **assinatura digital em arquivos PDF** no padrão **PAdES** (PDF Advanced Electronic Signatures).

---

## 🚀 Objetivo

Fornecer uma **solução gratuita, segura e pronta para produção** para assinatura digital de documentos, evitando custos com bibliotecas pagas como o iText.

---

## 🛠️ Tecnologias Utilizadas

- Java 21
- Spring Boot
- DSS (Digital Signature Services - Demselle)
- Maven

---

## 📌 Funcionalidades

- 🔐 Assinatura digital com certificados A1 (arquivo `.pfx`) ou A3 (token);
- 🧾 Geração de PDFs assinados no padrão PAdES (legislação compatível);
- 📡 API REST pronta para integração com sistemas de qualquer linguagem;
- ✅ Totalmente gratuito e open-source;
- 🔒 Assinatura visível ou invisível, conforme configuração.

---

```markdown
## 📂 Como usar

Este repositório disponibiliza apenas o microserviço em Java utilizado para assinar arquivos PDF. A geração dos documentos ocorre em um sistema externo, desenvolvido em C#, que utiliza este serviço como parte do processo.

### 1. Clone o projeto:

```bash
git clone https://github.com/LauroOlivera/assinatura-digital-java.git
cd assinatura-digital-java
