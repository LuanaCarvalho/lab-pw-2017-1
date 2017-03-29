# lab-pw-2017-1 - Luana S. Carvalho

Primeiro Exercício - Mini Biografia.

## Para rodar a Mini Biografia:

### Para fazer clone.

`git clone https://github.com/LuanaCarvalho/lab-pw-2017-1`

### Para rodar com o Tomcat.

`mvnw org.apache.tomcat.maven:tomcat7-maven-plugin:run`

No Linux, use `./mvnw` ao invés de apenas `mvnw`, como no Windows. Além disso, pelo menos uma vez, é preciso dar permissão de execução ao arquivo de script **mvnw** com o comando `chmod +x mvnw`.

## Para acessar a aplicação

`http://localhost:8080/lab-pw-2017-1` em qualquer navegador.

### Para "empacotar" a aplicação.

`mvnw package`

## Para "preparar" o projeto

### Para "embutir" o Maven no projeto.

Não precisa fazer isso! Já foi feito. :)

`mvn io.takari:maven:0.3.3:wrapper -Dmaven=3.3.9`
