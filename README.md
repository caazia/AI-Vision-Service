# Desafio: Reconhecimento Facil e transformação de imagens em Dados no Azure ML

Iniciaremos acessando o [portal do Azure](https://www.portal.azure.com).

- Criaremos um Recurso (+Create a resource).

 Opção no Menu (Três traços Verticais) ao lado esquerdo que poderá não estar visível.

![Menu](./Outputs/Microsoft-Menu.png)

- Clique para que ele expanda:

![Menu Lateral](./Outputs/Menu-Lateral.png)


- Ou ainda na parte inferior da página você encontrará um Menu com a opção "+ Create a resource"

![Serviços Azure](./Outputs/criarRecurso.png)

- Busque em Categorias "AI + Aprendizado de Máquina (Machine Learning) ou procure pela lupa.

![Categorias IA](./Outputs/IAMachineLearning.png)

- Clique para abrir as opções. Selecione "Criar" em Seriços de IA do Azure (Azure AI Service)

![Seriços Azure IA Criar](./Outputs/ServicosIA.png)

- Preencha os dados do seu Projeto

![Detalhes do Projeto](./Outputs/descreverServico01.png)

- Preencha Nível de Preços : SO.

- Marque a Caixa li e compreendi todos os termos abaixo.
Clique em "Revise + crie (Review +create)

![Detalhes do Projeto](./Outputs/descreverServico02.png)

- Aguarde a finalização e clique em "Create (Criar)"

![Criar Serviço Azure](./Outputs/criacaoServiço.png)

- Serviço criado com sucesso

![Serviço criado com sucesso](./Outputs/implementacaoConcluida.png)


## A segunda etapa será conectar o Serviço que acabamos de criar ao Vision Studio

Acesse o [Vision Studio](https://portal.vision.cognitive.azure.com/?azure-portal=true) .

![Portal Azure Visão](./SegundaEtapa/AzureVision.png)

- Clique em "Ver todos os recursos (View all resources)

![Ver todos os recursos](./SegundaEtapa/AzureVision02.png)

- Selecione o seu recurso criado e clique em "Selecione como recurso padrão (Select as default resource)"

![Selecione o seu Recurso criado](./SegundaEtapa/DefaultRecourse.png)

- Após, clique no "x" no canto superior direito para sair.


## A terceira etapa é testar a funcionalidade do Vision Studio

### Detectar Rostos no Vision Studio

- Clicar na aba face.
- Clicar em detectar rostos em uma imagem.


![Aba Face](./TerceiraEtapa/VisionFace.png)

![Detectar Rostos em uma imagem](./TerceiraEtapa/Face01.png)

- Marque a caixa "Experimente".
- Você pode Inserir uma foto, Tirar uma foto ou utilizar uma das fotos ao lado.

* Teste

Este serviço já vem com algumas amostras de imagens. Porém, submeti uma nova foto:

![Teste Face](./TerceiraEtapa/Face02.png)


* Resultado

Como observado, a informação de detecção de dois rostos foi efetuada.

## Reconhecimento Óptico de Caracteres

Um serviço em que consiste extrair textos nos mais diversos contextos como em fotos, documentos, notas fiscais. Sendo um serviço interessante para utilização em projetos para scanear documentos no geral, otimizando espaço físico e gerando maior agilidade na localização destes arquivos.

![Aba Reconhecimento Óptico de Caracteres](./TerceiraEtapa/VisionCharacterRecognition.png)
![Aba Reconhecimento Óptico de Caracteres 02](./TerceiraEtapa/OpticalCharacter01.png)

- Clicar na aba Reconhecimento Óptico de Caracteres.
- Clicar em Extraia texto de imagens.
- Marque a caixa "Experimente".
- Você pode Inserir uma foto, Tirar uma foto ou utilizar uma das fotos ao lado.

## Teste

Para testar este serviço, submeti uma imagem que eu tinha como arquivo, contendo vários textos com fontes, cores, tamanhos e formatos diferente:


![Teste Texto](./TerceiraEtapa/OpticalCharacter02.jpeg)


## Adicione Legendas às imagens

- Clicar na análise de imagem.
- Clicar em adicione legendas às imagens.

![Aba Análise de Imagem](./TerceiraEtapa/VisionImagemAnalysis.png)

![Adicione Legenda as imagens](./TerceiraEtapa/ImagemAnalysis01.png)

# Teste

Nesta foto, o serviço detecta a estátua de uma mulher segurando uma balnça no topo de um "prédio".

![Teste Descrição de Imagem](./TerceiraEtapa/ImagemAnalysis02.jpeg)

# Considerações Finais

A capacidade do Azure Vision Studio de adicionar legendas e extrair marcas de imagens amplia horizontes na análise de conteúdo visual, possibilitando melhorias significativas em acessibilidade, análise de marca e muito mais. Esses serviços oferecem uma variedade de formas inclusivas que podem ser integradas em projetos para facilitar a vida de todos, sempre respeitando as normas éticas no uso dos dados e da IA.






