## buscaTextoParalelo
### Programa de varredura de texto que busca usar todo o processamento de uma máquina. Código escrito em C para a disciplina de processamento paralelo do curso de Ciência da Computação. 
#
### Bibliotecas C utilizadas: **openmp** e **MPI** . A lógica principal que combina as duas bibliotecas pode ser encontrada no arquivo "search.c".
#
Para rodar o aplicativo é necessário estar rodando uma distribuição com terminal linux. Executar o arquivo "Makefile" e após rodar o script "run". O arquivo "texto" pode ser recriado rodando o código "1criar.c". Nele é possível definir qual será o tamanho do arquivo de texto.

A planilha "Speed-up e Eficiência" contém os resultados obtidos comparando a versão paralela final com a versão sequêncial. As configurações do computador também estão descritas nesse arquivo.
