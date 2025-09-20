# Estudo Maven

Este projeto é um estudo de como usar **Maven** em projetos Java: organização básica, estrutura, dependências, build, entre outras funcionalidades que o Maven oferece.

---

## 🧰 Tecnologias e Ferramentas

- Java  
- Maven  
- IDE Java (IntelliJ IDEA, Eclipse, etc.)  
- Estrutura padrão Maven (`src/main/java`, `src/test/java`, etc.)

---

## 📂 Estrutura do Projeto

```
Estudo-Maven/
├── src/
│   ├── main/
│   │   └── java/
│   └── test/
│       └── java/
├── target/              # Build gerado pelo Maven
├── pom.xml              # Arquivo de configuração do Maven
├── .gitignore
└── README.md
```

---

## 🚀 O que esse estudo abrange

- Como configurar o `pom.xml`  
- Gerenciar dependências com Maven  
- Compilar o projeto (`mvn compile`)  
- Testar com Maven (`mvn test`)  
- Executar build completo (`mvn package`)  
- Entender os diretórios padrão do Maven  
- Possivelmente outras configurações básicas (plugins, profiles, etc.)

---

## ⚙️ Requisitos

- JDK instalado  
- Maven instalado  
- IDE compatível com projetos Maven  
- Conhecimento básico de Java

---

## 🛠️ Como usar

1. Clone o repositório  
   ```bash
   git clone https://github.com/JoaoPedroBackEndDev/Estudo-Maven.git
   ```

2. Abra no IDE de sua preferência  

3. Explore o arquivo `pom.xml` para ver dependências, plugins, versão do Java, etc.

4. Execute comandos do Maven no terminal:
   ```bash
   mvn clean
   mvn compile
   mvn test
   mvn package
   ```

---

## 🔍 Possíveis melhorias

- Adicionar testes unitários para demonstrar uso de `src/test/java`  
- Incluir profiles do Maven para diferentes ambientes (desenvolvimento, produção)  
- Configurar plugins úteis, como plugin de verificação de qualidade de código, cobertura de testes (por exemplo, JaCoCo)  
- Gerar documentação com plugin Maven (ex: site)  
- Automatizar build com CI (GitHub Actions, GitLab CI)

---

## 📌 Autor

- **João Pedro** — desenvolvedor Java Backend  
- [GitHub](https://github.com/JoaoPedroBackEndDev)

---

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.
