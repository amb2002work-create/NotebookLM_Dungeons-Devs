# Dungeons & Devs

CONTEXTO E OBJETIVO 
Dungeons & Devs é o NotebookLM desenvolvido para o desafio da DIO com uma proposta inicial de ensinar linguagem de programação Python de maneira lúdica e divertida através de um mundo de RPG, tendo sua história e regras bases sido geradas pela própria inteligência artificial. 

CURADORIA DE FONTES
1. As fontes utilizadas como base de para que a IA compreendesse as regras de um RPG foram retiradas de bases do Dungons & Dragons: 
// https://online.anyflip.com/brfv/hydx/mobile/index.html#p=1
// https://bibliotecaelfica.org/2023/01/15/dd-5e-ficha-de-personagem-completavel/
// https://olddragon.com.br/livros/lb1
// https://newtonrocha.wordpress.com/wp-content/uploads/2012/03/sistema-de-rpg-2d6-tio-nitro-livreto.pdf

2. Para alimentar a base sobre Python, a linguagem de progrmação que eu desejava aprender, forma utilizadas as fontes:
// https://app.readthedocs.org/projects/curso-python/downloads/pdf/latest/
// https://docente.ifsc.edu.br/mello/livros/java/caelum-python-objetos-py14.pdf
// https://files.cercomp.ufg.br/weby/up/688/o/M2_IP_24-09-24.pdf
// https://gist.github.com/alexandre/8e8421246dbb9c8f465d326c3012ffb0

3. Após alimentar o NoteBookLM com as fontes acima, solicitei que fosse desenvolvido a história de mundo e as regras básicas, de forma que a resposta gerada fosse tambpem incluida nas fontes base do notebook, As informações foram as seguintes:

HISTÓRIA DO MUNDO
Aqui está uma proposta de história temática que combina os elementos de fantasia épica do Guia do Mestre de D&D 5E com a lógica de programação Python, criando um cenário para o seu RPG "Dungeons & Devs". Título da Campanha: O Código de Silício e Sombras
O Cenário: O Reino de Pythoria O mundo não é feito de átomos, mas de objetos instanciados por uma consciência primordial . Em Pythoria, a magia é conhecida como "Sintaxe". Os magos são chamados de Codificadores e utilizam pergaminhos escritos em uma linguagem rúnica chamada Python para manipular a realidade . A capital do reino é a metrópole de Grupy-Sanca, um centro de inovação e troca de conhecimento onde aventureiros se reúnem em tavernas conhecidas como PyBares para discutir novas "bibliotecas" de feitiços .

O Conflito: A Inconsistência do Saldo Real A paz em Pythoria é abalada quando o Grande Banco de Objetos começa a apresentar comportamentos erráticos . O saldo das contas dos cidadãos está sendo drenado por uma força invisível, e o sistema financeiro do reino entrou em um estado inconsistente . O Rei Guido van Rossum convoca um grupo de heróis para investigar. Se o saldo total do reino chegar a zero ou se tornar um valor negativo inválido, a própria realidade pode sofrer um SystemExit e deixar de existir .

Os Protagonistas (Os Contribuidores) Os jogadores devem preencher suas Fichas de Personagem com classes temáticas: O Guerreiro de Silício: Utiliza armaduras rúnicas baseadas em Arduino, capazes de ler os sinais do ambiente para prever ataques inimigos . O Clérigo da Manutenção: Especialista em curar "bugs" e remover condições de erro no sistema dos aliados . O Ladino do Script: Capaz de ler arquivos confidenciais e realizar "fatiamento" (slicing) preciso em seus ataques furtivos .

As Masmorras: Os Coding Dojos Para salvar o reino, os heróis devem invadir masmorras conhecidas como Coding Dojos . Cada sala apresenta um desafio de lógica que deve ser resolvido em equipe (pair programming): O Enigma do Loop Infinito: Os heróis ficam presos em um corredor que se repete (while True) até que consigam encontrar a condição de parada (break) escondida em uma alavanca secreta . A Porta do Dicionário: Para abrir o portão principal, os jogadores devem inserir a chave correta que corresponde ao valor do segredo da tumba .

