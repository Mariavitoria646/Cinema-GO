# Infográfico Cinema Goiano

## Descrição do projeto
O **Infográfico Cinema Goiano** é uma página web interativa que destaca filmes produzidos no estado de Goiás. Na página principal, os filmes são apresentados em uma grade de cartazes acompanhados de informações básicas. Cada cartaz possui uma sinopse oculta que é exibida quando o usuário clica no cartaz correspondente. O layout usa uma paleta de tons de azul claro para fundo e fontes legíveis para facilitar a leitura. O design é responsivo, adaptando-se automaticamente a diferentes tamanhos de tela e dispositivos. A interação do usuário é proporcionada por um script em JavaScript que alterna a visibilidade das sinopses dos filmes (por meio da função `toggleSinopse()`), tornando a experiência dinâmica e informativa.

## Tecnologias utilizadas
- **HTML**: estruturação do conteúdo da página e dos elementos de marcação, como imagens e botões.  
- **CSS**: definição do estilo visual, incluindo a paleta azul clara, tipografia legível e layout em grade responsivo. O arquivo `style.css` implementa todos os estilos necessários para organizar os cartazes dos filmes de forma atrativa.  
- **JavaScript**: implementação de funcionalidades interativas. O arquivo `script.js` contém a função `toggleSinopse()`, que alterna (mostra/oculta) a sinopse de cada filme quando o usuário clica no cartaz correspondente. Essa lógica em JS permite que as informações apareçam de forma dinâmica sem recarregar a página.  

## Como visualizar o projeto localmente
Para executar e visualizar o infográfico em seu computador, siga estes passos:
1. **Clone ou baixe o repositório** do projeto (por exemplo, usando `git clone` ou fazendo download do ZIP pelo GitHub).  
2. **Abra o arquivo HTML**: No diretório do projeto, dê um duplo-clique no arquivo `infografico-cinema-goiano.html` ou abra-o com o navegador de sua preferência (Chrome, Firefox, Edge etc.).  
3. **Interaja com a página**: A página abrirá com a grade de cartazes. Clique em qualquer cartaz para exibir ou ocultar a sinopse do filme correspondente. Não é necessário instalar dependências extras nem servidores; é um projeto web estático que roda localmente no navegador.

## Organização dos arquivos
O projeto possui a seguinte estrutura de arquivos:

- `infografico-cinema-goiano.html` – Página principal em HTML. Contém a estrutura da grade de cartazes de filmes e os elementos para cada filme (imagem do cartaz, título etc.). Cada cartaz está vinculado a um trecho de texto que contém a sinopse oculta.  
- `style.css` – Arquivo de estilos em CSS. Define o design visual do infográfico, incluindo cores de fundo (tons de azul claro), fontes legíveis e layout responsivo em grade. Todas as regras de estilo para a apresentação dos cartazes e a aparência geral da página estão neste arquivo.  
- `script.js` – Arquivo JavaScript (antes renomeado de `6cbf3320-676a-4479-a330-a617e24302b5.js`). Contém a função `toggleSinopse()`, responsável por mostrar ou ocultar as sinopses dos filmes. Cada cartaz está configurado para chamar essa função ao ser clicado, permitindo que o texto da sinopse apareça ou desapareça conforme a interação do usuário.  

## Créditos e informações adicionais
- Este infográfico foi desenvolvido com fins **educacionais/de divulgação cultural** para apresentar de forma interativa o cinema do estado de Goiás.  
- As **imagens dos cartazes** são ilustrativas e, na versão final do projeto, podem ser substituídas por cartazes oficiais ou licenciados. Caso sejam usadas imagens de divulgação, recomenda-se verificar direitos autorais ou usar imagens de domínio público.  
- As **informações sobre os filmes** (títulos, sinopses, diretores etc.) devem ser baseadas em fontes oficiais ou públicas, como sites de festivais de cinema, bancos de dados de filmes (IMDB, Cinemateca Brasileira) ou material promocional.  
- **Estilo e funcionalidade**: O design em tons de azul claro foi escolhido para combinar com a identidade visual proposta do projeto. A função de alternância de sinopses (`toggleSinopse`) foi criada em JavaScript puro, mas bibliotecas adicionais (como jQuery) podem ser usadas em versões futuras para enriquecer as interações.  
- **Contribuições**: Sinta-se à vontade para contribuir com melhorias, correções ou inclusão de novos filmes goianos. Feedbacks e sugestões são bem-vindos para aprimorar este infográfico. Se utilizar este projeto como base, por favor mantenha os créditos adequados.
