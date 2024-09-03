Análise de Odds - Campeonato Brasileiro
Este repositório contém um conjunto de arquivos para a análise das odds disponibilizadas pela Bet365 para os jogos do Campeonato Brasileiro de 2023. O objetivo é comparar essas odds com aquelas calculadas com base em dados históricos, destacando as discrepâncias através de heatmaps e boxplots.

Conteúdo do Repositório
odds bet365.xlsx: Esta planilha contém as odds oferecidas pela Bet365 para os jogos do Campeonato Brasileiro de 2023.

Base de dados - Brasileirão.xlsx: Planilha com a base de dados utilizada para o cálculo das odds. Inclui todos os jogos do Campeonato Brasileiro entre 2012 e 2023, com informações detalhadas de cada partida.

odds_modelo.py: Código em Python responsável por:
Calcular as odds para os jogos do Campeonato Brasileiro de 2023 com base nos dados históricos.
Comparar as odds calculadas com as odds oferecidas pela Bet365.
Gerar heatmaps e boxplots que mostram a magnitude das discrepâncias entre as odds calculadas e as oferecidas pela casa de apostas.

Como Utilizar
Ao rodar o código no Colab, certifique-se de que os arquivos odds bet365.xlsx e Base de dados - Brasileirão.xlsx estão no mesmo diretório que o código odds_modelo.
Execute o script Python: python calculo_odds_e_comparacao.py.
O script processará os dados e gerará os heatmaps e boxplots que aparecerão como um arquivo de imagem no mesmo diretório.

Interpretação do Heatmap
O heatmap gerado destaca as diferenças entre as odds calculadas com base nos dados históricos e aquelas oferecidas pela Bet365. Áreas mais escuras indicam maiores discrepâncias.
Contribuições
Contribuições são bem-vindas! Se você deseja adicionar novas funcionalidades, corrigir bugs ou melhorar a documentação, sinta-se à vontade para abrir um pull request.

Possíveis alterações
É possível calcular verificar as discrepâncias de outros jogos e ligas, bastando obter uma base de dados fidedigna e as odds da Bet365 para os jogos e ligas de interesse.

Contato
Se você tiver alguma dúvida ou sugestão, entre em contato através do email: alexsandroandre050@gmail.com.
