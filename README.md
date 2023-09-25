**!! Atenção: Renomeie o seu repositório para (Tema)_(NomeDoProjeto). !!** 

Temas:
 - Grafos1
 - Grafos2
 - PD
 - D&C
 - Greed
 - Final 
 
 **!! *Não coloque os nomes dos alunos no título do repositório*. Exemplo de título correto: Grafos2_Labirinto-do-Minotauro !!**
 
 (Apague essa seção)

# WayFinder

**Número da Lista**: 1<br>
**Conteúdo da Disciplina**: Grafos1<br>

## Alunos
|Matrícula | Aluno |
| -- | -- |
| 211006957  |  Sebastián Héctor Zuzunaga Rosado |
| xx/xxxxxx  |  xxxx xxxx xxxxx |

## Sobre 
Descreva os objetivos do seu projeto e como ele funciona. 
O objetivo deste projeto é utilizar o algoritmo breadth first search para encontrar o caminho mais curto entre diferentes cidades do Brasil.
- Neste caso, o gráfo é criado usando um diretório python onde os nós são armazenados com seus respectivos vizinhos, cada nó também é uma lista onde os vizinhos estão.
- Para a função de adiciona_nodo, que será usada para criar uma cidade, cria-se uma lista vazia no diretório, a chave desta lista será colocada pelo usuário.
- Para a função de remover_nodo, os vizinhos do nó que queremos remover serão pesquisados, então o nó será removido nas listas dos respectivos vizinhos, e o nó em si será finalmente removido.
- Para a função de verificar_nodo, o nó é procurado no diretório usam a sua chave, se o nó existe retorna 1 se não 0.
- Para a função de adiciona_aresta, usada para criar conexões, um nó A é adicionado à lista de vizinhos de outro nó B, depois o nó B é adicionado à lista de vizinhos do nó A, já que este é um gráfico não direcionado.
- Para a função BFS primeiro se criam 2 listas, uma para armazenar os nodos já visitados e outra que conterá os caminhos percorridos, logo se faz uma verificação, se o nó começo é igual ao final, antes de começar com o loop então já se esta no lugar de destino, logo se inicia um loop, enquanto encontram elementos na fila de caminhos se executa o codigo, se extrai o primeiro caminho da cauda e deste caminho se extrai o primeiro elemento, é adicionado à lista de visitantes e todos os seus vizinhos são adicionados a uma cópia da estrada e, em seguida, este caminho é adicionado à lista, uma vez que chegar ao nó alvo retorna o caminho que alcanço, do contrário não retorna nada.

## Screenshots
Adicione 3 ou mais screenshots do projeto em funcionamento.

## Instalação 
**Linguagem**: Python<br>
**Framework**: Ninguem (por agora)<br>
- **Prerequisitos**:<br>
  Python<br>
  Windows PowerShell<br>
- **Instruções**:<br>
  Abrir o Windows PowerShell<br>
  Usar o comando cd para chegar à pasta que contém o arquivo .py<br>
  Escrever o nome do programa com a extensão . py; neste caso CidadesCaminho.py<br>

## Uso 
Explique como usar seu projeto caso haja algum passo a passo após o comando de execução.

## Outros 
Quaisquer outras informações sobre seu projeto podem ser descritas abaixo.




