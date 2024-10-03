# Popularidade-de-Objetos
Códigos da Replicação Científica
Este diretório apresenta os códigos da oficina de replicação e os dados brutos e finais.

# Artigo-base da replicação e análise replicada
A seção 6.2 do artigo BitTorrent traffic from a caching perspective aborda a popularidade de objetos, observando que o tráfego do BitTorrent, em contraste com o tráfego da Web, exibe uma menor concentração de referências nos arquivos mais populares. Em vez de uma cauda longa comum em tráfegos da Web, os dados do BitTorrent são melhor modelados por distribuições Weibull ou Log-Normal. Isso impacta diretamente a política de substituição de objetos menos usada com frequência (LFU), que não apresenta o desempenho esperado para sistemas de cache do BitTorrent. A Figura 8 ilustra a popularidade dos objetos nos diferentes workloads do BitTorrent analisados​.

# Fases da replicação e códigos associados
Coletar dados de cada commit feito no repositório. Código getCommits.py;
Para cada programador, calcular a quantidade de dias em que fez pelo menos um commit no repositório. Código getDays.py
Gerar o gráfico com mesma lógica (eixos X e Y) do artigo-base. CódigographActivity
Dados usados coletados e gerados na replicação
Os dados brutos coletados por meio da API estão no arquivo data.json, a coleta foi feita em 24/03/2021. Os dados finais, totalmente processados e prontos para serem exibidos no gráfico, estão no arquivo activity.data.

Lesandro Ponciano (lesandrop at pucminas.br) - PUC Minas
