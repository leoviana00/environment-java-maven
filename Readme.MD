## Ambiente Java e Maven

- Script para preparar um ambiente com Java e Maven

## Tools
- Shell
- Java 17.0.5
- Maven 3.8.6

## Etapas do Script

1. Instalação do JDK
- Download dos binários do JDK
- Configuração do JAVA_HOME e path das variáveis de ambiente
- Verificação a Instalação do Java

2. Instalação do Apache Maven
- Download dos binários do Maven
- Configuração do M2_HOME e path das variáveis de ambiente
- Verificação a Instalação do Apache Maven

## Definindo JAVA_HOME e path das variáveis de ambiente

- Add ao .profile do usuário

```bash
sudo nano ~/.profile
```

- Add as seguintes linhas

```bash
JAVA_HOME=/opt/jdk17        
PATH=$PATH:$JAVA_HOME/bin  
export PATH      
```         

- Reinicie o terminal ou execute source .profile para aplicar as alterações
```bash
sudo source ~/.profile                           
```

## Definindo M2_HOME e path das variáveis de ambiente

- Add ao .profile do usuário

```bash
sudo nano ~/.profile
```

- Add as seguintes linhas

```bash
M2_HOME=/opt/maven                               
PATH=${M2_HOME}/bin:${PATH}                      
export PATH"        
```  

- Reinicie o terminal ou execute source .profile para aplicar as alterações
```bash
sudo source ~/.profile                           
```