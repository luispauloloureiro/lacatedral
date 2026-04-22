# La Catedral Barbearia - Landing Page

Website completo para a barbearia La Catedral, desenvolvido com HTML, CSS e JavaScript.

## Estrutura do Projeto

```
La Catedral/
├── index.html          # Página principal
├── styles.css          # Folha de estilo
├── script.js           # JavaScript para interatividade
├── package.json        # Configurações do projeto
├── abrir-site.bat      # Arquivo para abrir o site localmente
└── README.md           # Este arquivo
```

## Como Visualizar o Site

### Opção 1: Duplo clique no arquivo HTML
- Simplesmente clique duas vezes no arquivo `index.html`
- O site será aberto automaticamente no seu navegador padrão

### Opção 2: Usando o arquivo batch
- Execute `abrir-site.bat`
- O site será aberto automaticamente

### Opção 3: Servidor local (requer Node.js)
```bash
npm install live-server -g
live-server --port=3000
```

### Opção 4: Servidor Python (requer Python)
```bash
python -m http.server 3000
```

## Recursos Implementados

### ✅ Design Responsivo
- Layout mobile-first
- Compatível com todos os dispositivos
- Texto grande e legível em mobile (preferência do usuário)
- Hover effects sutis e balanceados (preferência do usuário)

### ✅ Seções do Site
1. **Hero Section** - Primeira dobra com headline e CTAs
2. **Quem Somos** - História e valores da barbearia
3. **No que a gente acredita** - Princípios e filosofia
4. **Serviços** - Lista completa de serviços oferecidos
5. **Diferencial na prática** - Pontos únicos da barbearia
6. **Nossa equipe** - Informações sobre os profissionais
7. **Localização** - Endereço e mapa integrado
8. **Agendamento** - Call-to-action para agendamentos
9. **Fechamento** - Footer com informações de contato

### ✅ Funcionalidades
- Menu mobile responsivo com animação
- Scroll suave entre seções
- Botões de agendamento via WhatsApp
- Animações ao rolar a página
- Botão voltar ao topo
- Links para redes sociais
- Mapa integrado do Google Maps

### ✅ Otimizações
- Código comentado em português
- Performance otimizada
- SEO básico implementado
- Acessibilidade considerada

## Personalização

### Alterar informações de contato:
- WhatsApp: Edite os links `href="https://wa.me/5553999999999"` no HTML
- Redes sociais: Atualize os links no footer
- Endereço: Modifique a seção de localização

### Alterar cores:
Edite as variáveis CSS no início do arquivo `styles.css`:
```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #e74c3c;
    --accent-color: #f39c12;
    /* ... outras variáveis */
}
```

## Requisitos Técnicos

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet para:
  - Fontes do Google Fonts
  - Ícones do Font Awesome
  - Google Maps

## Notas Importantes

- Todos os textos estão em português brasileiro
- O código está totalmente comentado em português
- Design segue as preferências do usuário:
  - Texto grande e visível em mobile
  - Hover effects sutis e balanceados
  - Contraste adequado

## Suporte

Para dúvidas ou problemas, entre em contato com o desenvolvedor.
