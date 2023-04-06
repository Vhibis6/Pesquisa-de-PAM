# Pesquisa de PAM 
Nome: Paulo Ricardo Matiasso Cruz; 
Nome: Vitória Campelo de Araújo Leal. – 
2° M-TEC PI Desenvolvimento de Sistemas (DS) - Grupo B

#### 1 INTRODUÇÃO – TIPOS DE DADOS DO JAVA

Dados são um conjunto de informações, sendo capaz ser organizadas ou não. Além disso, em uma linguagem de programação, as variáveis em Java, devem possuir uma “etiqueta” para dizer que tipo de dado poderá ser armazenado na memória dessa variável, então possui-se os tipos de dados.

#### 2 TIPOS NUMÉRICOS (INTEGRAIS)

##### 2.1 TIPO DE DADO BYTE
 
O tipo de dado byte é um exemplo de um tipo de dado primitivo. Sendo que é um inteiro de complemento de dois com assinatura de 8 bits. Sua faixa de valor está entre -128 até 127 (inclusive). Valor mínimo é -128 e o valor máximo é 127. Seu valor padrão é 0 (zero).
Ele é usado para gravar em memória grandes matrizes em que a memória salva é muito requisitada. Isso economiza espaço pelo motivo de um byte é quatro vezes menor que um número inteiro, além de que também pode ser utilizado no lugar de tipos de dados "int".

##### 2.2 TIPO DE DADO CHAR

O tipo de dado char é um único caractere unicode de 16 bits. Sua faixa de valor está entre '\u0000' (ou 0) até '\uffff' (ou 65.535 inclusive). Uma vez que o char é utilizado para armazenar caracteres.

##### 2.3 TIPO DE DADO SHORT

O tipo de dado short é um inteiro de complemento de dois com assinatura de 16 bits. Desse modo, sua faixa de valor está entre -32.768 até 32.767 (inclusive), seu valor mínimo é -32.768 e valor máximo é 32.767 e seu valor padrão é 0 (zero).
Vale salientar que também pode ser usado para economizar memória assim como o tipo de dado byte. Pode-se observar que ele é duas vezes menor que um inteiro.

##### 2.4 TIPO DE DADOS INT 

O tipo de dado int é um inteiro de complemento de dois, com armazenamento de 32 bits. Sua faixa de valor está entre -2.147.483.648 (-2³¹) até 2.147.483.647 (2³¹) . Seu valor mínimo é de -2.147.483.648 e valor máximo é 2.147.483.647. Seu valor padrão é 0 (zero).
Esse tipo de dado é geralmente usado como um tipo de dado padrão para valores inteiros sem nenhum problema de memória ou com casas decimais.

##### 2.5 TIPO DE DADOS LONG

O tipo de dado long é usado quando você precisa de uma faixa de valores maior do que a fornecida por int. É um inteiro com armazenamento de 64 bits. Sua faixa de valor está entre -9.223.372.036.854.775.808 (-2³¹) até 9.223.372.036.854.775.807 (2³¹). Seu valor mínimo é -9.223.372.036.854.775.808 e o valor máximo é de 9.223.372.036.854.775.807. O seu valor padrão é 0 (zero). 

#### 3 TIPOS NUMÉRICOS (PONTO FLUTUANTE)

##### 3.1 TIPO DE DADOS FLOAT

O tipo de dado float é um ponto flutuante, 754 de 32 bits de precisão única. Sua faixa de valor é ilimitada. É recomendado usar um ponto flutuante (em vez de double) se você precisar economizar memória em grandes arrays (matrizes) de número de ponto flutuante. O tipo de dado float nunca deve ser usado para valores precisos, como moeda.

##### 3.2 TIPO DE DADOS DOUBLE

O tipo de dado double é geralmente usado para valores decimais (ponto flutuante), assim como float. São 754 de 64 bits de precisão dupla. Seu valor é ilimitado. O tipo de dado double também não deve ser usado para precisar valores.

##### 3.3 TIPO DE DADO BOOLEAN (TRUE, FALSE)

O tipo de dado boolean é usado para armazenar somente dois possíveis valores: verdadeiro e falso (true e false). Este tipo de dado é usado por sinalizadores simples que localizam condições verdadeiras/falsa. Especifica um bit de informação, mas o “tamanho” não pode ser especificado precisamente.

