# 🌻 Para Sâmy, Minha Neném

Um site romântico e interativo criado com HTML, CSS e JavaScript puro. Perfeito para usar com Live Server e hospedar no GitHub Pages.

## 📁 Estrutura do Projeto

```
samilly-love-site-static/
├── index.html              # Página principal (HTML + CSS)
├── script.js               # Funcionalidades JavaScript
├── README.md               # Este arquivo
└── assets/
    ├── photos/             # Fotos da galeria (10 fotos)
    ├── video/              # Vídeo do pedido
    └── sunflowers/         # Imagens decorativas de girassóis
```

## 🚀 Como Executar Localmente com Live Server

### Passo 1: Instalar a Extensão Live Server no VSCode
1. Abra o VSCode
2. Vá para Extensions (Ctrl+Shift+X)
3. Procure por "Live Server"
4. Instale a extensão de Ritwick Dey

### Passo 2: Abrir o Projeto
1. Abra a pasta `samilly-love-site-static` no VSCode
2. Clique com botão direito no arquivo `index.html`
3. Selecione "Open with Live Server"

O site abrirá automaticamente em `http://localhost:5500`

## 📤 Como Hospedar no GitHub Pages

### Passo 1: Criar um Repositório no GitHub
1. Vá para [github.com](https://github.com)
2. Clique em "New repository"
3. Nomeie como `samilly-love-site` (ou outro nome)
4. Deixe como "Public"
5. Clique em "Create repository"

### Passo 2: Fazer Upload dos Arquivos
1. Abra o terminal na pasta do projeto
2. Execute os seguintes comandos:

```bash
git init
git add .
git commit -m "Inicial commit"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/samilly-love-site.git
git push -u origin main
```

### Passo 3: Ativar GitHub Pages
1. No repositório, vá para **Settings**
2. Procure por **Pages** no menu lateral esquerdo
3. Em "Source", selecione **main** branch
4. Clique em **Save**

Seu site estará disponível em: `https://SEU_USUARIO.github.io/samilly-love-site`

## ✨ Funcionalidades

- ✅ **Contadores em Tempo Real** - Dias desde 14/06/2025 e 16/08/2025
- ✅ **Galeria Interativa** - Fotos em preto e branco que ganham cor no hover
- ✅ **Vídeo Responsivo** - Player de vídeo com controles
- ✅ **Modal de Carta** - Clique em "LER MINHA CARTA" para abrir
- ✅ **Animações Suaves** - Fade-in ao scroll, pétalas caindo
- ✅ **Design Responsivo** - Funciona em mobile, tablet e desktop
- ✅ **Tipografia Elegante** - Fontes Google (Dancing Script, Playfair Display, Merriweather)

## 🎨 Paleta de Cores

- Amarelo Girassol: `#FDD835`
- Laranja: `#FF9800`
- Marrom Chocolate: `#5D4037`
- Verde Oliva: `#7CB342`
- Creme: `#FFF9E6`

## 📝 Personalizações

### Mudar Datas dos Contadores
Abra `script.js` e procure pela função `calculateDays()`:

```javascript
const counter1 = calculateDays('2025-06-14'); // Mude para sua data
const counter2 = calculateDays('2025-08-16'); // Mude para sua data
```

### Adicionar Mais Fotos
1. Coloque as fotos na pasta `assets/photos/`
2. Abra `script.js` e adicione os nomes na array `photos`:

```javascript
const photos = [
    'MeuAmor1.jpeg',
    'MeuAmor2.jpeg',
    'SuaNovaFoto.jpeg', // Adicione aqui
    // ...
];
```

### Mudar Textos
Abra `index.html` e procure pelos textos que deseja mudar. Todos estão no HTML.

## 🔧 Requisitos

- VSCode (ou outro editor de código)
- Extensão Live Server (para desenvolvimento local)
- Navegador moderno (Chrome, Firefox, Safari, Edge)

## 📱 Compatibilidade

- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ Tablet (iPad, Android)
- ✅ Mobile (iPhone, Android)

## 💡 Dicas

1. **Para adicionar mais animações**: Edite o arquivo `style` dentro de `index.html`
2. **Para mudar cores**: Procure por `--sunflower-*` no CSS
3. **Para adicionar sons**: Use a tag `<audio>` no HTML

## 📞 Suporte

Se tiver dúvidas sobre como usar o Live Server ou GitHub Pages, consulte:
- [Live Server Docs](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [GitHub Pages Docs](https://docs.github.com/en/pages)

---

Feito com ❤️ para Sâmy 🌻
