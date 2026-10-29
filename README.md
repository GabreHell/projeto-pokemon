# Listagem Pokémon

Página de estudo feita com HTML, CSS e JavaScript que exibe cartões de Pokémon com número, imagem animada, tipos e descrição. O botão no cabeçalho alterna entre os temas claro e escuro.

## Como visualizar

Baixe e extraia o ZIP do repositório ou clone-o:

```sh
git clone https://github.com/GabreHell/projeto-pokemon.git
cd projeto-pokemon
```

Abra [index.html](index.html) no navegador, mantendo a pasta `src` no mesmo diretório. Não há dependências para instalar nem etapa de compilação.

A fonte Poppins é carregada pelo Google Fonts e depende de conexão com a internet; as imagens dos cartões estão no próprio repositório.

## Estrutura

- [index.html](index.html): conteúdo dos cartões e cabeçalho.
- [src/css/](src/css/): estilos, reset e barra de rolagem.
- [src/JS/index.js](src/JS/index.js): alternância de tema.
- [src/imagens/](src/imagens/): imagens e animações.

## Escopo

A listagem está definida diretamente no HTML. Não há busca, consulta a uma API ou persistência da preferência de tema após recarregar a página.
