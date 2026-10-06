# 📚 Sistema de Gerenciamento de Biblioteca

Um sistema completo para gerenciamento e consulta de acervo bibliográfico, desenvolvido para facilitar a organização, cadastro e controle de livros e empréstimos.

---

## 🌐 Demonstração & Deploys

O projeto está hospedado e disponível para acesso através das seguintes plataformas:

* 🚀 **Vercel:** [sistema-de-biblioteca-sigma.vercel.app](https://sistema-de-biblioteca-sigma.vercel.app/)
* 📄 **GitHub Pages:** [natanpaques.github.io/Bliblio_SuplaBase/](https://natanpaques.github.io/Bliblio_SuplaBase/)

---

## 🗄️ Banco de Dados

A infraestrutura e o banco de dados do projeto foram integrados e hospedados utilizando o **[Supabase](https://supabase.com/)**, garantindo:

* **PostgreSQL:** Banco de dados relacional de alta performance e confiabilidade.
* **Segurança e Regras de Acesso:** Políticas de segurança em nível de linha (RLS - Row Level Security).
* **Conexão em Tempo Real:** Sincronização e consultas eficientes na aplicação.

---

## 🛠️ Tecnologias Utilizadas

* **Frontend:** HTML5, CSS3, JavaScript
* **Backend / Database:** [Supabase](https://supabase.com/) (PostgreSQL & API REST)
* **Hospedagem Frontend:** GitHub Pages & Vercel

---

## ✨ Funcionalidades

- [x] Cadastro e gerenciamento de livros no acervo
- [x] Consulta e busca de publicações
- [x] Integração direta com banco de dados Supabase
- [x] Interface responsiva e acessível

---

## 🚀 Como Executar o Projeto Localmente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/natanpaques/Bliblio_SuplaBase.git
   ```

2. **Acesse o diretório do projeto:**
   ```bash
   cd Bliblio_SuplaBase
   ```

3. **Configure as Variáveis de Ambiente:**
   Crie ou edite o arquivo de configuração para incluir suas credenciais do Supabase:
   ```env
   SUPABASE_URL=sua_url_do_supabase
   SUPABASE_KEY=sua_chave_anonima_do_supabase
   ```

4. **Execute o projeto:**
   Abra o arquivo `index.html` em seu navegador ou utilize uma extensão como o *Live Server* no VS Code.

---

## 👤 Autor

Desenvolvido por **Natan Paques**.

* GitHub: [@natanpaques](https://github.com/natanpaques)
