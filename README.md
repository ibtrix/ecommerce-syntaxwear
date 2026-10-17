# SyntaxWear

Uma landing page de e-commerce para uma marca de sneakers e calçados urbanos, com visual moderno, responsivo e focado em conversão.

## Visão geral

O projeto `SyntaxWear` é um site estático de e-commerce voltado para a venda de tênis e sneakers com foco em estilo urbano, acessórios para esporte e uma experiência de compra visualmente premium. A interface conta com navbar fixa, hero banner, categorias de produtos, grid de destaques e rodapé com newsletter e redes sociais.

A estrutura do site foi construída em HTML5 e CSS3, com foco em design responsivo para desktop, tablet e mobile, sem dependências de frameworks ou bibliotecas externas.

## Objetivo

- Apresentar a marca de forma elegante e moderna;
- Destacar modelos em destaque e categorias de produtos;
- Criar uma experiência visual atrativa para usuários em dispositivos móveis e desktops;
- Servir como base para uma loja online ou protótipo de storefront.

## Funcionalidades

- Header fixo com navegação principal;
- Hero section com call-to-action principal;
- Seção de categorias com imagens temáticas;
- Grid de produtos em destaque;
- Footer com formulário de newsletter e redes sociais;
- Layout totalmente responsivo;
- Visual com identidade forte em tons escuros, roxos e cinza.

## Tecnologias utilizadas

- HTML5
- CSS3
- Google Fonts (`Ubuntu`)
- Imagens locais em SVG e JPG

## Estrutura do projeto

```text
.
├── css/
│   ├── base.css
│   ├── reset.css
│   ├── variables.css
│   └── components/
│       ├── footer.css
│       ├── header.css
│       ├── hero.css
│       ├── product-category.css
│       └── product-grid.css
├── images/
│   ├── banners/
│   ├── icons/
│   ├── logo/
│   ├── favicons/
│   └── products/
├── js/
│   └── (pasta reservada para scripts futuros)
├── index.html
├── README.md
```

## Como executar localmente

### Opção 1: abrir diretamente no navegador

1. Faça o download ou clone o projeto;
2. Navegue até a pasta do repositório;
3. Abra o arquivo `index.html` em qualquer navegador.

### Opção 2: servidor local

Se quiser visualizar o site em um ambiente mais próximo de produção, execute:

```bash
python -m http.server 8000
```

Em seguida, acesse:

```text
http://localhost:8000
```

## Seções do site

### Header

A navegação principal inclui:

- categorias (`Masculino`, `Feminino`, `Outlet`);
- links rápidos (`Nossas lojas`, `Sobre`);
- ícones de conta, ajuda e carrinho.

### Hero section

A seção principal mostra a campanha da marca com título forte e botões de ação para visualizar modelos ou comprar.

### Categorias

Quatro blocos temáticos representam os principais estilos da coleção:

- Casual
- Esporte
- Moderno
- Futurista

### Grid de produtos

A área de destaques organiza itens em uma grade responsiva, destacando coleções e modelos especiais com fotografias e blocos de ação.

### Footer

O rodapé inclui:

- formulário de newsletter;
- ícones das redes sociais;
- links organizados por categoria;
- informações institucionais e redes da marca.

## Personalização

### Alterar cores e tipografia

Os valores globais ficam em `css/variables.css` e o estilo base em `css/base.css`.

### Ajustar layout e seções

Os componentes principais estão organizados em arquivos separados:

- `css/components/header.css`
- `css/components/hero.css`
- `css/components/product-category.css`
- `css/components/product-grid.css`
- `css/components/footer.css`

### Trocar imagens

As imagens ficam dentro da pasta `images/` e podem ser substituídas sem mudar a estrutura HTML, desde que mantenham proporções compatíveis com o layout.

## Observações

Este projeto é um mockup estático de e-commerce e não possui integração com backend, carrinho funcional ou checkout real. Ele funciona como apresentação visual e protótipo de interface de loja.

## Status do projeto

- Status: em desenvolvimento / protótipo estático
- Tipo: landing page e-commerce
- Responsividade: sim

## Contribuição

Contribuições são bem-vindas. Para sugerir melhorias, ajuste de UI ou novas seções, basta abrir uma issue ou enviar um pull request.

## Licença

Este projeto não possui licença formal definida no repositório. Se a intenção for publicar em produção ou compartilhar publicamente, recomenda-se adicionar uma licença adequada (como MIT ou GPL) antes da distribuição.

## Autor

Projeto desenvolvido para a marca `SyntaxWear`, com foco em apresentação visual e experiência de compra moderna.
