# DockerForJava (projeto para simular uso de docker em Java Spring e manipular imagem)
Working with docker in Java Spring MVC

git clone
git checkout
git add .
git push
git branch

mvn -v
java --version  17 with spring marven

Marven install
Spring Boot Inicializer
defining  java enviroments

mvn spring-boot:run
@SpringBootTest (classes=GraficoApplication.class) -- in test class to make tests
mvn spring-boot:build-image 

install docker
docker machine



docker run grafico:0.0.1-SNAPSHOT
docker.io/library/grafico:0.0.1-SNAPSHOT
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart


https://bobbyhadz.com/blog/docker-is-not-recognized-as-internal-or-external-command#:~:text=If%20you%20get%20a%20permissions,click%20%22Run%20as%20administrator%22.

https://docs.docker.com/desktop/install/windows-install/

https://www.atlassian.com/git/tutorials/syncing/git-fetch?fbclid=IwAR0d5PmjTf9ujavf-6OV911jLFJJedL3_NdIrwA2aclaAPy34DfOzkiFgg8

//Remove this piece of code from main to run in browser directely before build in docker
/* 
	private static void openHomePage() throws IOException {
		Runtime rt = Runtime.getRuntime();
		rt.exec("rundll32 url.dll,FileProtocolHandler " + "http://localhost:8080");

		
	}
	*/
