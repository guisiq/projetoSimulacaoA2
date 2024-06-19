# Trabalho de Simulação

[Link do projeto de Simulação](https://github.com/guisiq/projetoSimulacaoA2/)

## **Contexto**

A empresa L.G. Lavagem de Carros atualmente conta com uma equipe de quatro servidores/prestadores de serviços, onde cada um deles é responsável por uma das seguintes atividades:

- Lavagem Simples
- Lavagem Interna
- Aplicação de Cera
- Polimento

Internamente, a empresa divide esses serviços em dois grupos: **Lavagem** (Lavagem Simples e Lavagem Interna) e **Serviços Adicionais** (Aplicação de Cera e Polimento).

## Objetivo

Os donos da empresa desejam aumentar a eficácia de seu processo interno, pois almejam efetuar os atendimentos em um período menor do que os processos atuais permitem. Contudo, esses empresários estão disponibilizando uma nova vaga para um servidor atuar no time de operação do lava-jato. Para isso, solicitaram uma simulação dos seus processos operacionais e desejam saber em qual dos dois grupos de serviço esse novo colaborador deve ser alocado para obter o melhor desempenho da equipe.

## Mapeamento do processo

Para mapear de forma eficaz a simulação que deveria ser realizada  a equipe responsável contruiu dois modelos para mapear todo a cadeia de lavagem de veículos, sendo eles um FLuxograma e um Diagrama ACD.

### Fluxograma

![WhatsApp Image 2024-06-12 at 9.25.39 AM.jpeg](https://github.com/guisiq/projetoSimulacaoA2/blob/master/WhatsApp%20Image%202024-06-12%20at%209.25.39%20AM.jpeg)

### ACD

![WhatsApp Image 2024-06-12 at 7.56.33 AM.jpeg](https://github.com/guisiq/projetoSimulacaoA2/blob/master/WhatsApp%20Image%202024-06-12%20at%207.56.33%20AM.jpeg)

## Cenários

Foi considerado que a chegada de um novo integrante irá reduzir para em 2/3  do tempo atual o tempo de execução do grupo contemplado com o novo colaborador.

- **Processo Atual**

|  | Lavagem Simples | Lavagem Interna | Aplicação de Cera | Polimento |
| --- | --- | --- | --- | --- |
| Tempo de Atraso | Entre 14 e 19 minutos | Entre 8 e 12 minutos  | Entre 6 e 9 minutos  | Entre 12 e 17 minutos |
| Capacidade da fila  | 30 | 30 | 30 | 30 |

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/9932c372-c689-4d3e-b652-be0550ce9f7e/5de6a8bd-277c-49e9-b05e-16e654f476a8/Untitled.jpeg)

**Processo com Novo Integrante No Grupo de Lavagem**

|  | Lavagem Simples  | Lavagem Interna | Aplicação de Cera | Polimento |
| --- | --- | --- | --- | --- |
| Tempo de Atraso | 2/3 do Tempo atual | 2/3 do Tempo atual | Tempo atual | Tempo atual |
| Capacidade da fila  | 30 | 30 | 30 | 30 |

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/9932c372-c689-4d3e-b652-be0550ce9f7e/cea8085f-11d4-416d-a4fc-65b9ccf9a752/Untitled.jpeg)

- **Processo com Novo Integrante do Grupo de Serviços Adicionais**

|  | Lavagem Simples  | Lavagem InternaInterna | Aplicação de Cera | Polimento |
| --- | --- | --- | --- | --- |
| Tempo de Atraso | Tempo atual | Tempo atual | 2/3 do Tempo atual | 2/3 do Tempo atual |
| Capacidade da fila  | 30 | 30 | 30 | 30 |

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/9932c372-c689-4d3e-b652-be0550ce9f7e/ec4b1ec9-4c85-457f-a837-00e561672fd9/Untitled.jpeg)

## Conclusão

Conforme as simulações registradas acima, pode-se notar uma semelhança entre os cenários do Processo Atual e do Processo com Novo Integrante no Grupo de Serviços Adicionais. Contudo, destaca-se o Processo com Novo Integrante no Grupo de Lavagem. Este cenário trouxe uma melhor otimização, obtendo um menor tempo de execução total e uma redução das filas em todo o processo.ht2tps://hexagonal-mars-5e7.notion.site/Trabalho-de-Simula-o-6d3641feff9545528705570805f5c737 