#### 4 INTRODUÇÃO – INSTRUÇÕES CONDICIONAIS

As instruções condicionais avaliam as "status flags" para realizar uma operação somente se a condição for atendida. Vale apontar que há condições que testam o valor de mais de uma flag em combinação para casos diferentes. A nomenclatura de escrita de uma instrução condicional é o seu nome seguido de um 'cc', sigla para "conditional code."

##### 4.1 CONDICIONAIS SIMPLES (SE - IF) 

A estrutura condicional simples executa um comando e/ou vários comandos se a condição for verdadeira. No entanto, se a condição for falsa, a estrutura é completada sem executar os comandos. Ela é composta apenas pela palavra reservada if, traduzindo do inglês, o se.

##### 4.2 CONDICIONAIS COMPOSTAS (SENÃO – ELSE)

A diferença em relação a estrutura condicional simples é que se a condição for falsa, o algoritmo também irá tomar uma ação.
Diferente do exemplo sobre estrutura condicional simples onde o algoritmo não tomava nenhuma ação, aqui ele toma uma decisão diferente, exibindo alguma mensagem.

##### 4.3 CONDICIONAL SWITCH/CASE

A estrutura condicional switch/case vem como alternativa em momentos em que temos que utilizar múltiplos ifs no código. Múltiplos if/else encadeados tendem a tornar o código muito extenso, pouco legível e com baixo índice de manutenção.
O switch/case testa o valor contido em uma variável, realizando uma comparação com cada uma das opções. Cada uma dessas possíveis opções é delimitada pela instrução case.
Podemos ter quantos casos de análise forem necessários e, quando um dos valores corresponder ao da variável, o código do case correspondente será executado. Caso a variável não corresponda a nenhum dos casos testados, o último bloco será executado, chamado de default (padrão).
A análise de cada caso também precisa ter seu final delimitado. Essa delimitação é feita através da palavra break.

#### 5 INTRODUÇÃO – ESTRUTURAS DE REPETIÇÃO DO JAVA

As estruturas de repetição em Java também são conhecidas como iteração, ou laços (loops), são usadas para executar, repetidamente, uma instrução ou um bloco de instruções enquanto definida condição estiver sendo satisfeita.  Destaca-se que as principais estruturas de repetição na maioria das linguagens são o for e o while.

##### 5.1 WHILE (ENQUANTO)

A estrutura de repetição while, na tradução para o português “enquanto”, indica que, enquanto uma condição for válida, o bloco de código será executado, ou seja, testa a condição antes de executar o código, logo, caso a condição seja inválida no primeiro teste, o bloco nem será executado.

##### 5.2 PARA (FOR)

A condição PARA tem o mesmo princípio que utilizar enquanto (while), porém este recurso é mais utilizado quando se sabe o número de iterações da repetição, como listar os valores de um vetor por exemplo, também vale ressaltar a o código que é mais limpo.
Ao usar o PARA (for) o contador (a variável i) é inicializado e incrementado na própria condição do laço junto a expressão booleana a ser atendida, deixando o código mais limpo e sem a necessidade de criar variáveis adicionais.

#### 6 INTRODUÇÃO – ANDROID STUDIO (FERRAMENTAS)

O Android Studio é o ambiente de desenvolvimento integrado (IDE) oficial para o desenvolvimento de apps Android. As barras de ferramentas são as que realizam várias ações, incluindo executar apps e abrir ferramentas do Android.

##### 6.1 TEXT 

###### 6.1.1 TEXTVIEW

A utilidade do TextView é exibir o texto na tela de um aplicativo Android.  Sendo assim, a classe TextView contém uma lógica complexa que possibilita exibir um texto formatado, hyperlinks, números de telefone, e-mails, entre outras funcionalidades úteis.

###### 6.1.2 PLAINTEXT

O PlainText é o componente responsável por receber entrada de texto do usuário. Por meio desse componente que o usuário vai inserir o login e a senha para se autenticar/validar na aplicação.

###### 6.1.3 E-MAIL

E-mail são mensagens distribuídas por meios eletrônicos de um usuário do sistema para um e/ou mais destinatários através de uma rede.

###### 6.1.4 POSTALADDRESS

