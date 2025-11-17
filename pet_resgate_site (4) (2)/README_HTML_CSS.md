# Pet Resgate - Protótipos em HTML e CSS

## 📌 Sobre o Projeto

Este projeto contém a transformação completa dos protótipos de um site para uma ONG de resgate de animais, desenvolvido **exclusivamente em HTML e CSS** (sem JavaScript complexo).

## 🎨 Cores Principais

- **Primária**: `#CBDAD5` (Verde claro/menta)
- **Secundária**: `#34344E` (Azul escuro/marinho)

## 📁 Estrutura de Arquivos

```
pet_resgate_ong/
├── html/                          # Todas as páginas HTML
│   ├── index.html                 # Página inicial
│   ├── galeria_fotos.html         # Galeria de fotos
│   ├── galeria_videos.html        # Galeria de vídeos
│   ├── projetos.html              # Projetos finalizados e ativos
│   ├── voluntario_login.html      # Login de voluntário
│   ├── voluntario_cadastro.html   # Cadastro de voluntário
│   ├── doacao_financeira.html     # Formulário de doação financeira
│   ├── doacao_item.html           # Formulário de doação de itens
│   ├── contato.html               # Página de contato
│   ├── agenda.html                # Página de agendamento
│   ├── equipes.html               # Equipes e voluntários
│   ├── como_ajudar.html           # Como ajudar
│   ├── transparencia.html         # Relatórios e transparência
│   ├── confirmacao_cadastro.html
│   ├── confirmacao_doacao_financeira.html
│   ├── confirmacao_doacao_item.html
│   ├── confirmacao_agenda.html
│   └── confirmacao_contato.html
└── css/
    └── style.css                  # Estilos globais
```

## 🚀 Como Usar

### Opção 1: Abrir Diretamente no Navegador
1. Navegue até a pasta `html/`
2. Abra `index.html` em seu navegador
3. Use os links de navegação para explorar todas as páginas

### Opção 2: Usar um Servidor Local (Recomendado)

#### Com Python 3:
```bash
cd html/
python -m http.server 8000
```
Acesse: `http://localhost:8000`

#### Com Node.js (http-server):
```bash
npm install -g http-server
cd html/
http-server
```

#### Com PHP:
```bash
cd html/
php -S localhost:8000
```

## 📄 Páginas Disponíveis

| Página | Descrição |
|--------|-----------|
| `index.html` | Página inicial com apresentação da ONG |
| `galeria_fotos.html` | Galeria de fotos com modais |
| `galeria_videos.html` | Galeria de vídeos em grid |
| `projetos.html` | Projetos finalizados e ativos |
| `voluntario_login.html` | Login para voluntários |
| `voluntario_cadastro.html` | Cadastro de novos voluntários |
| `doacao_financeira.html` | Formulário de doação em dinheiro |
| `doacao_item.html` | Formulário de doação de itens |
| `contato.html` | Formulário de contato |
| `agenda.html` | Agendamento com calendário |
| `equipes.html` | Informações sobre equipes |
| `como_ajudar.html` | Formas de contribuir |
| `transparencia.html` | Relatórios e estatísticas |

## 🎯 Características Implementadas

✅ **Design Responsivo** - Funciona em desktop, tablet e mobile
✅ **Navegação Consistente** - Menu presente em todas as páginas
✅ **Componentes Reutilizáveis** - Cards, botões, formulários padronizados
✅ **Cores Personalizadas** - Conforme especificado
✅ **Modais Interativos** - Para galeria de fotos
✅ **Formulários Funcionais** - Com redirecionamento para confirmação
✅ **Rodapé Padronizado** - Em todas as páginas
✅ **Sem Dependências Externas** - Apenas HTML e CSS puro

## 🔧 Personalização

### Alterar Cores
Abra `css/style.css` e modifique as variáveis CSS no início do arquivo:
```css
:root {
  --color-primary: #CBDAD5;
  --color-dark: #34344E;
  /* ... outras cores ... */
}
```

### Adicionar Conteúdo
Edite os arquivos HTML diretamente. Todos seguem a mesma estrutura:
```html
<header><!-- Navegação --></header>
<section class="banner"><!-- Banner --></section>
<section><!-- Conteúdo principal --></section>
<footer><!-- Rodapé --></footer>
```

### Integrar com Backend
Os formulários possuem atributos `onsubmit` que podem ser modificados para integrar com um servidor:
```html
<form onsubmit="handleSubmit(event)">
  <!-- Campos do formulário -->
</form>
```

## 📱 Breakpoints Responsivos

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: até 767px

## 🎨 Componentes CSS Disponíveis

- `.container` - Largura máxima com padding
- `.btn`, `.btn-primary`, `.btn-dark`, `.btn-outline` - Botões
- `.card` - Cards com sombra e hover
- `.grid`, `.grid-2`, `.grid-3`, `.grid-4` - Grids responsivos
- `.flex`, `.flex-center`, `.flex-between` - Flexbox utilities
- `.banner` - Seção de banner com overlay
- `.modal` - Modais para conteúdo
- `.alert` - Alertas (success, error, warning, info)

## 📝 Notas Importantes

1. **Sem JavaScript Complexo** - Apenas HTML e CSS, com JavaScript mínimo para interações básicas
2. **Imagens Placeholder** - Use gradientes e ícones emoji; substitua por imagens reais conforme necessário
3. **Links Internos** - Todos os links internos funcionam; links externos (WhatsApp, Email) precisam de configuração
4. **Formulários** - Redirecionam para páginas de confirmação; integre com backend conforme necessário

## 🔗 Links Úteis

- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## 📧 Suporte

Para dúvidas ou melhorias, entre em contato através do formulário de contato no site.

---

**Desenvolvido com ❤️ para Pet Resgate**
