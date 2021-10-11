# Projeto Casa do Código Alura

## Resources 
 * JBOSS Forge
 * Wildfly
 * Maven

### Creating a Base Structure
 Open JBOSS Forge Terminal 
 ```bash
 HOME_DO_FORGE/bin/forge
 ```
 or install the forge dependency in eclipse and use the JBOSS forge terminal
 ```bash
 project-new -named casadocodigo
 ```
 base project br.com.casadocodigo
 project type WAR
 Build System MAVEN
 
 ```bash
 faces-setup --facesVersion 2.2
 cdi-setup --cdiVersion 1.1
 ```
 Install Wildfly server and use standalone-full.xml
 
### See the app

http://localhost:8080/casadocodigo/index.xhtml
