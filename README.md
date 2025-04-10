# MLG-Modelos-para-Contagens-com-Excessos-de-Zero

Arquivos relacionados ao trabalho de Modelos Lineares Generalizados, com foco em Modelos para Contagens com Excessos de Zero.

Os biólogos de vida selvagem do estado da Califórnia, nos Estados Unidos, queriam modelar quantos peixes estavam sendo capturados por pescadores em um parque estadual. Os visitantes foram questionados quanto tempo ficaram, quantas pessoas estavam no grupo, se havia crianças no grupo e quantos peixes foram pescados. Alguns visitantes que visitaram o parque não pescaram, mas não há dados sobre se uma pessoa pescou ou não, e como alguns visitantes que pescaram não pegaram nenhum peixe, há excesso de zeros nos dados por causa das pessoas que não pescaram. Foram 250 grupos que foram ao parque e cada grupo foi questionado sobre quantos peixes pescaram (variável resposta count), quantas crianças haviam no grupo (variável explicativa child), quantas pessoas haviam no grupo (variável explicativa persons) e se trouxeram ou não um trailer para o parque (variável explicativa camper).

O arquivo zero-inflated.Rmd mostra o markdown utilizado para o documento final, assim como os códigos utilizados para a análise dos dados. O resultado final do código pode ser visto através do arquivo zero-inflated.pdf

Os arquivos envel_pois_log.txt e envel_nbin_log.txt são usados para adicionar as funções para a criação dos envelopes utilizados no código final. 

O PDF do trabalho apresenta todas as informações relevantes sobre o conjunto de dados, como a modelagem foi feita, interpretações e conclusões. 
