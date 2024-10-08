# Trabalho sobre Blockchain - Aula de Segurança da Informação - Profª Bruno Zolotareff

## Link para o PDF do artigo
https://pdf.ac/2ANOVo

## Nome dos integrantes
Lucas Santos - https://www.linkedin.com/in/lucas-santos-298671330
<br/>Nicolas Assunção - www.linkedin.com/in/nicolas-assunção-de-jesus-444670330
<br/>Pedro Lucas - www.linkedin.com/in/pedro-souza-6803432a7
<br/>Thiago Januário - www.linkedin.com/in/thiago-januário-6728302a4
<br/>Vitor Antonio - www.linkedin.com/in/vitor-antonio-25412a248

## Informações do professor que fez o artigo
Título do artigo - Blockchain in Developing 
Countries
<br/>Nome - Jeffrey Voas
<br/>Link do Linkedin - https://www.linkedin.com/in/jeffrey-voas-48a10710

## Explicação do código 
1. Estrutura Básica:
   - Importação do módulo 'crypto' para gerar hashes
   - Duas classes principais: Block e Blockchain

2. Classe Block:
   - Representa um único bloco na blockchain
   - Propriedades: índice, timestamp, dados, hash anterior, hash próprio, nonce
   - Métodos:
     - calculateHash(): gera o hash do bloco
     - mineBlock(): simula o processo de mineração (prova de trabalho)

3. Classe Blockchain:
   - Gerencia a cadeia completa de blocos
   - Inicia com um bloco gênesis
   - Métodos:
     - createGenesisBlock(): cria o primeiro bloco
     - getLatestBlock(): retorna o bloco mais recente
     - addBlock(): adiciona um novo bloco à cadeia
     - isChainValid(): verifica a integridade da blockchain

4. Demonstração de Uso:
   - Criação de uma instância da blockchain
   - Adição de novos blocos
   - Verificação da validade da cadeia

5. Simulação de Adulteração:
   - Modificação dos dados de um bloco existente
   - Demonstração de como a alteração invalida a cadeia

6. Conceitos Ilustrados:
   - Estrutura encadeada de blocos
   - Hashing criptográfico
   - Prova de trabalho simplificada
   - Integridade e imutabilidade dos dados

7. Propósito:
   - Exemplo educacional dos princípios básicos de blockchain
   - Não adequado para uso em ambiente de produção
