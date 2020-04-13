# Problema 03 de Sistemas Digitais
A ideia do projeto é criar um programa para plotagem de gráfico em tempo real, pegando dados simulados de um ADS1115

## Objetivos 
- Realizar comunicação interprocessos;
- Protar o gráfico em tempo real;
- Aprender utilizar recursos do SO, por exemplo, o pipe.

## Atividades desenvolvidas 
- Criação de script em C para gerar dados aleatórios;
- Script para plotagem no GNUPlot;


## Como executar 
- Compila e executa o arquivo gerador de dados
```bash
$ gcc geradorDeDados.c -o geradorDeDados -lm
$ ./geradorDeDados
```
- Compila e executa o arquivo de chamada para o GNUPlot
```bash
$ gcc PBL3.c -o pbl
$ ./pbl
```

