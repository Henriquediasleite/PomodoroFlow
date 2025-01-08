O projeto "Fokus" é uma aplicação web focada em melhorar a produtividade dos usuários por meio de um timer baseado na técnica Pomodoro. Ele permite alternar entre modos de foco, descanso curto e descanso longo, além de oferecer uma opção para reprodução de música.

# Estrutura do Projeto

- ## HTML

O arquivo principal (“index.html”) é responsável pela estrutura do conteúdo da página. Ele utiliza tags semânticas para definir seções do aplicativo, como:

**Header**: Contém o logotipo.

**Main**: Abriga as principais funcionalidades do timer e descrições.

**Footer**: Apresenta um rodapé com os créditos do projeto.

- ## CSS

O estilo da aplicação está definido no arquivo "**styles.css**", que:

Utiliza **variáveis** CSS para cores e gradientes.

Possui estilos responsivos para diferentes dispositivos (tablets e celulares).

Inclui classes para botões, elementos do timer e layout geral.

- ## JavaScript

O arquivo "**script.js**" é responsável pela lógica funcional da aplicação, como:

Gerenciamento do temporizador.

Alternância entre modos de foco e descanso.

Controle do estado do botão de reprodução de música.

Funcionalidades JavaScript

Inicialização e Configurações Gerais

Declaração de variáveis DOM para manipulação de elementos como botões, título, imagem, e música.

- ### Configuração de áudios:

Música principal em loop.

Sons para play, pausa e finalização do tempo.

Música

- ### Controle da reprodução da música com o interruptor (musicaFocoInput):

Quando ativado, inicia a música.

Quando desativado, pausa a música.

Modos de Temporizador

Foco: 25 minutos (1500 segundos).

Descanso Curto: 5 minutos (300 segundos).

Descanso Longo: 15 minutos (900 segundos).

Cada botão altera o contexto visual e reseta o temporizador.

- ### Atualiza:

Texto do título com mensagens motivacionais.

Banner da interface.

- ### Timer

Exibição do tempo restante formatado (minutos e segundos).

- ### Redução do tempo a cada segundo com verificação para:

Tocar som de finalização.

Exibir mensagem de alerta.

### Controle de início e pausa:

Toca áudio correspondente.

Alterna entre estados de play e pausa com atualização de ícone e texto do botão.

- ## Funções Utilizadas

alterarContexto(contexto): Atualiza o layout e as mensagens com base no modo selecionado.

iniciarOuPausar(): Alterna entre iniciar e pausar o temporizador.

zerar(): Reseta o temporizador para o estado inicial.

mostrarTempo(): Formata e exibe o tempo restante na tela.

- ## Execução Inicial

A função mostrarTempo() é chamada no escopo global para inicializar a interface com o tempo padrão (25 minutos).

- ## Design Responsivo

O projeto foi desenvolvido com responsividade, ajustando o layout e tamanhos de fonte para:

Tablets: Resoluções entre 768px e 1024px.

Celulares: Resoluções abaixo de 768px.

- ## Tecnologias Utilizadas

> **HTML5**: Para a estrutura semântica.

> **CSS3**: Para estilização e responsividade.

> **JavaScript**: Para lógica de interatividade.

> **Google Fonts**: Fontes personalizadas (Montserrat, Unbounded e Prata).

> **Reset CSS**: Normalização dos estilos entre navegadores.
