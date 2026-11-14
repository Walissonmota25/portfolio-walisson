# Portfólio - Walisson da Silva Mota

Portfólio acadêmico para apresentar meu perfil, meus conhecimentos em desenvolvimento de sistemas e projetos que realizei durante meus estudos.

## Acessos

- **Site publicado:** `https://walissonmota25.github.io/portfolio-walisson/`
- **Repositório:** `https://github.com/Walissonmota25/portfolio-walisson`

## Tecnologias utilizadas

- HTML5
- CSS3
- Bootstrap 5
- JavaScript do Bootstrap para o menu responsivo

## Seções do portfólio

- **Sobre:** apresentação pessoal e objetivo profissional.
- **Habilidades:** conhecimentos que estou desenvolvendo em Python, HTML, CSS, lógica de programação, Git, GitHub e Bootstrap.
- **Projetos:** links para projetos acadêmicos publicados no GitHub.
- **Contato:** links para meu GitHub e LinkedIn.

## Recurso novo

O projeto tem um tema visual escuro com detalhes vermelhos e cards de habilidades e projetos com efeito de hover. Ao passar o cursor sobre um card, ele se eleva levemente e recebe uma sombra.

Também foi adicionada ao topo do site uma ilustração animada personalizada do autor em estilo ninja programador, com bandana vermelha, manto preto de gola alta, faixa vermelha e motivos decorativos de nuvens. O fundo traz referências visuais a código, fluxo de sistemas e circuitos. A arte foi criada com edição assistida por IA a partir da foto fornecida pelo autor, preservando seus traços.

## Como o recurso foi implementado

O tema foi criado no arquivo `styles.css` usando variáveis CSS para as cores, gradientes e estilos personalizados. O efeito dos cards usa `transition`, `transform: translateY()` e `box-shadow`. Também foi incluída a preferência `prefers-reduced-motion`, que reduz o movimento para visitantes que solicitam menos animações.

A imagem final fica em `assets/walisson-ninja-dev-manto-ajustado.png` e é exibida no cabeçalho com uma tag `<img>`, texto alternativo e regras responsivas de proporção, enquadramento e borda definidas em `styles.css`. A região indicada recebeu um retoque pontual, preservando o restante da arte.

O layout usa o grid responsivo do Bootstrap. Os links do menu apontam para os `id` das seções da própria página, e o JavaScript do Bootstrap controla a abertura do menu em telas menores.

## Como executar localmente

1. Baixe ou clone o repositório.
2. Mantenha `index.html` e `styles.css` na mesma pasta.
3. Abra `index.html` no navegador. Como Bootstrap é carregado por CDN, é necessária uma conexão com a internet para carregar seus estilos e o menu responsivo.

## Publicação

O site pode ser publicado pelo GitHub Pages. Depois de ativar a publicação para a branch e pasta que contêm o `index.html`, substitua os campos acima pelos links reais do repositório e do site publicado.