Representa um endereço postal como, por exemplo, para endereços para pagamento ou distribuição postal. Dessa forma, o serviço de correios pode entregar itens em um local, uma caixa postal ou outro local semelhante.

###### 6.1.5 MULTILINE TEXT

Um campo de entrada de texto de várias linhas armazena uma string como valor e outra como texto, sendo que é sempre uma string válida. No entanto, o texto dela consegue qualquer string inserida no editor. Ao contrário de um campo de entrada de texto, esse campo também é adaptável com caracteres de nova linha inseridos no editor.

###### 6.1.6 TIME

Uma instância da classe Time representa um momento no tempo, especificado com precisão de segundos. 

###### 6.1.7 NUMBER

Um campo de número armazena um número como value e uma string como text. O value é um número válido, definido pelas restrições dadas ao campo na criação. Vale ressaltar que o texto dele pode ser qualquer string adicionada no editor.

###### 6.1.8 NUMBER (SIGNED)

Um sistema de números representado por um sinal + ou – prefixado a um dígito ou outro numeral, de modo que a soma de dois números com sinais diferentes e elementos numéricos semelhantes seja 0.

###### 6.1.9 NUMBER (DECIMAL)

Possui uma variedade de recursos projetados para possibilitar a análise e formatação de números em qualquer localidade, incluindo suporte para dígitos ocidentais, árabes ou índicos. Ele suporta diferentes tipos de números, incluindo números de ponto fixo, notação científica, porcentagens e valores monetários. Todos esses sabores podem ser facilmente localizados.

###### 6.1.10 AUTOCOMPLETETEXTVIEW

É uma exibição de texto editável que mostra sugestões de conclusão automaticamente enquanto o usuário está digitando. A lista de sugestões é exibida em um menu suspenso no qual o usuário pode escolher um item para substituir o conteúdo da caixa de edição.

###### 6.1.11 MULTIAUTOCOMPLETETEXTVIEW

Uma exibição de texto editável, estendendo AutoCompleteTextView, que pode mostrar sugestões de conclusão para a substring do texto em que o usuário está digitando, em vez de necessariamente para a coisa toda.

###### 6.1.12 TEXTINPUTLAYOUT

Layout que envolve um TextInputEditText, EditText ou descendente para mostrar um rótulo flutuante quando a dica está oculta enquanto o usuário insere texto.

##### 6.2 BUTTONS

###### 6.2.1 BUTTON

Um elemento da interface do usuário no qual o usuário pode tocar ou clicar para realizar uma ação.

###### 6.2.2 IMAGEBUTTON

ImageButton combina a Button exibição e Image a exibição para gerar um botão, onde o conteúdo é uma imagem. Dessa forma, quando é pressionado o ImageButton com um dedo ou clica nele com um mouse, ele direciona o aplicativo para executar uma tarefa.

###### 6.2.3 CHIP 

O componente chip é uma pequena caixa que pode conter até: imagem de perfil; texto; e ícone. Na documentação do Material Design este componente é retratado como "pequena caixa complexa", além de que pode ser usado em vários contextos, por exemplo, tags; contatos; marcações em texto; entre outros.

###### 6.2.4 CHIPGROUD  

Utiliza-se o componente ChipGroup para garantir que os chips sejam agrupados corretamente. 

###### 6.2.5 CHECKBOX 

CheckBox pertence à classe android.widget.CheckBox, visto que é utilizado em um local onde o usuário pode selecionar uma ou mais opções de uma determinada lista de opções, selecionando hobbies, por exemplo.

###### 6.2.6 RADIOGROUP

A classe RadioGroup tem como objetivo colocar um conjunto de botões de opção dentro dela, já que essa classe adiciona o recurso de escopo de exclusão múltipla aos botões de opção. 

###### 6.2.7 RADIOBUTTON

É um botão de dois estados que consegue ser marcado ou desmarcado. Quando o botão de rádio está desmarcado, o usuário pode pressioná-lo ou clicar nele para marcá-lo. Vale salientar que ele não pode ser desmarcado pelo usuário após marcado.

###### 6.2.8 TOGGLEBUTTON

Um ToggleButton relaciona-se ao botão de alternância, ou seja, dependendo do seu estado (pressionado ou não) um comando é executado.

###### 6.2.9 SWITCH

