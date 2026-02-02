# OS Flow - Sistema de Gestão de Ordens de Serviço

Um dashboard inteligente e profissional para gestão completa de ordens de serviço, vendas, clientes e muito mais.

## 📋 Sobre o Projeto

**OS Flow** é um sistema web completo para gerenciamento de negócios, oferecendo módulos para:

- 📊 **Dashboard** - Visão geral do negócio com métricas em tempo real
- 👥 **Cadastro de Clientes** - Gestão completa de clientes
- 📦 **Produtos** - Catálogo e controle de produtos
- 🔧 **Serviços** - Gerenciamento de serviços oferecidos
- 💰 **Vendas** - Controle de vendas e propostas
- 📝 **Ordens de Serviço** - Criação e acompanhamento de OS
- ✅ **Garantias** - Gestão de garantias
- 📁 **Arquivos** - Armazenamento de documentos
- 💳 **Cobrança** - Controle financeiro e cobranças
- ⚙️ **Configurações** - Configurações do sistema

## 🗂️ Estrutura do Projeto

```
os-flow/
├── index.html              # Página principal (Dashboard)
├── pages/                  # Páginas do sistema
│   ├── arquivos.html       # Gestão de arquivos
│   ├── cadastrar-clientes.html
│   ├── cobranca.html       # Módulo financeiro
│   ├── configuracoes.html  # Configurações
│   ├── garantias.html      # Garantias
│   ├── ordem-servico.html  # Ordens de serviço
│   ├── produtos.html       # Catálogo de produtos
│   ├── servicos.html       # Serviços
│   └── vendas.html         # Vendas
├── assets/
│   ├── css/
│   │   └── main.css        # Estilos compartilhados
│   └── js/
│       └── main.js         # Scripts compartilhados
└── README.md               # Este arquivo
```

## 🚀 Como Usar

### Opção 1: Abrir Localmente

1. Clone ou baixe este repositório
2. Abra o arquivo `index.html` no seu navegador
3. Navegue entre as páginas usando o menu lateral

### Opção 2: Servidor Local

Para melhor experiência, use um servidor HTTP local:

```bash
# Com Python 3
python3 -m http.server 8000

# Com Node.js (npx)
npx http-server

# Com PHP
php -S localhost:8000
```

Depois acesse: `http://localhost:8000`

### Opção 3: GitHub Pages

Este projeto está pronto para ser hospedado no GitHub Pages:

1. No seu repositório, vá em **Settings → Pages**
2. Em **Source**, selecione a branch principal (main/master)
3. Salve e aguarde alguns minutos
4. Seu site estará disponível em: `https://seu-usuario.github.io/nome-do-repositorio/`

## 🎨 Características

- ✨ Design moderno e profissional
- 📱 Interface responsiva
- 🎯 Menu lateral recolhível
- 🎨 Paleta de cores consistente (azul claro como cor principal)
- 🔄 Navegação fluida entre módulos
- 📊 Gráficos e estatísticas visuais
- 🌐 Sistema de notificações

## 🛠️ Tecnologias

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos modernos com CSS Variables
- **JavaScript Vanilla** - Interatividade sem dependências
- **Google Fonts** - Tipografia profissional (Plus Jakarta Sans, Manrope)

## 📝 Organização do Código

O projeto foi reorganizado para melhor manutenibilidade:

- ✅ **CSS Centralizado**: Todo o CSS foi extraído para `assets/css/main.css`
- ✅ **JavaScript Unificado**: Scripts compartilhados em `assets/js/main.js`
- ✅ **Estrutura Clara**: Separação entre página principal e módulos internos
- ✅ **Sem Duplicação**: Código reutilizado em vez de duplicado

## 🔧 Manutenção

### Adicionar Nova Página

1. Crie o arquivo HTML em `pages/`
2. Use a estrutura de uma página existente como base
3. Certifique-se de referenciar os arquivos CSS/JS corretamente:
   ```html
   <link rel="stylesheet" href="../assets/css/main.css">
   <script src="../assets/js/main.js"></script>
   ```
4. Atualize os links de navegação no menu lateral

### Modificar Estilos

- Edite `assets/css/main.css`
- Use as variáveis CSS já definidas (`:root`)
- As mudanças serão aplicadas em todas as páginas

### Modificar Comportamento

- Edite `assets/js/main.js`
- Mantenha compatibilidade com todas as páginas

## 📄 Licença

Este projeto é de código aberto. Sinta-se livre para usar e modificar conforme necessário.

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📧 Contato

Para dúvidas ou sugestões, abra uma issue no repositório.

---

**OS Flow** - Gestão Inteligente de Serviços 🚀
