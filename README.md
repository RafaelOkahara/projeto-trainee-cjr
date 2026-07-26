# projeto-trainee-cjr
    projeto de site de estoque fictício produzido para o processo seletivo da empresa júnior de computação da Universidade de Brasília
# Tecnologias Utilizadas

* **Front-end:** Next.js (App Router), React, TypeScript, Tailwind CSS
* **Comunicação:** Axios, Fetch API
* **Estilização e Ícones:** Tailwind CSS / Custom Components

# Funcionalidades Principais

* **Exploração Dinâmica:** Listagem de categorias, produtos e lojas consumidas diretamente de uma API REST.
* **Sistema de Busca:** Pesquisa em tempo real de produtos integrada com o back-end.
* **Página da Loja Personalizada:** 
  * Banner dinâmico, informações da loja e sistema de média de avaliações com estrelas personalizadas.
  * Verificação automática de permissão: **Apenas o dono da loja** logado consegue visualizar o botão de gerenciar e adicionar novos produtos.

# Estrutura do Projeto

* `app/page.tsx` — Página inicial com os carrosséis inteligentes de categorias, produtos e lojas.
* `app/lojas/[id]/page.tsx` — Página dinâmica da loja, contendo a lógica de validação de propriedade (`isOwner`) e carrosséis customizados.
* `components/` — Componentes reutilizáveis (Cards de produtos, avaliações, modais de criação/edição e barra de pesquisa).

# Como Rodar o Projeto Localmente

Certifique-se de ter o **Node.js** instalado na sua máquina. O projeto também requer que o back-end correspondente esteja rodando na porta `3001` (ou a configurada no arquivo `.env`).

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO/grupo04-cjr-front.git](https://github.com/SEU-USUARIO/grupo04-cjr-front.git)
2. **Entre na pasta do projeto:**
3. **Configure as variáveis de ambiente:**
Crie um arquivo .env na raiz e aponte a URL da API
4. **Execute o projeto em modo de desenvolvimento:**
