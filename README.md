# MobileVision

[Link para o aplicativo](mobilevision.mybluemix.net/reconhecer)

MobileVision é um aplicativo de demonstração que reconhece documentos (RG, CNH e Comprovante de Residência) de imagens enviadas por **upload** ou da *internet*, enviando a **URL**. O código pode ser modificado para funcionar com outros classificadores do **Visual Recognition** seguindo os passos abaixo.

## Características
* Visual Recognition: O aplicativo utiliza o visual recognition para reconhecer o conteúdo de imagens. No link [mobilevision.mybluemix.net/reconhecer](mobilevision.mybluemix.net/reconhecer), apenas  reconhece documentos.

* Node-Red: O aplicativo utiliza tem **Node-Red** como seu *back-end*.

## Como Utilizar
Para utilizar o aplicativo entre no *link*: [mobilevision.mybluemix.net/reconhecer](mobilevision.mybluemix.net/reconhecer).
<div align="center">
<img src="http://www.brightlightpictures.com/assets/images/portfolio/thethaw_header.jpg" alt="Página inicial">
<p>Imagem 1: Página incial</p></div>

Após entrar no aplicativo, selecione a opção que preferir, e envie o arquivo ou URL.
<div align="center">
<img src="http://www.brightlightpictures.com/assets/images/portfolio/thethaw_header.jpg" alt="Opções disponíveis">
<p>Imagem 2: Opções disponíveis</p></div>

Espere a imagem ser processada.
<div align="center">
<img src="http://www.brightlightpictures.com/assets/images/portfolio/thethaw_header.jpg" alt="Resultado">
<p>Imagem 3: Resultado</p></div>

## Como criar uma demo em sua conta do Bluemix:

1. Crie um **Node-Red** e um serviço de **Visual Recognition** em seu espaço
2. Treine o **Visual Recognition** para reconhecer aquilo que você quer ou utilize os classicadores padrão
3. Copie o conteúdo dentro do arquivo **flow.json**
4. Vá para as configurações e clique em *Import -> Clipboard*
5. Cole o conteúdo copiado no campo e clique em *Import*
6. Configure o nó do Visual Recognition com a sua key e os nós de *change* com o *ID* do seu classificador
