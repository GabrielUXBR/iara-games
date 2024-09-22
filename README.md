# Iara Games

**Iara Games** é uma plataforma interativa para entusiastas de jogos de tabuleiro. Os usuários podem explorar uma variedade de jogos disponíveis para compra, agendar partidas com amigos, gerenciar suas coleções de jogos e muito mais. A plataforma oferece uma experiência fácil e intuitiva, permitindo que jogadores se conectem e organizem suas partidas.

## 🚀 Funcionalidades

- **Exploração de Jogos**: Navegue por uma lista de jogos de tabuleiro, veja detalhes como descrição, número de jogadores, autor, ilustrador, e adicione-os ao seu carrinho.
- **Perfil do Usuário**: Os usuários têm um perfil personalizado com sua coleção de jogos, histórico de partidas jogadas e a possibilidade de editar suas informações pessoais.
- **Agendamento de Partidas**: Crie e gerencie partidas com seus amigos, informando o jogo, data, local e número de participantes.
- **Gerenciamento de Amizades**: Adicione e remova amigos da sua lista, e convide-os para participar de partidas.
- **Autenticação**: Sistema de login e cadastro seguro para garantir a privacidade e personalização da experiência do usuário.

## 🛠️ Tecnologias Utilizadas

- **React**: Framework para o desenvolvimento da interface de usuário.
- **React Router**: Navegação entre as páginas da aplicação.
- **Axios**: Para requisições HTTP e integração com a API de jogos.
- **Context API**: Para gerenciamento de estado global (ex.: autenticação, dados de jogos).
- **Node.js** (Back-end): Para o gerenciamento das APIs e integração com banco de dados.
- **Vercel**: Para o deploy da aplicação.

## 📂 Estrutura de Pastas

```bash
/iara-games
├── /public              # Arquivos públicos (index.html, favicon, etc.)
├── /src                 # Código-fonte do projeto
│   ├── /assets          # Imagens e estilos globais
│   ├── /components      # Componentes reutilizáveis
│   ├── /pages           # Páginas da aplicação (Home, Login, etc.)
│   ├── /services        # Integração com API (requisições HTTP)
│   ├── /context         # Contextos globais (AuthContext, GameContext)
│   ├── /hooks           # Custom Hooks (ex.: useAuth)
│   ├── /utils           # Funções utilitárias
│   └── index.js         # Arquivo principal do React
└── README.md            # Documentação do projeto

🔧 Instalação e Execução
Siga os passos abaixo para rodar o projeto localmente:

Pré-requisitos
Node.js e npm instalados na sua máquina.


Clone o repositório:
git clone https://github.com/seu-usuario/iara-games.git

Navegue até o diretório do projeto:
cd iara-games

Instale as dependências:
npm install

Inicie o servidor de desenvolvimento:
npm start

