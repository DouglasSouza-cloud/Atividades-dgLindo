# Sistema-de-velocidade-dgLindo
Sistema de Velocidade

Este é um programa simples em Python que permite ao usuário inserir velocidades de um motor, calcula a média, a maior, a menor e a soma dessas velocidades, e exibe um relatório final. O usuário pode optar por reiniciar o processo ou finalizar o programa.

Funcionalidades

Entrada de Velocidades: O usuário insere 5 velocidades de motor. Se um valor inválido (como um número negativo ou não inteiro) for inserido, o programa solicitará uma nova entrada.

Cálculos:

Média das velocidades.

Maior velocidade.

Menor velocidade.

Soma das velocidades inseridas.

Reinício ou Finalização: Após exibir o relatório final, o programa pergunta ao usuário se ele deseja reiniciar o processo ou finalizar o programa. Se reiniciar, há um temporizador de 2 segundos antes de começar novamente.

Como usar

Clone este repositório para sua máquina local:

git clone https://github.com/seu-usuario/sistema-de-velocidade.git

Navegue até o diretório do projeto:

cd sistema-de-velocidade

Execute o código Python:

python sistema_velocidade.py

O programa pedirá para inserir as velocidades do motor. Após inserir as 5 velocidades, ele exibirá o relatório final.

Você pode escolher se deseja reiniciar o processo ou finalizar o programa.

Como funciona

O programa solicita que o usuário insira 5 velocidades, garantindo que as entradas sejam válidas (não negativas).

Calcula a média, a maior, a menor e a soma das velocidades.

Mostra um relatório com essas informações.

Após o relatório, o usuário pode optar por reiniciar o processo ou finalizar o programa. Se escolher reiniciar, o programa espera 2 segundos antes de começar novamente.

Exemplo de Execução
=== Sistema de Velocidade ===

Insira velocidade do motor: 50
Insira velocidade do motor: 60
Insira velocidade do motor: 70
Insira velocidade do motor: 80
Insira velocidade do motor: 90

===Relatório final===

Velocidades inseridas:  [50, 60, 70, 80, 90]

Média Aritmética das velocidades:
70.0

Maior velocidade:
90

Menor velocidade:
50

Valor total das velocidades:
350

Deseja refazer? s/n:
s
Reiniciando programa...
Requisitos

Python 3.x

Como Contribuir

Fork este repositório.

Crie uma branch para sua feature (git checkout -b feature/nova-feature).

Faça suas alterações.

Commit suas alterações (git commit -am 'Adiciona nova feature').

Faça push para a branch (git push origin feature/nova-feature).

Abra um Pull Request.