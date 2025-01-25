# simple-paint-kivy
Criei um projeto com Python e Kivy para desenvolver um paint simples, focando em aprender os fundamentos do Kivy. O programa permite desenhar em uma tela interativa com diferentes cores, proporcionando uma abordagem prática para explorar widgets, eventos e construção de interfaces gráficas básicas.

Aplicativo de Paint Simples com Kivy
Este é um aplicativo de paint simples desenvolvido usando Python e o framework Kivy. O projeto foi criado como um exercício de aprendizado para explorar os fundamentos do Kivy, incluindo widgets, manipulação de entrada por toque e elementos gráficos na tela.

Funcionalidades
Desenho Livre: Use o mouse (ou toque) para desenhar linhas e pontos na tela.
Variedade de Cores: O aplicativo utiliza cores HSV aleatórias para cada desenho, tornando o canvas colorido e dinâmico.
Limpar Canvas: Um botão "Clear" permite apagar o desenho atual e começar do zero.
Requisitos
Para executar este projeto, você precisará de:

Python 3.x
Biblioteca Kivy
Instalação
Clone o Repositório:

bash
Copiar
Editar
git clone https://github.com/seuusuario/simple-paint-app.git
cd simple-paint-app
Instale as Dependências:
Use o pip para instalar o framework Kivy, caso ainda não tenha instalado:

bash
Copiar
Editar
pip install kivy
Execute o Aplicativo:
Execute o arquivo Python para iniciar o aplicativo:

bash
Copiar
Editar
python simple_paint.py
Como Funciona
Desenho:

Clique e arraste o mouse para desenhar linhas.
Um ponto é criado no início de cada evento de toque.
Geração de Cores:

Cada traço começa com uma cor HSV aleatória, tornando cada desenho único e vibrante.
Botão "Clear":

Clique no botão "Clear" para limpar o canvas e reiniciar a área de desenho.
Visão Geral do Código
Classe MyPaintWidget
Responsável pela lógica de desenho:

on_touch_down: Desenha um ponto na posição de toque e inicia uma linha.
on_touch_move: Estende a linha enquanto o toque se move pela tela.
Classe MyPaintApp
Configura o aplicativo:

Cria o widget do canvas (MyPaintWidget) e um botão "Clear".
Vincula o botão "Clear" ao método clear_canvas, que limpa o canvas de desenho.
Exemplo de Uso
Abra o aplicativo.
Use o mouse ou toque para desenhar livremente no canvas.
Clique no botão "Clear" para apagar e começar novamente.
Estrutura de Arquivos
arduino
Copiar
Editar
simple-paint-app/
│
├── simple_paint.py     # Arquivo principal do aplicativo
├── README.md           # Documentação do projeto
Melhorias Futuras
Adicionar opções para diferentes tamanhos de pincel.
Incluir mais paletas de cores ou um seletor de cores.
Permitir salvar o desenho como um arquivo de imagem.
Adicionar uma funcionalidade de desfazer/refazer.
Licença
Este projeto é open-source e está disponível sob a Licença MIT. Sinta-se à vontade para modificá-lo e compartilhá-lo.

Agradecimentos
Documentação do Kivy
Python.org
