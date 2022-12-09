# Curso da Dio sobre IDEs

## Comandos básicos IDE Eclipse
Ctrl + M = Maximiza a tela de código.

Ctrl + SPACE = Completa código ou da opções para completar.
Exemplos: syso, fore, main, etc

Ctrl + 1 = Verificar opções para o alerta no código.

Ctrl + S = Salvar.

Ctrl + F11 = Executar o Run As.

Shift + Alt + S (depois R) = Generate Getters and Setter (ggas).

Ctrl + Shift + O = Para os imports automáticos, ou opções de imports.

Ctrl + (Page Up ou Page Down) = Para alterar entre as abas de códigos.

Ctrl + N = Criar uma Classe nova, ou outro artefato.

Alt + Shift + A = Para seleção em blocos, ex: colocar a palavra private em vários atributos. Segurar Shift + seta pra baixo até onde vai a seleção, escrever a palavra, e selecionar Alt + Shift + A novamente para sair da seleção.

Alt + Shift + L = Extract Local Variable (Cria uma variavel local).

Alt + (cima ou baixo) = para movimentar a linha selecionada para cima ou para baixo.

Ctrl + Alt + (cima ou baixo) =  para copiar a linha selecionada logo abaixo.

Ctrl + D = Para apagar uma linha.

Ctrl + 3 = Abre opção para abrir algum menu, escrevendo seu apelido ou parte do nome.
Ex: ggas (para getters and setters) ou gcuf (Generate Cosntructor using Fields), etc…

Ctrl + 3 (digitar Delegate) = Para Generate Delegate Methods.

Ctrl + 3 (digitar Preferences) = Para menu preferences.

Ctrl + 2 (+ L) = para criar uma variável local depois que informamos o tipo.
Ex: new Carro() (Ctrl + 1, selecionar opção ou Ctrl + 2 (+ L) )

Ctrl + Shift + F = Formatar e organizar o código.

Alt + Shift + R = Renomear variáveis ou classes e suas devidas referências.

Alt + Shift + M = Extrair método, selecione as linhas de código que vai refatorar, retirando de um método maior, para construir um método menor e informe os dados da janela que vai se abrir com o nome do novo método.

Ctrl + Shift + R = Open Resource, procurar qualquer arquivo pelo nome.

Ctrl + Shift + T = Open Type, para procurar classes.

F3 = Abrir uma classe, selecionando a tipagem no código, ou para a declaração de uma algum elemento dentro da mesma classe.

Ctrl + O = Pesquisar dentro de uma classe aberta no editor do eclipse, todos os membros da classe.

Ctrl + T = Ver todas as subclasses de uma classe, ou ver todas as classes que sobrescrevem um método, selecionar a classe ou método antes e aplicar o atalho.

Alt + seta para esquerda = Voltar.

Ctrl + Shift + G = Ver onde um determinado método, classes ou atributos estão sendo usados por outras classes.

Ctrl + Shift + H = Parecido com o anterior, mas apenas para métodos e mostrando sua hierarquia de chamada.

Ctrl + F = Busca textual, para buscar qualquer texto dentro de arquivo atual.

Ctrl + H = Busca textual, para buscar qualquer texto dentro de qualquer arquivo no workspace. (File Search)

Ctrl + Shift + W = Fecha todos os editores abertos no eclipse.

Ctrl + F8 = Para mudar a perspectiva.
Ex. Mudar de Java para JavaEE por exemplo ou vice-versa.

Ctrl + F11 ou Alt + Shift + X (depois T) = Executar os testes automatizados do JUnit.
– Barra verde, todos os testes passaram.
– Barra vermelha, quando pelo menos um teste da erro.

Ctrl + Shift + B = para inserir Breakpoints no debug.

F6 = Modo debug, executar uma linha.

F8 = Modo debug, executar até o proximo breakpoint se houver, ou até o final da execução.

Ctrl + F2 = Para a execução atual do debug.

Ctrl + Shift + I = Com uma variável selecionada, mostra os valores dessa variável.

Ctrl + Shift + D = abre a aba Display.

Ctrl + 3 (digitar SLN) =  mostrar os números das linhas de código no eclipse.

Ctrl + Shift + L = Lista de todos os atalhos do eclipse.

## Comandos Básicos IDE IntelliJ
Geral

Alt + 1: Focar aba de projetos
Alt + Shift + Insert: Alterna entre modo de seleção de linha/coluna
Ctrl + Shift + F12: Expandir a tela

Na aba de projetos

Alt + Insert: Para criar um novo arquivo

Templates de código

psvm: Criar método main
sout: System.out.println()
Ctrl + Alt + C: Cria constante (precisa estar sobre código que permite atribuição)
Ctrl + Alt + F: Cria field - propriedade da classe (precisa estar sobre código que permite atribuição)
Ctrl + Alt + V: Cria variável (precisa estar sobre código que permite atribuição)
Ctrl + Alt + T: Templates de IF, for, while, etc (precisa selecionar o código antes)
Ctrl + J: Exibe todos os templates disponíveis

Na aba de código

Ctrl + Y: Apaga a linha inteira
Ctrl + D: Duplicar linha atual
Alt + Shift + Setas: Mover linha atual
Ctrl + Shift + Setas: Mover linha atual mantendo contexto
Ctrl + Shift + A: Find Action - mostra todas as ações da IDE em uma lista
Ctrl + N: Busca rápida de classes
Ctrl + Shift + N: Busca rápida de arquivos
Ctrl + B: Inspecionar elemento - go to class, method, declaration, etc
Ctrl + Alt + L: Reformatar código
Ctrl + Alt + M: Extrair método - transforma código selecionado em método
Shift + F6: Renomeia classe, variável, método, etc
Ctrl + Shift + F6: Usar referência de outra classe
Shift & Shift: Search everywhere
Ctrl + Shift + F: Busca por conteúdo de arquivo
Alt + Enter: Intention actions
Alt + Insert: Generate shortcut
Ctrl + F12: Mostra a estrutura do arquivo - por exemplo, exibe métodos de uma classe
Alt + F7: Find usages - mostra a lista de quem está chamando o método, usando a variável, etc
Ctrl + G: Ir para linha
Ctrl + H: Mostrar hierarquia da classe (classes pais)
Alt + Home: Ir para a barra de navegação
Ctrl + P: Mostrar parâmetros do método
Ctrl + Q: Documentação rápida
Ctrl + / ou Ctrl + Shift + /: Comentar código
Ctrl + Shift + Alt + T: Métodos de refatoração
Ctrl + Alt + O: Reajustar imports da classe (remove imports não utilizados)


## Comandos Básicos IDE Visual Studio
Executar código: comando Ctrl + Alt + N;
Parar a execução: comando Ctrl + Alt + M;
Salvar código: Ctrl + S, ou você pode ativar o Auto Save, que salva automaticamente a cada modificação, acessando em File -> AutoSave);
Abrir a aba de configurações do VSCode: comando Ctrl + Shift + P;
Abrir uma nova aba de arquivo: comando Ctrl + N;
Abrir uma nova janela do VSCode: pode ser útil para múltiplos projetos, o comando é o Ctrl + Shift + N.
