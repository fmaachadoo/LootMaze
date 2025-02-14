# LootMaze

## Sobre 
Um jogo onde um mago encontra o menor caminho entre seu spawn e o objetivo usando multiplos algoritmos...

Três algoritmos são executados em cada fase do jogo, gerando estatísticas de execução.
Os algoritmos são:

  - A*
  - Dijkstra
  - DFS

O jogo lê os dados do mapa a partir de arquivos png, sendo possível adicionar novos mapas.

## Screenshots
![image](https://github.com/projeto-de-algoritmos/Grafos2_LootMaze/assets/40258400/91eea1d6-d9ba-4162-b91f-ec66a7660485)
![image](https://github.com/projeto-de-algoritmos/Grafos2_LootMaze/assets/40258400/7122b52e-2bd4-49c7-992c-c9995f04bdbb)
![image](https://github.com/projeto-de-algoritmos/Grafos2_LootMaze/assets/40258400/68616b91-638e-490a-add8-12799581e19b)
![image](https://github.com/projeto-de-algoritmos/Grafos2_LootMaze/assets/40258400/eb73b769-c328-4602-9fb8-d54174446d07)



## Instalação 
**Linguagem**: Python<br>
**Framework**: Pygame<br>

Para instalar as dependências basta instalar o pygame em seu ambiente python...

```shell
make install
```

ou

```shell
pip install -r requirements.txt
```

## Uso 

Uma vez que esteja em seu ambiente python com as dependências instaladas basta executar o projeto:

```
make run {nome_do_mapa}.png
```

ou 

```
python -m src.game.main {nome_do_mapa}.png
```

Por exemplo

```
make run map_3.png
```

ou 

```
python -m src.game.main map_3.png
```

### Adicionar novos mapas

Para adicionar novos mapas, é só adicionar uma imagem png em ```src/assets/maps```
E executar o programa com o nome do arquivo adicionado.

> Recomenda-se uma imagem de 32x32 pixels.

> Atente-se às cores do spawn e do objetivo



