# To Do List

1 - [x] Encontrar o tamanho maximo que pode ser alocado dinamicamente (long int)
2 - [x] Encontrar 25 faixas de tamanho para realizar o teste
3 - [x] Organização das amostras:
 - [x] Valores pseudo aleatorios (em qualquer ordem)
 - [x] Valores em ordem nao decrescente
 - Obs: Em ambos os casos, podem haver valores repetidos
4 - [ ] Resultados da busca:
- [ ] Pior caso (quando k não está no vetor)
- [ ] Quando k encontra-se distante 3/4 do comprimento de A
- [ ] A terceira ocorrencia de k no arranjo (se existir)
5 - [ ] Algoritmos:
 - [x] busca sequencial interativa
 - [x] busca sequencial recursiva
 - [ ] busca sequencial padrão (std::search -> algorithm)
 - [x] busca binária interativa                          // Apenas em arranjos ordenados
 - [x] busca binária recursiva                           // Apenas em arranjos ordenados
 - [x] busca binária padrão (std::bsearch -> cstdlib)    // Apenas em arranjos ordenados
 - [x] busca ternária interativa                         // Apenas em arranjos ordenados
 - [x] busca ternária recursiva                          // Apenas em arranjos ordenados
6 - [ ] Adaptações:
 - [ ] fazer as funções retornarem a 3º ocorrencia (chama a funcao mais 2 vezes com os parametros adequados)
 - [x] incluir um parametro i, para determinada ocorrencia (i = 0 -> primeira, i = 1 -> segunda...)
7 - [ ] Criação de wrappers:
 - [ ] Criar uma nova função para chamar as funções std::search e std::bsearch
8 - [ ] Armazenar as 8 funções (item 5) em um vetor de ponteiros para função (por isso o wrapper), com a mesma assinatura
9 - [x] Receber por linha de comando um valor k, limite de amostras a serem testadas (num_Amostras = 2^i, com i ∈ [5, k+5])
10 - [ ] Gerar um arquivo .dat com os dados para serem plotados no gnuplot
11 - [ ] Armazenar o valor de 100 execuções para cada instância (gerando a média progressiva)
12 - [x] Não alocar os vetores a cada execução, mas alocar uma unica vez com o tamanho máximo
13 - [ ] Gerar um gráfico (n x tempo) para cada algoritmo
14 - [ ] Criação do relatório:
 - [ ] Introdução com o propósito do relatório
 - [ ] Método
  - [ ] Materiais
   - [ ] Configurações da máquina utilizada (processador, memória, placa mãe)
   - [ ] Linguagem de programação
   - [ ] Tipo e versão do SO
   - [ ] Tipo e versão do compilador
   - [ ] Lista dos algoritmos utilizados (com o código)
   - [ ] Cenários considerados
  - [ ] Metodologia
   - [ ] Descrição do método ou procedimento empregado para a geração dos dados
   - [ ] Quais e como as medições foram tomadas para comparação (tempo, passos, memória...)
  - [ ] Resultados Alcançados (Gŕaficos e Tabelas)
  - [ ] Discussão dos Resultados
   - [ ] O que foi descoberto
   - [ ] Quais algoritmos são recomendados para quais cenários
   - Existe um ganho em termos de processamento se dividirmos o arranjo em 3 partes?
    - [ ] Se sim, por que não continuar dividindo-o?
   - Aconteceu algo inesperado nas medições? (picos ou vales nos gráficos) Por que?
   - [ ] Que função matemática melhor se aproxima para descrever o gráfico gerado?
   - É possível estimar o tempo necessário para cada algoritmo executar com 10[ ] 0 milhões de elementos?
   - [ ] A análise empírica é compatível com a análise matemática?
15 - [ ] Entrega
 - [ ] Um arquivo compactado contendo as pastas do projeto e o PDF com o relatório técnico