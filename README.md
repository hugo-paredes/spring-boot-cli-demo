# Demo

## Spring Boot CLI

### Useful

#### Get help to initialize Spring Boot

```bash
spring init help --list
```

#### Initialize project

```bash
spring init --dependencies=web --boot-version=3.2.4 --build=maven --artifact-id=demo --group-id=nl.allianz --packaging=jar spring-boot-init-demo
```

#### Add .gitignore

```bash
(
    echo "# https://raw.githubusercontent.com/spring-projects/spring-boot/main/.gitignore" && \
    curl -s https://raw.githubusercontent.com/spring-projects/spring-boot/main/.gitignore && \
    echo "# https://raw.githubusercontent.com/github/gitignore/main/Maven.gitignore" && \
    curl -s https://raw.githubusercontent.com/github/gitignore/main/Maven.gitignore && \
    echo "# https://raw.githubusercontent.com/github/gitignore/main/Java.gitignore" && \
    curl -s https://raw.githubusercontent.com/github/gitignore/main/Java.gitignore
) > .gitignore
```