É um widget de alternância de dois estados que pode selecionar entre duas opções. Ele é usado para exibir o estado marcado e desmarcado de um botão, fornecendo controle deslizante ao usuário. Switch é uma subclasse de CompoundButton. É basicamente um botão liga/desliga que indica o estado atual do Switch. É muito usado para selecionar ligar/desligar em Som, Bluetooth, WiFi, etc.

###### 6.2.10 FLOATINGACTIONBUTTON

Um botão de ação flutuante (FAB) é um botão circular que aciona a ação principal na interface do usuário do seu aplicativo. Esta página mostra como adicionar o FAB ao seu layout, personalizar parte de sua aparência e responder a toques de botão.

##### 6.3 WIDGETS

###### 6.3.1 VIEW

View é um retângulo na tela que apresenta algum conteúdo, onde pode ser uma imagem, um pedaço de texto, um botão ou qualquer outra coisa que o aplicativo pode exibir. Desse modo, todas as Views juntas constituem o layout da interface.

###### 6.3.2 IMAGEVIEW

É projetado exclusivamente para exibir imagens na tela. Isso pode ser utilizado para a exibição de recursos armazenados no aplicativo ou para a exibição de imagens, na qual são baixadas da internet.

###### 6.3.3 WEBVIEW

O WebView do sistema Android é um componente com tecnologia do Google Chrome que possibilita abrir links no aplicativo que está sendo usado sem sair dele. 

###### 6.3.4 VIDEOVIEW

Exibe um arquivo de vídeo. A classe VideoView pode carregar imagens de várias fontes (como recursos ou provedores de conteúdo), calcula sua medição a partir do vídeo para que possa ser usada em qualquer gerenciador de layout e fornece várias opções de exibição, como dimensionamento e tonalidade. O VideoView não retém seu estado completo ao entrar em segundo plano.

###### 6.3.5 CALENDARVIEW

Esta classe é um widget de calendário para exibir e selecionar datas. O intervalo de datas suportado por este calendário é configurável.
A aparência exata e o modelo de interação deste widget podem variar entre as versões e temas do sistema operacional (por exemplo, Holo versus Material), mas, em geral, um usuário pode selecionar uma data tocando nela e pode rolar ou lançar o calendário para uma data desejada.

###### 6.3.6 PROGRESSBAR

Android ProgressBar é um indicador de visualização gráfica que mostra algum progresso. A barra de progresso do Android exibe uma barra que representa a conclusão da tarefa. A barra de progresso no Android é útil, pois dá ao usuário uma ideia do tempo para terminar sua tarefa. O uso da ProgressBar é uma boa prática de experiência do usuário, pois exibe o status do progresso de determinada tarefa (como baixar uma imagem) para o usuário.

###### 6.3.7 PROGRESSBAR (HORIZONTAL)

ProgressBar horizontal tem uma barra horizontal para mostrar o progresso de uma operação. Você pode ter modo determinado/indeterminado para ProgressBar horizontal.

###### 6.3.8 SEEKBAR

Um SeekBar é uma extensão do ProgressBar que adiciona um polegar arrastável. O usuário pode tocar no polegar e arrastar para a esquerda ou para a direita para definir o nível de progresso atual ou usar as teclas de seta. 

###### 6.3.9 SEEKBAR (DISCRETE)

Discrete SeekBar funciona para valores discretos, e funciona igualmente aí SeekBar.

###### 6.3.10 RATINGBAR

Uma RatingBar é uma extensão de SeekBar e ProgressBar que mostra uma classificação em estrelas. O usuário pode tocar/arrastar ou usar as teclas de seta para definir a classificação ao usar o tamanho padrão RatingBar. Ao usar um RatingBar que oferece suporte à interação do usuário, não é recomendável colocar widgets à esquerda ou à direita do RatingBar.

###### 6.3.11 SEARCHVIEW

Um widget que fornece uma interface de usuário para o usuário inserir uma consulta de pesquisa e enviar uma solicitação a um provedor de pesquisa. Mostra uma lista de sugestões ou resultados de consultas, se disponível, e permite que o usuário escolha uma sugestão ou resultado para iniciar.

###### 6.3.12 TEXTUREVIEW

Um TextureView pode ser usado para exibir um fluxo de conteúdo, como proveniente de uma visualização de câmera ou um vídeo. O fluxo de conteúdo pode vir do processo do aplicativo, bem como de um processo remoto.
TextureView só pode ser usado em uma janela acelerada por hardware. 

