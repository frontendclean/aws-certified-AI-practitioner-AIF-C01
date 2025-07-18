# Guia para o AWS Certified AI Practitioner (AIF-C01)

![Tela inicial](./assets/img/AI-Practitioner.png)

Este repositório foi criado para ajudar quem está se preparando para a certificação **AWS Certified AI Practitioner (AIF-C01)**. O foco é compartilhar **recursos gratuitos**, **explicações simples** e **dicas práticas** para quem está começando na nuvem AWS.

## Recursos de Estudo

### 1. **Guia do exame** 
- [AWS Guia do exame](https://d1.awsstatic.com/onedam/marketing-channels/website/aws/en_US/certification/approved/pdfs/docs-ai-practitioner/AWS-Certified-AI-Practitioner_Exam-Guide.pdf)
  > Guia oficial da AWS.

### 2. **Cursos gratuitos**
- [AWS Skill Builder](https://www.aws.training/Details/Curriculum?id=20685)
  > Curso oficial e gratuito da AWS. Ideal para começar.

### 3. **Simulados e testes**

- [Simula+ (Criado por @frontendclean) GRATUITO](https://simulaplus.com.br/)
  > Plataforma com diversas questões e simulados para praticar.

---

## O que estudar (+15 tópicos)

### Menu 

- [Inteligência Artificial (IA)](#inteligência-artificial-ia)
- [Aprendizado de Máquina (ML)](#aprendizado-de-máquina-ml)
- [Deep Learning](#deep-learning)
- [Diferença entre IA, ML e Deep Learning](#diferença-entre-ia-ml-e-deep-learning)
- [Modelo](#modelo)
- [Visão Computacional](#visão-computacional)
- [Inferência](#inferência)
- [Principais tipos de dados](#principais-tipos-de-dados)
- [Processamento de Linguagem Natural (PLN)](#processamento-de-linguagem-natural-pln)
- [Modelo de Linguagem Ampla](#modelo-de-linguagem-ampla)
- [Aprendizagem Supervisionada](#aprendizagem-supervisionada)
- [Aprendizagem Não Supervisionada](#aprendizagem-não-supervisionada)
- [Diferença entre supervisionado e não supervisionado](#diferença-entre-supervisionado-e-não-supervisionado)
- [Aprendizagem por Reforço](#aprendizagem-por-reforço)
- [Diferença entre Supervisionado, Não supervisionado e Por reforço](#diferença-entre-supervisionado-não-supervisionado-e-por-reforço)

---

### Inteligência Artificial (IA)

Inteligência Artificial (IA) é um ramo da ciência da computação que cria sistemas capazes de imitar a inteligência humana — como aprender, raciocinar, tomar decisões e resolver problemas.

Em outras palavras: é fazer máquinas "pensarem" ou "agirem" de forma parecida com humanos.

#### Para que serve

A IA é usada para automatizar tarefas, analisar dados, tomar decisões e interagir com seres humanos de maneira mais inteligente.

#### Casos de uso

| Área | Exemplo de uso |
|:------:|:------:|
| Saúde | Diagnóstico por imagem, apoio a decisões médicas |
| Financeiro | Análise de crédito, detecção de fraudes |
| E-commerce | Recomendação de produtos, atendimento via chatbot |
| Indústria | Manutenção preditiva de máquinas |
| Transporte | Carros autônomos, rotas inteligentes |
| Marketing | Análise de sentimentos, segmentação de clientes |

#### Vantagens

  - Automatização de tarefas repetitivas
    - IA pode assumir trabalhos cansativos e repetitivos, liberando humanos para tarefas mais criativas ou estratégicas.
  - Maior velocidade e precisão
    - Sistemas de IA analisam grandes volumes de dados em segundos, com menos chance de erro.
  - Decisões baseadas em dados
    - Ela ajuda empresas e governos a tomarem decisões melhores com base em dados em tempo real.
  - Disponibilidade 24/7
    - Chatbots, assistentes virtuais e serviços automáticos funcionam o tempo todo, sem pausa.
  - Personalização
    - Sistemas inteligentes adaptam serviços conforme o perfil do usuário (ex: Netflix, Spotify, Amazon).

---

### Aprendizado de Máquina (ML)

É um tipo de Inteligência Artificial que permite que sistemas aprendam automaticamente a partir de dados, sem serem programados explicitamente para cada tarefa.

Em vez de programar todas as regras, o ML detecta padrões nos dados e usa esses padrões para fazer previsões ou tomar decisões.

#### Para que serve

O ML é usado para resolver problemas complexos e tomar decisões com base em grandes volumes de dados. Ele é ideal para situações em que:

  - Regras são difíceis de definir manualmente
  - Há muito dado histórico disponível
  - O sistema precisa melhorar ao longo do tempo

#### Casos de uso

| Área | Aplicação |
|:------:|:------:|
| Saúde | Prever doenças com base em exames e histórico |
| Bancos | Detectar fraudes em tempo real |
| E-commerce | Recomendação de produtos personalizados |
| Agronegócio | Previsão de safra baseada no clima e solo |
| TI | Detecção automática de falhas em sistemas |

#### Vantagens

  - Melhora contínua
    - Modelos de ML aprendem com novos dados e podem se tornar mais precisos com o tempo.
  - Tomada de decisão inteligente
    - Ajuda empresas a prever comportamentos, tendências e resultados futuros com base em dados históricos.
  - Eficiência em tarefas complexas
    - ML resolve problemas que seriam muito difíceis ou demorados para programar manualmente.
  - Detecção de padrões invisíveis ao olho humano
    - Modelos conseguem identificar correlações em grandes volumes de dados que humanos não perceberiam.
  - Automatização com inteligência
    - Melhora a automação, tornando sistemas adaptativos e mais eficientes (ex: carros autônomos, assistentes de voz).

---

### Deep Learning

Deep Learning (Aprendizado Profundo) é um subconjunto do Machine Learning, baseado em redes neurais artificiais com muitas camadas (por isso o "deep" = profundo).

Ele simula o funcionamento do cérebro humano, com "neurônios artificiais" organizados em camadas interligadas.

Deep Learning é Machine Learning com redes neurais profundas, capaz de resolver problemas ainda mais complexos — especialmente quando há muitos dados e alta complexidade (ex: imagens, voz, linguagem natural).

#### Para que serve

É usado quando tarefas exigem interpretação de informações não estruturadas, como imagem, vídeo, áudio ou texto.

#### Casos de uso

| Área | Aplicação |
|:------:|:------:|
| Visão Computacional | Reconhecimento facial, detecção de objetos, OCR |
| Processamento de Linguagem Natural (NLP) | Tradução automática, chatbots, análise de sentimentos |
| Reconhecimento de voz | Assistentes virtuais como Alexa, Siri |
| Veículos autônomos | Identificação de pedestres, placas, sinais |
| Geração de conteúdo | Imagens com IA, texto, voz, vídeo (ex: GPT, DALL·E) |

#### Vantagens

  - Alta precisão
    - Quando treinado com muitos dados, pode superar humanos em algumas tarefas específicas (ex: diagnóstico por imagem).
  - Aprende recursos automaticamente
    - Não precisa de muita engenharia manual de dados — o modelo “descobre” os padrões relevantes.
  - Funciona com dados não estruturados
    - É excelente para áudio, imagem, vídeo e texto, que são dados difíceis para algoritmos tradicionais.
  - Avanços em IA Generativa
    - É a base para modelos como GPT, DALL·E, Stable Diffusion, Midjourney, entre outros.

---

### Diferença entre IA, ML e Deep Learning


#### Inteligência Artificial (IA)

É o conceito mais amplo. Engloba qualquer técnica que permita a uma máquina simular inteligência humana — como tomar decisões, resolver problemas, reconhecer padrões.

##### Exemplo

  - Jogar xadrez contra um humano
  - Um chatbot simples baseado em regras
  - Reconhecer uma voz ou rosto

#### Machine Learning (ML)

É um subconjunto da IA. Refere-se a métodos que permitem que as máquinas aprendam com dados, em vez de serem programadas com todas as regras.

##### Tipos

  - Aprendizado supervisionado
  - Aprendizado não supervisionado
  - Aprendizado por reforço

##### Exemplo

  - Um sistema que analisa dados de crédito e aprende a prever inadimplência


#### Deep Learning (DL)

É um subconjunto do ML. Usa redes neurais artificiais profundas para aprender padrões complexos — especialmente em dados como imagens, texto e áudio.

##### Exemplo

  - Um modelo que traduz texto entre idiomas automaticamente
  - Reconhecimento facial em fotos
  - Geração de imagens ou textos com IA (como o ChatGPT)

#### Comparação

| Categoria | Exemplo simples | Precisa de dados? | Usa redes neurais? | Nível de complexidade |
|:------:|:------:|:------:|:------:|:------:|
| IA | Robô que joga damas | Nem sempre | Não necessariamente | Baixo a alto |
| ML | Sistema que prevê vendas | Sim | Opcional | Médio |
| Deep Learning | Modelo que reconhece rostos em fotos | Sim, muitos dados | Sim | Alto |

---

### Modelo

Um modelo é um programa treinado para reconhecer padrões em dados e fazer previsões ou decisões automaticamente.

  - É o resultado do processo de aprendizado de máquina.

Ele aprende com exemplos (dados) durante o treinamento e, depois disso, pode ser usado para inferência (fazer previsões com novos dados).

#### Como funciona 

  1. Você fornece dados de entrada (ex: fotos, texto, números)
  2. O modelo aprende os padrões a partir desses dados (durante o treinamento)
  3. Ele gera uma saída (ex: “isso é um cachorro”, “esse cliente vai sair da empresa”)

#### Exemplo 

Imagine que você quer prever se um e-mail é spam ou não-spam:

  1. Você coleta milhares de e-mails rotulados
  2. Treina um modelo de classificação
  3. Depois, usa esse modelo para analisar novos e-mails automaticamente

#### Tipos 

| Tipo de Modelo | Função |
|:------:|:------:|
| Classificação | Decide entre categorias (ex: spam ou não) |
| Regressão | Prediz um valor numérico (ex: preço de casa) |
| Clustering | Agrupa dados semelhantes (ex: segmentar clientes) |
| Redes Neurais | Base de modelos mais avançados, como Deep Learning |

#### Vantagens

| Vantagem | Explicação |
|:------:|:------:|
| Automatizam decisões | O modelo pode tomar decisões com base em dados em tempo real |
| Rápidos e escaláveis | Um modelo pode processar milhares de entradas por segundo |
| Aprendem com o tempo | Podem ser atualizados com novos dados para melhorar o desempenho |
| Detectam padrões invisíveis | Encontram correlações que humanos não perceberiam |

---

### Visão Computacional

É uma área da Inteligência Artificial que permite que máquinas “vejam” e entendam imagens ou vídeos, de forma semelhante (ou até superior) ao olho humano.

É a tecnologia que permite a um computador identificar, interpretar e agir com base em informações visuais.

#### Para que serve

Ela é usada para analisar, classificar, detectar ou interpretar imagens e vídeos automaticamente.

| Área | Aplicações de Visão Computacional |
|:------:|:------:|
| Segurança | Reconhecimento facial, monitoramento por câmeras |
| Saúde | Diagnóstico de imagens médicas (ex: raios-X, tomografias) |
| Agronegócio | Drones detectando pragas ou qualidade da plantação |
| Indústria | Detecção de falhas em peças na linha de produção |
| E-commerce | Pesquisa por imagem (ex: “buscar por foto”) |
| Veículos autônomos | Leitura de sinais de trânsito, pedestres, obstáculos |

#### Vantagens

  - Automatiza tarefas visuais
    - Elimina a necessidade de inspeções manuais demoradas e propensas a erro.
  - Alta velocidade e precisão
    - Analisa milhares de imagens ou quadros de vídeo por segundo com alta acurácia.
  - Funciona 24/7
    - Ideal para ambientes industriais, monitoramento, vigilância e processos contínuos.
  - Reduz custos operacionais
    - Substitui ou complementa processos manuais, reduzindo mão de obra e erros humanos.
  - Detecta padrões sutis
    - Identifica detalhes que o olho humano pode não perceber — útil na medicina e indústria.

#### Serviços AWS para Visão Computacional

| Serviço | O que faz |
|:------:|:------:|
| Amazon Rekognition | Detecta objetos, rostos, texto, cenas e atividades em imagens e vídeos |
| SageMaker (com modelos próprios) | Treinamento personalizado de modelos de visão |
| Amazon Lookout for Vision | Detecta anomalias em imagens industriais automaticamente |
| AWS Panorama | Roda modelos de visão computacional localmente em câmeras (edge computing) |

---

### Inferência

Na área de Machine Learning, inferência é o processo de usar um modelo treinado para fazer previsões com novos dados.

  - Treinamento: o modelo aprende com dados históricos
  - Inferência: o modelo é usado para prever algo novo (ex: "Esse cliente vai cancelar?")

Na prática, inferência na significa usar um modelo de IA/ML treinado para fazer previsões em produção, usando serviços e recursos da AWS.

#### Para que serve

Serve para aplicar modelos de IA já treinados em ambientes reais. Por exemplo:

| Exemplo | Inferência na prática |
|:------:|:------:|
| Reconhecimento de imagem | Enviar uma foto para o modelo e receber a classificação (“gato” ou “cachorro”) |
| Análise de sentimentos | Enviar um texto e obter se é “positivo”, “neutro” ou “negativo” |
| Previsão de vendas | Prever a demanda da próxima semana com base em dados históricos |


#### Serviços para Inferência

| Serviço | Finalidade |
|:------:|:------:|
| Amazon SageMaker | Hospedagem de modelos com endpoints para inferência em tempo real ou em lote |
| Amazon Bedrock | Usar modelos de fundação (como Claude, Jurassic, Titan) para inferência com prompts |
| AWS Lambda + modelo | Inferência rápida sem servidor, ideal para chamadas esporádicas |
| Amazon EC2 Inf1/Inf2 | Instâncias otimizadas para inferência de alto desempenho usando chips AWS Inferentia |
| Amazon Comprehend, Rekognition, Polly etc. | Serviços prontos que realizam inferência diretamente (sem você treinar o modelo) |

#### Vantagens

  - Escalabilidade
    - Infraestrutura automática para lidar com muitos pedidos simultâneos.
  - Baixa latência
    - Respostas rápidas, mesmo com modelos complexos.
  - Custo-benefício
    - Você paga pelo uso, e pode escolher instâncias otimizadas (ex: Inf1, Inf2) para reduzir o custo da inferência.
  - Flexibilidade
    - Escolha entre inferência em tempo real (para apps) ou em lote (para análises periódicas).
  - Integração fácil
    - Com outros serviços AWS: API Gateway, Lambda, S3, DynamoDB, etc.

#### Tipos

| Tipo | Descrição | Exemplo |
|:------:|:------:|:------:|
| Tempo real | O modelo responde imediatamente | Chatbots, detecção em vídeo |
| Em lote | O modelo processa grandes volumes de uma vez só | Análise de milhares de relatórios por noite |

---

### Principais tipos de dados

Tipos de dados são fundamentais, pois são eles que alimentam os modelos.


#### Dados Estruturados

Dados organizados em tabelas, com linhas e colunas — fáceis de armazenar e consultar.

  - Planilhas (Excel)
  - Bancos de dados (MySQL, Amazon RDS, Redshift)
  - Dados de vendas, clientes, transações

Usado em: previsão de demanda, análise de churn, classificação de risco

#### Dados Não Estruturados

Dados que não seguem um formato fixo — difíceis de analisar diretamente com ferramentas tradicionais.

  - Imagens (JPG, PNG)
  - Vídeos (MP4)
  - Textos (PDF, e-mails, posts de redes sociais)
  - Áudio (gravações, voz)

Usado em: visão computacional, processamento de linguagem natural (NLP), reconhecimento de fala

#### Dados Semiestruturados

Dados com alguma organização, mas não tão rígida quanto tabelas.

  - JSON, XML
  - Logs de aplicativos
  - Arquivos de sensores IoT

Usado em: análises de comportamento, detecção de padrões em sistemas

#### Dados rotulados vs. não rotulados

| Tipo | Descrição | Exemplo |
|:------:|:------:|:------:|
| Rotulados | Dados com a "resposta certa" | Imagens com o rótulo “gato” ou “cachorro” |
| Não rotulados | Dados brutos, sem classificação | Textos ou imagens sem descrição |

Esses dois tipos definem o tipo de aprendizado de máquina:

  - Supervisionado = dados rotulados
  - Não supervisionado = dados não rotulados

#### Para que serve

  - Treinar modelos (aprender padrões)
  - Testar e validar modelos
  - Realizar inferência (usar o modelo treinado com novos dados)
  - Aprimorar continuamente os modelos com novos dados

#### Vantagens

| Vantagem | Descrição |
|:------:|:------:|
| Melhor escolha de modelo | Modelos diferentes funcionam melhor com tipos de dados diferentes |
| Redução de custos | Processar só o necessário evita gastos excessivos |
| Melhor desempenho | Dados bem organizados = modelos mais eficientes e precisos |
| Maior controle e segurança | Saber que tipo de dado está lidando ajuda a proteger informações sensíveis (ex: dados de saúde) |

---

### Processamento de Linguagem Natural (PLN)

PLN é uma área da Inteligência Artificial que permite que máquinas entendam, interpretem, gerem e respondam à linguagem humana, seja falada ou escrita.

Em resumo: é a tecnologia por trás de chatbots, assistentes de voz, tradutores automáticos e ferramentas como o ChatGPT.

#### Para que serve

O PLN é usado para analisar, extrair significado e interagir com linguagem natural (textos, comandos de voz, perguntas, etc).

| Área | Aplicações de PLN |
|:------:|:------:|
| Atendimento ao cliente | Chatbots, assistentes virtuais (ex: Alexa, Siri) |
| Análise de sentimentos | Identificar emoções em comentários, redes sociais |
| Tradução automática | Tradutores em tempo real (ex: Amazon Translate) |
| Classificação de texto | Detectar spam, categorizar e-mails ou documentos |
| Resumo e extração de texto | Resumir textos longos ou extrair informações importantes |
| Reconhecimento de voz | Converter fala em texto (ex: Amazon Transcribe) |

#### Vantagens

  - Interação mais humana
    - Permite que usuários se comuniquem com máquinas usando linguagem comum, sem precisar de comandos técnicos.
  - Automatiza tarefas manuais
    - Classificação de e-mails, análise de feedbacks e criação de relatórios podem ser feitas automaticamente.
  - Melhora a experiência do usuário
    - Chatbots inteligentes e interfaces de voz tornam os serviços mais acessíveis e rápidos.
  - Escalável e consistente
    - Consegue lidar com milhares de textos ou conversas por minuto, com a mesma qualidade.
  - Apoia decisões
    - Analisa textos para extrair tendências, opiniões e temas relevantes em grandes volumes de informação.

#### Serviços da AWS relacionados

| Serviço AWS | O que faz |
|:------:|:------:|
| Amazon Comprehend | Detecta sentimentos, entidades, linguagem, tópicos em textos |
| Amazon Translate | Tradução automática de idiomas |
| Amazon Transcribe | Transforma voz em texto |
| Amazon Lex | Criação de chatbots com compreensão de linguagem |
| Amazon Bedrock | Permite gerar texto com IA generativa (usando modelos como Anthropic, AI21, Titan) |

---

### Modelo de Linguagem Ampla

Um LLM (Modelo de Linguagem Ampla) é um tipo de modelo de IA treinado com enormes volumes de texto para entender, gerar, traduzir, resumir ou responder linguagem humana com alto nível de coerência.

São redes neurais profundas (deep learning) que aprendem padrões da linguagem com bilhões de parâmetros.

#### Exemplos

  - ChatGPT (OpenAI)
  - Claude (Anthropic)
  - LLaMA (Meta)
  - Amazon Titan Text (AWS)
  - Gemini (Google)
  - Mistral, Cohere, entre outros

#### Para que serve

| Área | Exemplos de uso |
|:------:|:------:|
| Atendimento | Chatbots inteligentes, assistentes virtuais (ex: Alexa com Bedrock) |
| Geração de conteúdo | Escrita de textos, resumos, e-mails, roteiros |
| Programação | Geração e correção de código (ex: Amazon CodeWhisperer) |
| Pesquisa e consulta | Assistência com perguntas em linguagem natural |
| Tradução e adaptação | Texto multilíngue, ajuste de tom ou estilo |
| Análise de texto | Compreensão de contexto, classificação, sentimento, etc. |

#### Vantagens

  - Compreensão profunda da linguagem
    - Entendem contexto, ambiguidade, ironia e relações complexas entre palavras e frases.
  - Versatilidade
    - Um mesmo modelo pode ser usado para muitas tarefas: responder perguntas, resumir, escrever, classificar, etc.
  - Geração de conteúdo humano-like
    - Criam textos naturais, bem escritos e contextualmente relevantes.
  - Adaptação e personalização
    - Podem ser ajustados (via prompt ou fine-tuning) para se comportar de forma específica a diferentes necessidades.
  - Melhora produtividade
    - Auxiliam humanos em tarefas repetitivas ou criativas, economizando tempo.

#### LLMs na AWS

A AWS oferece LLMs prontos via Amazon Bedrock, uma plataforma para usar modelos fundacionais de diversos provedores com segurança e escalabilidade.

| Plataforma | LLMs disponíveis |
|:------:|:------:|
| Amazon Bedrock | Claude (Anthropic), Titan (Amazon), Jurassic (AI21), Mistral, Cohere, Meta LLaMA 3 |

---

### Aprendizagem Supervisionada

Aprendizagem supervisionada (ou Supervised Learning) é um tipo de aprendizado de máquina onde o modelo é treinado com dados que já têm as respostas certas (rótulos).

Ou seja: o modelo "aprende com exemplos" que já contêm o que está certo, e depois tenta aplicar esse conhecimento a novos dados.

#### Exemplo 

Se você quer treinar um modelo para classificar e-mails como spam ou não-spam, você fornece ao modelo:

  - O conteúdo dos e-mails (dados de entrada)
  - A informação se é spam ou não (rótulo)

Assim, o modelo aprende o que diferencia um e-mail spam de um normal.

#### Para que serve

Serve para fazer previsões, classificações e decisões com base em dados históricos rotulados.

| Aplicação | O que faz |
|:------:|:------:|
| Diagnóstico médico | Prevê doenças com base em exames anteriores rotulados |
| Análise de crédito | Determina risco com base no histórico de clientes |
| Detecção de fraude | Classifica transações como legítimas ou suspeitas |
| Recomendação de produtos | Prevê o que o usuário pode gostar, com base no comportamento anterior |

#### Vantagens

  - Alta precisão
    - Como o modelo aprende com exemplos rotulados, tende a ser mais preciso quando bem treinado.
  - Facilidade de avaliação
    - Você pode medir o quão bom o modelo é, porque conhece as respostas corretas.
  - Aplicação ampla
    - Serve para uma enorme variedade de problemas do mundo real: previsão, classificação, recomendação, etc.
  - Interpretação clara
    - Algoritmos supervisionados como regressão linear e árvores de decisão são mais fáceis de entender e explicar.

---

### Aprendizagem Não Supervisionada

Aprendizagem não supervisionada (ou Unsupervised Learning) é um tipo de aprendizado de máquina onde o modelo é treinado com dados que não possuem rótulos (respostas corretas).

O modelo explora os dados por conta própria para encontrar padrões, agrupamentos ou estruturas escondidas.

#### Exemplo 

Imagine que você tem dados de clientes (idade, renda, localização), mas não sabe nada sobre o perfil deles.

Com aprendizagem não supervisionada, o modelo pode agrupar clientes semelhantes automaticamente, revelando segmentos de mercado (ex: jovens urbanos com alta renda).

#### Para que serve

  - Descobrir padrões ocultos nos dados
  - Agrupar dados semelhantes
  - Reduzir a dimensionalidade (complexidade) dos dados
  - Exploração de dados sem supervisão humana

| Aplicação | O que faz |
|:------:|:------:|
| Segmentação de clientes | Agrupa clientes com comportamentos parecidos |
| Detecção de anomalias | Identifica padrões fora do comum (ex: fraudes) |
| Organização de documentos | Agrupa textos por tema automaticamente |
| Recomendação de conteúdo | Descobre preferências parecidas entre usuários |

#### Vantagens 

  - Funciona sem rótulos
    - Você não precisa rotular os dados manualmente — isso economiza tempo e dinheiro.
  - Descobre insights escondidos
    - Encontra padrões que humanos talvez não perceberiam.
  - Flexível e exploratória
    - Boa para análises iniciais e descoberta de conhecimento em dados desconhecidos.
  - Redução de dimensionalidade
    - Técnicas como PCA ajudam a simplificar dados complexos para visualização e análise.

#### Na AWS

Serviços como o Amazon SageMaker também permitem aplicar algoritmos não supervisionados, como K-Means, para tarefas de agrupamento ou detecção de padrões.

#### Principais algoritmos

| Algoritmo | O que faz |
|:------:|:------:|
| K-Means | Agrupa dados semelhantes (clustering) |
| DBSCAN | Agrupamento baseado em densidade |
| PCA (Análise de Componentes Principais) | Reduz a dimensionalidade dos dados |
| Autoencoders | Compressão e reconstrução de dados em Deep Learning |

---

### Diferença entre supervisionado e não supervisionado

| Aspecto | Supervisionado | Não Supervisionado |
|:------:|:------:|:------:|
| Dados rotulados | Sim | Não |
| Tipo de tarefa | Previsão, classificação | Agrupamento, descoberta de padrões |
| Exemplo | Prever se um cliente vai cancelar | Agrupar clientes por perfil |
| Avaliação | Fácil (com respostas) | Mais difícil (sem respostas certas) |

---

### Aprendizagem por Reforço

Aprendizagem por reforço é um tipo de aprendizado onde um agente (o modelo) toma decisões em um ambiente com base em tentativa e erro, recebendo recompensas ou punições a cada ação.

O agente aprende sozinho a escolher as melhores ações ao longo do tempo, com base nas recompensas acumuladas.

#### Exemplo 

Imagine treinar um robô para andar:

  1. Ele tenta dar passos (ações).
  2. Se cai, recebe punição (recompensa negativa).
  3. Se anda corretamente, recebe recompensa.
  4. Com o tempo, aprende quais movimentos funcionam melhor.

#### Para que serve

É usado para resolver problemas onde há uma sequência de decisões e o objetivo é maximizar a recompensa total com o tempo.

| Aplicação | Como o RL atua |
|:------:|:------:|
| Jogos (ex: xadrez, Go, videogames) | Aprende a jogar melhor a cada partida |
| Robótica | Aprende a andar, pegar objetos, evitar obstáculos |
| Carros autônomos | Aprende a dirigir evitando colisões e seguindo regras |
| Finanças | Aprende a otimizar decisões de investimento |
| Recomendações | Adapta sugestões com base nas reações dos usuários |

#### Vantagens 

  - Aprende com a experiência
    - O agente melhora com a prática, mesmo sem saber a resposta correta.
  - Adapta-se a ambientes dinâmicos
    - Ideal para cenários que mudam com o tempo ou que envolvem interação contínua.
  - Maximiza o desempenho a longo prazo
    - O foco é acumular recompensas ao longo do tempo, não apenas fazer boas escolhas imediatas.
  - Toma decisões sequenciais
    - Funciona bem quando uma decisão afeta o que acontece depois — como em jogos ou navegação.

#### Componentes principais do RL

| Componente | Função |
|:------:|:------:|
| Agente | Quem toma as decisões |
| Ambiente | Onde o agente interage |
| Estado | Situação atual no ambiente |
| Ação | Escolha feita pelo agente |
| Recompensa | Feedback que guia o aprendizado |
| Política | Estratégia que o agente aprende (como agir) |

#### Na AWS

A AWS oferece suporte a Aprendizagem por Reforço via:

  - Amazon SageMaker RL: Integra ambientes como OpenAI Gym e simulações 3D para treinar agentes em tarefas complexas.
  - Permite treinar e testar agentes de forma escalável usando EC2, containers e clusters.

---

### Diferença entre Supervisionado, Não supervisionado e Por reforço

| Tipo de aprendizado | Tem rótulos? | Tem feedback? | Aprende a... |
|:------:|:------:|:------:|:------:|
| Supervisionado | Sim | Sim (resposta certa) | Prever resultado |
| Não supervisionado | Não | Não | Descobrir padrões |
| Por reforço | Não direto | Sim (recompensa) | Tomar decisões sequenciais |

---

## Documentações para outras certificações AWS

- [Guia para AWS Certified Cloud Practitioner](https://github.com/frontendclean/aws-practitioner-CLF-C02)

---

## Dicas Finais

- Revise os conceitos, não decore.
- Faça simulados com foco em entender o **porquê da resposta**.
- Use analogias do dia a dia para entender serviços.
- Mantenha a calma no exame — é introdutório!

---

## Contribua

Achou um recurso legal? Melhoraria algum trecho? Sinta-se à vontade para abrir um PR ou criar uma issue!

---

## Contato

Caso tenha dúvidas ou queira trocar ideias, me chama no [Instagram](https://www.instagram.com/frontend_clean/).

---

**Bons estudos e boa sorte na prova!**