O Antagonista: Nullius, o Arauto do None O vilão da história é Nullius, uma entidade feita de puro NoneType que deseja apagar o Histórico do mundo . Nullius não ataca com espadas, mas lançando exceções de NameError e AttributeError para fazer com que os heróis esqueçam quem são ou percam suas habilidades . A batalha final ocorre no Diretório Raiz do mundo . Os heróis precisarão usar o poder do Polimorfismo para adaptar suas estratégias às várias formas de Nullius e, finalmente, executar um comando de commit para salvar o estado de Pythoria para a eternidade . Dica para o Mestre: Use as mecânicas de Vantagem e Desvantagem do D&D 5E para testes de resistência contra "erros de sintaxe" lançados pelo vilão . Se um jogador tiver sucesso em um teste de Inteligência (Arcanismo), ele pode identificar qual "função" o inimigo está prestes a usar .

REGRAS BÁSICAS
Com base nos manuais de RPG fornecidos e nos conceitos de programação, aqui está o desenvolvimento do sistema de regras para o mundo de Pythoria, integrando mecânicas de jogo com o aprendizado de Python.

Sistema de Regras: O Protocolo 2D6-Py O sistema é baseado no Sistema +2D6, que utiliza dois dados de seis faces para resolver ações . Resolução de Conflitos: Em vez de rolar dados aleatoriamente, o "valor do dado" é determinado pelo desempenho do jogador em um Desafio de Código . Sucesso: Se o jogador resolver o problema de Python (corrigir uma linha, prever uma saída ou responder um conceito), ele é considerado como se tivesse rolado um 12 (Acerto Crítico) . Erro: Se o jogador errar o problema, ele é considerado como se tivesse rolado um 2 (Falha Crítica) e sofre dano ou penalidades . Classe de Dificuldade (CD): A complexidade do problema de Python corresponde à CD do teste . Fácil (CD 6): Perguntas sobre tipos básicos (int, float, str) . Normal (CD 10): Problemas envolvendo if/else ou listas . Difícil (CD 15+): Desafios de funções, classes ou tratamento de exceções .

Personagem Básico: O Codificador Aprendiz Este é o arquétipo inicial para o jogador, equilibrado para exploração e combate lógico. Atributos (Escala 1-5): INT (Inteligência): 4 (Sua capacidade de processar algoritmos complexos) . PER (Percepção): 3 (Sua habilidade em notar erros de sintaxe ocultos) . CON (Constituição): 3 (Resistência física para longas jornadas de compilação) . DES (Destreza): 2 (Velocidade de digitação e iniciativa) . CAR (Carisma): 2 (Capacidade de realizar Pair Programming com NPCs) . Pontos de Vida (PV): 16 (Calculado como 10 + 2xCON) . Perícia Inicial: Depuração 1 (Bônus de +1 em testes para identificar bugs) .

