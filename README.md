# Beginner
Beginner guide to java

Download HomeBrew pelo terminal de comando, adicionando _/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Para baixar o JDK, rodar na linha de comando: _brew update
e depois: _brew tap caskroom/versions
e depois: _brew cask install java8

Para checar se o JDK esta instalado corretamente: _javac --version

Guias para iniciantes online: 
 * https://beginnersbook.com/2013/05/java-introduction/ 
 * https://beginnersbook.com/2013/05/jvm/ 
 * https://beginnersbook.com/java-tutorial-for-beginners-with-examples/
 
 
# Meu Primeiro Programa em Java
Para criar um repositorio: mkdir [NomeDoRepositorio]
Para mover para o repositorio: cd [NomeDoRepositorio]
Para criar um novo arquivo: touch [NomeDoArquivo.TipoDoArquivo]
Para editar o arquivo: nano [NomeDoArquivo.TipoDoArquivo]

Adicionar no arquivo: 
public class FirstJavaProgram {
  public static void main(String[] args){
    System.out.println("This is my first program in java");
  }//End of main
}//End of FirstJavaProgram Class

Para Renomear o Arquivo: mv [NomeDoArquivo.TipoDoArquivo] FirstJavaProgram.java
Para  __Compilar__ o arquivo: javac FirstJavaProgram.java
Para __Rodar__ o arquivo: java FirstJavaProgram

# Fim

