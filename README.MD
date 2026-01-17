# 🛠️ NM Assistência — Sistema de Gestão de Serviços

Sistema web desenvolvido para a **NM Assistência**, com o objetivo de **gerenciar serviços técnicos**, clientes e pagamentos de forma simples, moderna e eficiente.

O projeto foi pensado para uso real no dia a dia da assistência, com foco em **UI/UX profissional**, **performance** e **escala futura**.

---

## 🚀 Funcionalidades

* ✅ Cadastro de clientes
* ✅ Registro de serviços realizados
* ✅ Armazenamento de telefone, endereço e observações
* ✅ Registro de data, hora e valor do serviço
* ✅ Histórico completo de serviços
* ✅ Exclusão de registros
* ✅ Interface responsiva (desktop e mobile)
* ✅ Animações suaves com **GSAP**
* ✅ Integração com **Supabase (PostgreSQL)**

---

## 🎨 UI / UX

O layout segue uma identidade visual profissional utilizando:

* 🔵 Azul escuro
* ⚫ Preto
* ⚪ Branco

Além disso, são aplicadas animações com **GSAP** para melhorar a experiência do usuário sem comprometer a performance.

---

## 🧰 Tecnologias Utilizadas

* **HTML5**
* **CSS3** (layout responsivo e moderno)
* **JavaScript (Vanilla)**
* **GSAP** (animações)
* **Supabase**

  * PostgreSQL
  * API REST automática
  * Auth (futuro)

---

## 🗄️ Estrutura do Banco de Dados (Supabase)

### 📁 Tabela `clientes`

| Campo      | Tipo      |
| ---------- | --------- |
| id         | uuid (PK) |
| nome       | text      |
| telefone   | text      |
| endereco   | text      |
| created_at | timestamp |

### 📁 Tabela `servicos`

| Campo        | Tipo      |
| ------------ | --------- |
| id           | uuid (PK) |
| cliente_id   | uuid (FK) |
| descricao    | text      |
| observacao   | text      |
| data_servico | timestamp |
| valor        | numeric   |
| created_at   | timestamp |

---

## ⚙️ Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/nm-assistencia.git
```

2. Abra o arquivo `index.html` no navegador

> 💡 O sistema funciona 100% no navegador e se conecta diretamente ao Supabase.

---

## 🔐 Segurança

* Utiliza **Row Level Security (RLS)** no Supabase
* Preparado para autenticação por usuário (admin)
* Chave pública utilizada apenas para operações permitidas

---

## 📈 Evoluções Futuras

* 🔐 Sistema de login
* 🔍 Busca e filtros por cliente e data
* 📊 Relatórios financeiros
* 📄 Exportação em PDF / Excel
* 📱 Versão mobile (React Native)
* ☁️ Backup e multiusuário

---

## 👨‍💻 Autor

**Nathan Mariotto**
Desenvolvedor Full Stack
📍 Paraná — Brasil

Projeto desenvolvido para uso real na **NM Assistência**.

---

## 📄 Licença

Este projeto é de uso privado da **NM Assistência**.
Todos os direitos reservados.
