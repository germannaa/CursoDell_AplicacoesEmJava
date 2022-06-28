# CursoDell_AplicacoesEmJava

Para desenvolvermos nosso programa em Java, precisamos primeiro instalá-lo em nossa máquina. 
Para isso, acesse o site http://www.oracle.com/technetwork/java/javase/downloads/ e navegue até a opção de download do Java Development Kit (JDK). 

Atenção! 
Como a página de download do Java pode mudar com o tempo, para saber qual ícone ou link redireciona para o arquivo que você precisa, 
procure sempre pela sigla JDK (Java Development Kit). A seguir, você conhecerá o passo a passo de instalação da plataforma Java.

# Definindo as variáveis do ambiente
Para utilizarmos as ferramentas de desenvolvimento que o JDK contém, é necessário criar formas para o sistema operacional encontrar os arquivos do Java. 
Para isso, definiremos algumas variáveis de ambiente, que são variáveis do sistema operacional que contêm o endereço para programas e arquivos dos quais ele precisará. 

As variáveis de ambiente que definiremos são:

JAVA_HOME: deve conter o diretório em que foi instalado o JDK. Podemos referenciar esta variável dentro de outras variáveis de ambiente, como CLASSPATH e PATH, para diminuir o tamanho do endereço de diretórios dentro da pasta de instalação do Java.
PATH: deve conter o diretório no qual se encontram as ferramentas de desenvolvimento do Java (compilador, interpretador, gerador de documentação etc.). Os arquivos relativos a essas ferramentas estão dentro da pasta “bin’’ do diretório de instalação do Java.
CLASSPATH: deve conter o diretório no qual o ClassLoader (componente que carrega as classes que estão em disco para a memória) poderá encontrar as classes que são utilizadas pela sua aplicação, principalmente as classes de base do Java. Esses arquivos estão dentro da pasta “lib” do diretório de instalação do Java.
