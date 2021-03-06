# MobileVision

[Link para o aplicativo](mobilevision.mybluemix.net/reconhecer)

MobileVision é um aplicativo de demonstração que reconhece documentos (RG, CNH e Comprovante de Residência) de imagens enviadas por **upload** ou da *internet*, enviando a **URL**. O código pode ser modificado para funcionar com outros classificadores do **Visual Recognition** seguindo os passos abaixo.

## Características
* Visual Recognition: O aplicativo utiliza o visual recognition para reconhecer o conteúdo de imagens. No link [mobilevision.mybluemix.net/reconhecer](mobilevision.mybluemix.net/reconhecer), apenas  reconhece documentos.

* Node-Red: O aplicativo utiliza tem **Node-Red** como seu *back-end*.

## Como Utilizar
(Clique nas setas para ver as imagens)

<details>
   <summary>1. Para utilizar o aplicativo entre no *link*: [mobilevision.mybluemix.net/reconhecer](mobilevision.mybluemix.net/reconhecer).</b></summary>
   <div align="center">
<img src="https://user-images.githubusercontent.com/25907136/29436447-efecf06c-8381-11e7-92eb-2c915006cd6f.jpg" alt="Página inicial">
<p>Imagem 1: Página incial</p></div>
</details>

<details>
   <summary>2. Após entrar no aplicativo, selecione a opção que preferir.</summary>
   <div align="center">
<img src="https://user-images.githubusercontent.com/25907136/29436448-f1e9086a-8381-11e7-88df-6f851a59c95c.jpg" alt="Opções disponíveis">
<p>Imagem 2: Opções disponíveis</p></div>
</details>

<details>
   <summary>3. Envie o arquivo ou URL</summary>
   <div align="center">
<img src="https://user-images.githubusercontent.com/25907136/29436856-13b55262-8384-11e7-9ff3-c01a6fcef414.jpg" alt="Enviando um arquivo" width="50%"><img src="https://user-images.githubusercontent.com/25907136/29436859-19a610b2-8384-11e7-94fe-9dca79027c17.jpg" alt="Enviando uma URL" width="50%">
<p>Imagem 3: Enviando um arquivo (esquerda) e uma URL (direita)</p></div>
</details>

<details>
   <summary>4. Espere a imagem ser processada.</summary>
   <div align="center">
<img src="https://user-images.githubusercontent.com/25907136/29436449-f4411fda-8381-11e7-99ae-e0974e966812.jpg" alt="Resultado">
<p>Imagem 4: Resultado</p></div>
</details>


## Como criar uma demo em sua conta do Bluemix:

1. Crie um **Node-Red** e um serviço de **Visual Recognition** em seu espaço
2. Treine o **Visual Recognition** para reconhecer aquilo que você quer ou utilize os classicadores padrão
3. Copie o conteúdo dentro do arquivo **flow.json**
4. Vá para as configurações e clique em *Import -> Clipboard*
5. Cole o conteúdo copiado no campo e clique em *Import*
6. Configure o nó do Visual Recognition com a sua key e os nós de *change* com o *ID* do seu classificador
