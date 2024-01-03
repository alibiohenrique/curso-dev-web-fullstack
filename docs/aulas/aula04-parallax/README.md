# Cafeteria IOS - Guia de Desenvolvimento

Neste README, você encontrará informações sobre o desenvolvimento da página "Cafeteria IOS," destacando os principais elementos do código HTML e CSS, bem como conceitos importantes relacionados a efeito parallax.

## Principais Atributos do Código HTML:

- **Metadados e Título:** O código HTML define a linguagem (lang) como "pt-br" e inclui metadados como a ligação para o arquivo de estilo "style.css" e o título da página "Cafeteria IOS."

- **Estrutura do Documento:** O HTML está estruturado com cabeçalho (`<head>`) e corpo (`<body>`) do documento, seguindo práticas comuns.

## Durante o desenvolvimento deste código, alguns conhecimentos e técnicas específicas foram aplicados:

- **Estilo CSS Global:** O CSS define estilos globais para o corpo da página, incluindo margens, padding, cor de texto e fonte.

- **Media Queries:** O código inclui media queries para ajustar o layout em dispositivos com largura máxima de 820 pixels. Isso garante uma experiência responsiva em dispositivos móveis.

- **Animações CSS:** Utiliza animações CSS para o surgimento suave de elementos na página. A animação é aplicada à classe `.container` usando a regra `@keyframes surgir`.

- **Seções Parallax:** Cria seções parallax usando imagens de fundo e texto sobreposto. Cada seção parallax é estilizada com cores de texto e sombras para legibilidade.

## Estrutura de Seções na Página:

1. **Seção 1: Parallax**
   - Apresenta um título principal com efeito parallax.

2. **Seção 2: Conteúdo**
   - Destaca a imersão de sabor oferecida pela cafeteria, com texto descritivo sobre a qualidade dos cafés.

3. **Seção 3: Parallax"**
   - Apresenta um título principal relacionado aos cafés e seus acompanhamentos.

4. **Seção 4: Conteúdo**
   - Informa sobre a variedade de alimentos disponíveis na cafeteria, incluindo bolos, croissants e biscoitos gourmet.

5. **Seção 5: Parallax**
   - Apresenta um título principal relacionado ao ambiente acolhedor da cafeteria.

6. **Seção 6: Conteúdo**
   - Descreve o ambiente diferenciado da cafeteria, destacando a decoração, iluminação e serviço atencioso.

## Conceitos Importantes:

### Efeito Parallax

Este efeito cria a ilusão de profundidade ao mover os elementos da página em diferentes velocidades durante o scroll. O conceito tem raízes na Física.

### Wrapper

Quando trabalhamos com parallax, diferenciamos por sessões utilizando a classe `<section class="modulo parallax parallax-1">`. No exemplo, o nome da classe pode ser acessado diretamente, e cada palavra pode resultar em diferentes efeitos.

### Overflow: Hidden

A propriedade `overflow: hidden` é utilizada para retirar a barra de rolagem caso a imagem de fundo seja muito grande, mantendo uma aparência mais limpa e fluida.

### Background-attachment: Fixed

A propriedade `background-attachment: fixed` é crucial para o efeito parallax. Ela faz com que a imagem de fundo fique fixa, tornando o parallax possível ao deslocar o conteúdo sobre ela.

## Considerações Finais:

- O código HTML e CSS cria uma página responsiva e visualmente atraente para a Cafeteria IOS.
- As seções parallax proporcionam uma experiência de navegação envolvente.
- A aplicação de animações suaves contribui para uma transição agradável entre os elementos da página.

<details>
  <summary>
    Referências
  </summary>
  
  - [Anton & Irene](https://antonandirene.com/)
  - [Social King](http://socialking.ru/eng)
  
</details>

