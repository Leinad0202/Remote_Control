# Remote_Control
**Descrição:** Exemplo didático em Java de orientação a objetos. Simula um
controle remoto (`ControleRemoto`) que implementa uma interface
(`Controlador`) com operações como ligar/desligar e ajustar volume.
6
**Como Executar:**
1. Instale Java 8+ e Maven.
2. Navegue até a pasta do projeto em terminal.
3. Compile e rode com Maven:
 ```bash
 mvn clean compile exec:java -
Dexec.mainClass="com.mycompany.aula_06.AULA_06"
 ```
 ou gere o JAR e execute:
 ```bash
 mvn package
 java -cp target/Remote_Control.jar com.mycompany.aula_06.AULA_06
 ```
4. Observe as saídas no console (liga o controle e exibe menu de status de
volume).
**Funcionalidades:**
- **Controlador:** interface com métodos para ligar, desligar, abrir/fechar
menu, aumentar/diminuir volume, ativar/desativar mudo, play e pause.
- **ControleRemoto:** implementação que armazena o estado atual (ligado/
desligado, volume, tocando) e executa as ações definidas na interface.
- **Main (AULA_06):** exemplo de uso: liga o controle e exibe o menu.
**Tecnologias:** Java (JDK), Maven (build).
**Aprendizados:** conceitos de interfaces, implementação de métodos
abstratos, encapsulamento de atributos, uso de construtor padrão e controle
de fluxo em Java. 
