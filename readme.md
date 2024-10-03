# Processamento de Linguagem Natural

Projetos desenvolvidos e materiais utilizados durante o curso de capacitação em Processamento de Linguagem Natural, fornecido pelo projeto Tomorrow, uma parceria do instituto de computação ad Universidade Federal da Bahia (UFBA) e a Positivo. Curso ministrado pelo professor [Marlo Vieira](http://buscatextual.cnpq.br/buscatextual/visualizacv.do?id=K4246824U6), meu professor orientador.

## Objetivos do Curso
Compreender e Delimitar a área de Processamento de Linguagem Natural e suas principais tarefas, implementando técnicas clássicas e contemporâneas aos principais problemas da área.

## Objetivos Específicos
* Posicionar a área de Processamento de Linguagem Natural como área interdisciplinar; 
* Compreender níveis de análise linguística e principais tarefas de análise associadas a esses; 
* Construir soluções a algumas tarefas baseado em métodos simbólicos, estatísticos ou neurais;

## Ementa
* Linguística Computacional e PLN;
* Análise Linguística; 
* Classificação de Textos: aplicações a classificação por tópico, análise de sentimentos e outros; 
* Classificação de sequências: aplicações a etiquetagem morfossintática e Reconhecimento de Entidades Nomeadas; 
* Aplicações

## Trabalhos
Para a conclusão do curso, foram propostos quatros trabalhos, sendo eles (com suas respectivas especificações):

### Analisador morfosintático para a língua portuguesa;
Construa um algoritmo para análise morfológica automatizada utilizando a linguagem Python.
O algoritmo deverá receber um texto (cadeia de caracteres) e devolver uma lista de itens, cada qual contendo: a forma textual do token, seu lema, sua classe gramatical e flexões (gênero, número, tempo, etc.).
 - O tagset da tarefa de etiquetagem morfossintática (PoS) será o da Universal Dependencies - o mesmo do exmplo no corpus bosque apresentado
  - As flexões a serem consideradas serão:
     - NOUN: Gênero (Gender) e Número (Number)
     - ADJ: Gênero (Gender) e Número (Number)
     - VERB: Gênero (Gender), Pessoa (Person), Tempo (Tense)  e Forma Verbal (VerbForm)
     - PRON: Gênero (Gender) e Número (Number), Tipo (PronType)
     - DET: Gênero (Gender) e Número (Number)

NÃO DEVERÃO SER UTILIZADOS MODELOS PRÉ-TREINADOS, COMO SPACY OU STANZA PARA IMPLEMENTAR O MÉTODO

### Etiquetagem morfossintática através de modelos de classificação
Implemente um classificador morfossintático através da estratégia de classificação de palavras. Você pode utilizar para tal implementação a classe ClassifierBasedTagger do NLTK, definindo uma função de representação (extração de features) e um classificador qualquer da API nltk.classify

### Classificação de textos através de Modelos de Linguagem baseados na arquitetura Transformer
Com base nos datasets de classificação textual e modelos de linguagem para a língua portuguesa listados na plataforma Huggingface, implemente um classificador textual para uma determinada tarefa.

Atenção, sua implementação DEVE ser baseada na utilização das bibliotecas transformers e datasets, podendo utilizar como infraestrutura básica as bibliotecas Pytorch, Tensorflow ou keras.
 
### Estudo da literatura:
Escolha um artigo recente (último 3 anos) da literatura em Processamento de Linguagem Natural publicado em conferência ou periódico da área que proponha um método a ser aplicado a uma tarefa de PLN e apresente uma descrição do artigos elencando:

- ARTIGO
  * Quem são os autores? de quais universidades
  * Onde foi publicado o artigo? é um veículo de renome na área?

- TAREFA:
   * Qual tarefa/problema está sendo abordado pelo trabalho. tal tarefa é definida dentro do trabalho? Outros trabalhos são referenciados em que a tarefa é apresentada/definida? A tarefa/fenômeno abordada é formalizada ou discutida informalmente?
   * Quais outros autores são referenciados que abordam o mesmo ou problema semelhante?

- ABORDAGEM
   * Qual abordagem é proposta para solucionar a tarefa? a solução é baseada em que estratégias (aprendizagem de máquina, regras, etc.)? Como tais estratégias são empregadas (arquitetura, etc) para construir a solução proposta?
   * O que a literatura relacionada apresenta de diferente da abordagem dos autores? qual a contribuição original dos autores?

- METODOLOGIA
   * Quais dados são utilizados no artigo? como foram obtidos? estão disponíveis?
   * Os autores apresentam experimentos? Como foram projetados? Os resultados são comparados com a literatura? como

-  DISCUSSÃO
   * Os autores apresentam discussão dos resultados?
   * Os erros da abordagem são analisados qualitativamente?
   * Qual a sua impressão sobre o artigo?