###### 6.3.13 SURFACEVIEW

Fornece uma superfície de desenho dedicada incorporada dentro de uma hierarquia de exibição. Você pode controlar o formato desta superfície e, se quiser, seu tamanho. O SurfaceView cuida de colocar a superfície no local correto na tela.

###### 6.3.14 HORIZONTAL/VERTICAL DIVIDER

Como o nome sugere, um divisor é algo que divide o espaço em dois. Então, basicamente, um divisor pode existir apenas entre duas entidades. No Android, podemos usar um divisor para separar dois elementos. Ele aparece visualmente como um segmento de linha reta. Os elementos podem ser basicamente empilhados verticalmente ou apenas horizontalmente. Portanto, um divisor pode ter orientação vertical ou horizontal.

#### REFERÊNCIAS BIBLIOGRÁFICAS:

http://fabrica.ms.senac.br/2015/03/tipos-de-dados-em-java/
https://acervolima.com/tipos-de-dados-em-java-1/
https://www.javatpoint.com/pt/tipo-de-dado-em-java
https://mentebinaria.gitbook.io/assembly/aprofundando-em-assembly/instrucoes-condicionaishttp://fabrica.ms.senac.br/2013/06/algoritmo-estruturas-condicionais/
https://www.jdevtreinamento.com.br/estruturas-de-repeticao-em-java/
https://glysns.gitbook.io/java-basico/controle-de-fluxo/estruturas-de-repeticao
https://www.androidpro.com.br/blog/desenvolvimento-android/android-views-intro/
https://materialpublic.imd.ufrn.br/curso/disciplina/3/66/5/6
https://developers.google.com/assistant/df-asdk/reference/webhook/rest/Shared.Types/PostalAddress?hl=pt-br
https://developers.google.com/blockly/guides/create-custom-blocks/fields/built-in-fields/multiline-text-input?hl=pt-brhttps://developer.android.com/reference/android/widget/Button
https://developers.google.com/blockly/guides/create-custom-blocks/fields/built-in-fields/number?hl=pt-br
https://tutorialspoint.com/android/android_sending_email.htm
https://learn.microsoft.com/pt-br/dotnet/maui/user-interface/controls/imagebutton?view=net-maui-7.0
https://jamiltondamasceno.com.br/2018/12/13/conhecendo-android-design-support-v28/
https://www.thiengo.com.br/chips-android-quando-e-como-utilizar
https://acervolima.com/como-usar-o-checkbox-no-android/
https://developer.android.com/reference/android/widget/RadioButton
https://acervolima.com/radiogroup-em-kotlin/
https://juliobattisti.com.br/artigos/livroexc2007ribbon/capitulo1/11.asp#:~:text=Um%20toggleButton%20refere%2Dse%20ao,vis%C3%ADvel%20ou%20n%C3%A3o%2C%20por%20exemplo.
https://www.androidpro.com.br/blog/desenvolvimento-android/android-views-intro/
https://www.techtudo.com.br/listas/2020/06/o-que-e-webview-do-sistema-android-saiba-para-o-que-serve-o-app.ghtml
https://developer.android.com/reference/android/text/format/Time
https://www.javatpoint.com/pt/tipo-de-dado-em-java
https://www.treinaweb.com.br/blog/estruturas-condicionais-e-de-repeticao
https://www.treinaweb.com.br/blog/estruturas-condicionais-e-estruturas-de-repeticao-em-java
https://developer.android.com/studio/intro?hl=pt-br
https://www-geeksforgeeks-org.cdn.ampproject.org/v/s/www.geeksforgeeks.org/create-vertical-and-horizontal-divider
https://tutorialwing.com/android-surfaceview-tutorial-with-example/
https://www-geeksforgeeks-org.cdn.ampproject.org/v/s/www.geeksforgeeks.org/discrete-seekbar-in-android/amp/
https://developer.android.com/reference/android/R.style#Widget_ProgressBar_Horizontal
https://developer.android.com/reference/android/widget/AutoCompleteTextView
https://developer.android.com/reference/android/widget/CheckedTextView
https://developer.android.com/reference/com/google/android/material/textfield/TextInputLayout
