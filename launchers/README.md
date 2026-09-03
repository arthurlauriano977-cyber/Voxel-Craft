# Launchers

Este diretório contém lançadores web e instruções para rodar as versões Eaglercraft (1.8.8 e 1.12.2) integradas como submódulos.

Instruções rápidas:

1. Clone o repositório:

   git clone https://github.com/arthurlauriano977-cyber/Voxel-Craft.git
2. Inicialize e atualize os submódulos (traz os upstreams originais do Eaglercraft):

   git submodule update --init --recursive

3. Abra o lançador no navegador (ex.: launchers/1.8/index.html) rodando um servidor estático simples:

   # com Python 3
   python -m http.server 8000
   # abrir http://localhost:8000/launchers/1.8/

Observação: os builds do cliente Eaglercraft ficam dentro dos submódulos; os lançadores aqui são wrappers que apontam para os builds presentes nos submódulos.
