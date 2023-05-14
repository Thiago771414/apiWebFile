# Api Web File

Gerenciamento de Arquivos Simplificado

# Sobre o projeto

  O projeto Gerenciamento de Arquivos Simplificado apresenta uma implementação prática para lidar com arquivos em JavaScript de forma simplificada. O objetivo principal é permitir que os usuários selecionem arquivos e realizem diferentes operações com eles, como exibir imagens ou ler conteúdo de arquivos de texto.

Neste projeto, o código fornecido demonstra como lidar com a seleção de arquivos e executar diferentes ações com base no tipo de arquivo selecionado. Ao carregar a página, são definidos os manipuladores de eventos necessários para a funcionalidade.

O botão "Escolher arquivo" é vinculado ao elemento de entrada de arquivo oculto com o ID "arquivos". Quando o botão é clicado, ele aciona o evento btnArquivos.onclick, que por sua vez dispara o clique no elemento de entrada de arquivo, permitindo que o usuário selecione um ou mais arquivos.

O evento arquivos.onchange é acionado quando um arquivo é selecionado. Nesse evento, diferentes ações são realizadas com base no tipo de arquivo selecionado. O exemplo fornecido contém três trechos de código comentados, representando diferentes ações que podem ser executadas.

No primeiro trecho de código, o arquivo selecionado é convertido em uma URL de dados (data URL) usando a classe FileReader. A URL de dados é então utilizada para exibir uma imagem na área de saída, representada pelo elemento com o ID "output". Isso permite que os usuários visualizem a imagem selecionada.

No segundo trecho de código comentado, o arquivo de texto selecionado é lido como uma sequência de caracteres usando a classe FileReader. O conteúdo do arquivo é então exibido na área de saída, novamente representada pelo elemento com o ID "output". Essa abordagem permite que os usuários visualizem o conteúdo de arquivos de texto.

O terceiro trecho de código comentado demonstra duas abordagens alternativas para exibir os nomes dos arquivos selecionados. A primeira abordagem usa o método Array.from() para converter a lista de arquivos em um array, e então o método map() é utilizado para extrair apenas os nomes dos arquivos. Esses nomes são então unidos com a tag <br/> para exibir em linhas separadas na área de saída representada pelo elemento com o ID "arqs".

A segunda abordagem utiliza um loop for tradicional para percorrer cada arquivo selecionado, obtendo seus nomes individualmente e exibindo-os na área de saída.

Ao explorar este projeto, você terá a oportunidade de aprender como lidar com a seleção de arquivos e realizar diferentes ações com eles usando JavaScript. Você poderá visualizar imagens selecionadas, ler o conteúdo de arquivos de texto e exibir os nomes dos arquivos selecionados.

Aproveite essa abordagem simplificada para aprimorar suas habilidades no desenvolvimento de recursos de gerenciamento de arquivos em suas aplicações e proporcione aos usuários uma experiência mais interativa e personalizada.

## Layout API WEB File
![Api Web File](https://github.com/Thiago771414/imagensProjetos/blob/main/slices/mobile/apiWebFile.png)

## Vídeo de demonstração
[[Vídeo de demonstração]](https://youtu.be/oD97HRID5As)

# Tecnologias utilizadas

## Front end
- Java Script, HTML

# Autor

Thiago Reis Lima

https://www.linkedin.com/in/thiago-lima-2a5896166/
