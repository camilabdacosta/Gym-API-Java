Estrutura

gym-api/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── camilabdacosta/
│   │   │           └── gymapi/
│   │   │               ├── controller/
│   │   │               │   └── MeuController.java
│   │   │               ├── model/
│   │   │               │   └── Entidade.java
│   │   │               ├── repository/
│   │   │               │   └── MeuRepositorio.java
│   │   │               ├── service/
│   │   │               │   ├── MeuServico.java
│   │   │               │   └── MeuServicoImpl.java
│   │   │               └── MeuAplicativo.java
│   │   ├── resources/
│   │   │   ├── application.properties
│   │   │   ├── static/
│   │   │   └── templates/
│   ├── test/
│   │   └── java/
│   │       └── com/
│   │           └── camilabdacosta/
│   │               └── gymapi/
│   │                   ├── controller/
│   │                   │   └── MeuControllerTest.java
│   │                   ├── service/
│   │                   │   └── MeuServicoTest.java
│   │                   └── MeuAplicativoTest.java
│   └── resources/
│       └── application-test.properties
│
├── build.gradle
├── settings.gradle
└── gradlew