# SAA × Cosmos - Site Corporativo

Um site moderno e responsivo para a parceria entre SAA e Cosmos, desenvolvido com HTML, CSS e JavaScript.

## 🚀 Características

- **Design Moderno**: Interface limpa e profissional
- **Totalmente Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Animações Suaves**: Transições e efeitos visuais elegantes
- **Formulário de Contato**: Funcional e com validação
- **Navegação Suave**: Scroll automático para as seções
- **Otimizado para SEO**: Estrutura semântica e meta tags

## 📁 Estrutura do Projeto

```
website-saa-cosmos/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript interativo
├── README.md           # Este arquivo
└── logo_placeholders.txt # Instruções para logos
```

**Logos hospedadas na nuvem:**
- SAA: https://www.saasoftware.com.br/images/logo1-03.png
- Cosmos: https://cosmos.saasoftware.com.br/logo.png

## 🎨 Personalização

### 1. Logos Hospedadas

As logos já estão configuradas e hospedadas na nuvem:

- **SAA**: https://www.saasoftware.com.br/images/logo1-03.png
- **Cosmos**: https://cosmos.saasoftware.com.br/logo.png

As logos são carregadas automaticamente e não precisam ser adicionadas localmente.

### 2. Personalizar Cores

Para alterar as cores do site, edite as variáveis CSS no arquivo `styles.css`:

```css
:root {
    --primary-color: #6366f1;      /* Cor principal */
    --secondary-color: #8b5cf6;    /* Cor secundária */
    --accent-color: #06b6d4;       /* Cor de destaque */
    /* ... outras cores */
}
```

### 3. Personalizar Conteúdo

Edite o arquivo `index.html` para personalizar:

- **Títulos e textos**
- **Informações de contato**
- **Serviços**
- **Estatísticas**

### 4. Configurar Formulário de Contato

O formulário atual simula o envio. Para torná-lo funcional:

1. **EmailJS** (Recomendado):
   ```javascript
   // Adicione no <head> do HTML
   <script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
   ```

2. **PHP** (Alternativa):
   - Crie um arquivo `process-form.php`
   - Configure o servidor para processar o formulário

## 🛠️ Como Usar

### Visualizar Localmente

1. Abra o arquivo `index.html` em qualquer navegador
2. Ou use um servidor local:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (com http-server)
   npx http-server
   ```
   
## 📱 Responsividade

O site é totalmente responsivo e funciona em:

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🎯 Seções do Site

1. **Header**: Logos e navegação
2. **Início**: Hero section com chamada principal
3. **Sobre**: Informações sobre SAA e Cosmos
4. **Serviços**: 6 serviços principais oferecidos
5. **Contato**: Formulário e informações de contato
6. **Footer**: Links e informações adicionais

## 🔧 Funcionalidades JavaScript

- **Scroll Suave**: Navegação entre seções
- **Animações**: Elementos aparecem conforme scroll
- **Contadores**: Números animados na seção "Sobre"
- **Formulário**: Validação e feedback visual
- **Menu Mobile**: Navegação responsiva
- **Parallax**: Efeito visual no hero

## 🎨 Paleta de Cores Baseada nas Logos

- **SAA Verde**: #2d5016 (Verde escuro da SAA)
- **SAA Verde Claro**: #4a7c59 (Verde mais claro da SAA)
- **Cosmos Azul**: #00d4ff (Azul elétrico do Cosmos)
- **Cosmos Roxo**: #6366f1 (Roxo do Cosmos)
- **Cosmos Roxo Escuro**: #4f46e5 (Roxo escuro do Cosmos)
- **Texto**: #1f2937 (Cinza escuro)
- **Fundo**: #f8faf8 (Verde muito claro)
---

**Desenvolvido by noahzera and agentes**