Bestiário de Pythoria (Os Bugs) Inimigos que representam falhas no sistema e devem ser "debugados". Erro de Sintaxe (ND 1): Pequenas criaturas voadoras que parecem aspas soltas ou parênteses não fechados . PV: 5. Ataque: "Aspas Inesperadas" (Dano 1d6-2). Desafio para Derrotar: Corrigir um código simples como print("Olá'. Loop Infinito (ND 3): Uma serpente que morde a própria cauda, forçando o tempo a parar . PV: 15. Habilidade Especial: Prende o jogador em um estado de while True. Desafio para Derrotar: O jogador deve identificar a instrução break correta ou a condição de parada . Vazamento de Memória (ND 5): Uma massa gelatinosa que consome os recursos do ambiente . PV: 30. Desafio para Derrotar: Requer 3 respostas corretas consecutivas sobre gerenciamento de objetos e o comando del .

Buffs, Debuffs e Itens Itens de Ajuda: Café de Guido: Um item consumível que restaura 1d6 PV e concede bônus de +2 em INT no próximo desafio . Manual de Bolso: Permite ao jogador consultar um conceito de Python uma vez por sessão (fornece uma dica para o problema) . Escudo de IDLE: Uma proteção que reduz o dano recebido de bugs em 2 pontos (DEF 2) . Buffs (Efeitos Positivos): Import Math: Aumenta o dano de ataques baseados em cálculos matemáticos . Instalação de Biblioteca: Concede ao jogador uma nova habilidade (como random para ataques imprevisíveis) . Debuffs (Efeitos Negativos): IndentationError: O personagem fica "tropeçando" e perde sua ação na próxima rodada até alinhar seus pensamentos . NameError: O personagem esquece o nome de um item em seu inventário, tornando-o inutilizável até que ele seja "redefinido" .

Progressão e Objetivo O objetivo final é derrotar o Grande Erro de Segmentação, um chefe que requer o uso de Orientação a Objetos e Polimorfismo para ser vencido . Conforme o jogador vence os bugs, ele ganha Pontos de Personagem para aumentar suas perícias de programação .

ENGENHARIA DE PROMPT
  1. Para desenvolver a história de mundo, o prompt utilizado foi:
    >>> Desenvolva uma história temática para um jogo de RPG. <<<
     Como todas as fontes adicionadas estavam selecionadas, a IA entregou uma resposta que misturava os conceitos de RPG do Dungeosn & Dragons com os conceitos teóricos da linguagem Python. 
  
  2. Para desenvolver as regras básicas de mundo, o prompt utilizado foi:
      >>> Desenvolva todo sistema de regras deste mundo. Crie os monstros/ inimigos que devem ser derrotados (de preferência, que se assemelehm a bugs), crie um único personagem básico para ser usado pelo jogador e  desenvolva alguns buffs, debuffs e itens de ajuda que podem ser utilizados durante o jogo. O Objetivo é que os inimos sejam derrotados conforme o jogador conseguir resolver um problema de Python como por exemplo resolver um problema de código ou desbugar uma linha de código, ou até mesmo , responder corretamente alguma pergunta conceitual sobre a linguagem de programação. Quanto mais dificil o inimigo, mais dificil a pergunta a ser respondida e até a mesmo a quantidade de perguntas para derrotar um inimigo pode ser diferente <<<
     Desta forma, as regras geradas foram as adicionadas como fontes (voltar ao tópico anterior).

  3. A partir deste ponto, dei início à jornada de aprendizagem com o prompt :
      >>> Vamos começar a jogar! Você será o mestre, e eu serei o codificador aprendiz! Inicie a narrativa conforme você desejar e veja quais serão minhas próximas ações. Conto com você para aprender Python! <<<
     
O retorno foi como se segue : 
    >>> Saudações, Codificador Aprendiz! Como seu Mestre, guiarei seus passos pelo reino de Pythoria. Prepare seu console mental e vamos começar.
Prólogo: O Caos em Grupy-Sanca
Você está na taverna PyBar, na metrópole de Grupy-Sanca, um lugar conhecido pela troca de conhecimento e pelo excelente café rúnico
. O ambiente é calmo até que, subitamente, as luzes das tochas de neon começam a piscar. O menu de poções na parede, que deveria exibir os preços, entra em um estado errático.
Uma pequena criatura voadora, que parece um parêntese torto e uma aspa solitária, surge de dentro de um barril de cerveja artesanal. É um Erro de Sintaxe (ND 1)! [Regras anteriores]. Ele está "corrompendo" a realidade ao seu redor, e o taberneiro grita: "Alguém chame um Codificador! O sistema está instável!"
O bug olha para você e emite um chiado estático. Ele deixa um rastro de "Sintaxe" (magia) no ar, que impede o sistema de continuar a execução.
Seu Primeiro Desafio: O Código de Entrada
Para derrotar este bug, você não precisa de uma espada, mas de lógica. O bug gerou a seguinte instrução malformada que está travando o bar:
>>> print("Bem-vindo ao PyBar'
Seus Atributos Atuais:
PV: 16/16
INT: 4 | PER: 3 | CON: 3 | DES: 2 | CAR: 2
Perícia: Depuração 1 (+1 em testes de bug) [Regras anteriores]
O que você faz?
Ação de Depuração (CD 6): Você tenta reescrever a linha de código corretamente para anular a existência do bug. (Escreva como seria o código correto).
Teste de Percepção (PER): Você tenta analisar o ambiente para ver se há mais "Bugs" escondidos nas sombras antes de agir.
Uso de Item: Você consulta seu Manual de Bolso para obter uma dica sobre como as strings (sequências de caracteres) devem ser fechadas em Python.
Como você deseja proceder?


GRIMÓRIO DA SINTAXE ESSENCIAL
No meio da partida, eu gentilmente solicitei ao nosso mestre de mesa que me entreguasse um manual com os principais comandos para eu ter comigo no meu inventário durante a jornada. Este é o manual Nível 1 do codificador aprendiz : 
>>> Com certeza, Codificador Aprendiz! Como Mestre de Pythoria, eu lhe concedo um item lendário para o seu inventário: o "Grimório da Sintaxe Essencial". Este artefato contém os encantamentos rúnicos fundamentais para manipular a realidade do reino
.
Aqui está o compêndio de comandos que você agora carrega em seu inventário:
📜 Grimório da Sintaxe Essencial (Nível 1)
1. Oráculos de Entrada e Saída (Comunicação)
print(): O feitiço de manifestação. Exibe mensagens ou valores no console mental
.
input(): O ritual de invocação de dados. Captura o que o usuário digita no teclado
.
type(): Identifica a essência (tipo) de um objeto rúnico
.
2. Alquimia de Dados (Tipos e Variáveis)
Pythoria utiliza tipos dinâmicos, onde o interpretador descobre a magia por trás de cada variável
.
int: Números inteiros (Ex: 42)
.
float: Números reais ou com casas decimais (Ex: 3.14)
.
str (Strings): Textos delimitados por aspas simples ou duplas
.
bool: Valores de verdade, True (Verdadeiro) ou False (Falso)
.
3. Aritmética Rúnica (Operadores)
+ , - , * , / : Operações básicas de soma, subtração, multiplicação e divisão
.
//: Divisão inteira (descarta o resto)
.
%: Resto da divisão (essencial para detectar números pares ou ímpares)
.
**: Exponenciação (elevar à potência)
.
4. Pergaminhos de Decisão (Controle de Fluxo)
if / elif / else: Permitem que o código tome decisões baseadas em condições lógicas
.
Indentação: Em Python, o espaço no início da linha é obrigatório para definir blocos de poder. Falhar nisso invoca o temido bug IndentationError
.
5. Círculos de Repetição (Loops)
for: Itera sobre uma sequência definida (como uma lista ou um intervalo)
.
while: Repete um bloco de comandos enquanto uma condição for verdadeira
.
range(início, fim): Gera uma sequência de números para usar em círculos de repetição
.
6. Contêineres de Itens (Estruturas de Dados)
list (Listas): Coleções ordenadas e mutáveis de elementos entre colchetes []
.
dict (Dicionários): Coleções de pares chave:valor entre chaves {}
.
len(): Revela o comprimento ou a quantidade de itens em um contêiner
.
7. Auxílio Arcano
help(): Invoca a documentação oficial para explicar qualquer comando ou função
.
import: Instala novas bibliotecas (escolas de magia) no seu sistema atual
.
Mestre: "Com este grimório guardado, você se sente mais confiante. O Erro de Sintaxe à sua frente continua chiando, aguardando sua correção para que a paz volte ao PyBar."
O que você faz agora? (Lembre-se que você pode tentar resolver o desafio de código print("Bem-vindo ao PyBar' usando o que acabou de aprender!)
