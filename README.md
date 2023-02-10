# Counting-Stars-with-OpenCV

PARA EXECUTAR O PROGRAMA VOCÊ PRECISA:

1 - OpenCV instalado:

```
$ sudo apt install libopencv-dev
```

2 - Compilar o código da seguinte forma:

```
$ g++ contandoEstrelas.cpp -o contandoEstrelas `pkg-config --cflags --libs opencv4`
```

3 - Executar o código da seguinte forma (onde Stars.png é a imagem do céu com estrelas):

```
$ ./contandoEstrelas Stars.png
```
