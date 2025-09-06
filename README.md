# Desafio-Instância-EC2
🚀 **Bootcamp Santander Code Girls 2025**

Repositório com diagrama de arquitetura AWS, desenvolvido durante o Bootcamp Code Girls 2025 e anotações gerais sobre o contéudo.

**Objetivo**  
Aprofundar conhecimentos em instâncias EC2 na AWS e explorar integração com armazenamento e banco de dados.

**Serviços utilizados**  
💻 EC2 → Computação em nuvem e processamento de arquivos  
📦 EBS → Armazenamento persistente: volume D (entrada de arquivos) e C (dados processados)  
🗄️ RDS → Banco de dados relacional gerenciado  

 **Estrutura do repositório**  
🖼️ Desafio_Instancias_EC2.drawio → Diagrama exportado editável  
📄 README.md → Documentação do projeto  

🏗️ **Fluxo da arquitetura**  
1. Usuário envia o arquivo  
2. Arquivo vai para volume D (EBS) na EC2  
3. EC2 processa/valida e resultados temporários vão para volume C  
4. Dados finais vão para o RDS  
5. Tudo na AWS, garantindo segurança, escalabilidade e confiabilidade
