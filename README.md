Projeto Super Mário Responsivo

Este projeto consiste em uma landing page inspirada no universo do Super Mário, com foco em técnicas de responsividade usando CSS Flexbox e Media Queries. A página inclui um vídeo de fundo, seção "Sobre Nós", formulário de contato e um botão flutuante do WhatsApp.

📂 Estrutura de Pastas

/              # raiz do projeto
├── index.html # arquivo HTML principal
├── style.css  # estilos CSS
└── assets/    # (opcional) imagens, vídeo e outros recursos

🛠 Tecnologias

HTML5

CSS3 (Flexbox, Media Queries)

🚀 Como Executar

Clone este repositório:

git clone https://github.com/seu-usuario/projeto-mario-responsive.git

Acesse a pasta do projeto:

cd projeto-mario-responsive

Abra o arquivo index.html no seu navegador preferido.

📱 Responsividade

Mobile‑First: estilos base para dispositivos móveis, depois media queries para telas maiores.

Breakpoints:

max-width: 1000px — ajusta layout para tablets e celulares grandes.

Personalize no arquivo style.css conforme necessidade.

Flexbox: containers flexíveis que se adaptam à largura da tela.

Unidades relativas: uso de %, vw, rem para fluidificar o design.

⚙️ Personalização

Para alterar o breakpoint, edite o valor em:

@media (max-width: 1000px) { ... }

Ajuste cores, fontes e espaçamentos no style.css.

Substitua o vídeo de fundo trocando o src da tag <video> em index.html.

🧩 Componentes Principais

Seletor

Descrição

header

Cabeçalho com logo e link de navegação

.container

Container principal com layout em Flexbox

.sobre-nos

Seção de descrição/texto

.mario

Imagem responsiva do Mario

.fale-conosco

Formulário de contato

.whatsapp

Botão flutuante para contato via WhatsApp

💡 Dicas

Teste em diferentes tamanhos de tela via DevTools.

Use display: none;, visibility: hidden; ou opacity: 0; para controlar visibilidade de elementos.

Mantenha o meta viewport em seu <head>:

<meta name="viewport" content="width=device-width, initial-scale=1.0">

🤝 Contribuição

Contribuições são bem-vindas! Abra uma issue ou pull request para sugerir melhorias.

Desenvolvido por Samuel Ferreira Inocêncio
