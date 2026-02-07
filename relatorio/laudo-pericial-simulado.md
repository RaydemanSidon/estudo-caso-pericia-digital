# LAUDO PERICIAL TÉCNICO – ANÁLISE FORENSE DIGITAL

---

## 1. IDENTIFICAÇÃO

Perito Responsável: Raydeman Santiago Sidon da Rocha  
Data da Análise: 07/02/2026 
Tipo de Exame: Análise Forense Digital em Arquivo  
Natureza: Estudo de Caso Simulado  

---

## 2. OBJETO DA PERÍCIA

Realizar análise técnica em arquivo identificado como potencialmente suspeito, aplicando procedimentos de preservação, integridade e análise estática básica.

Arquivo analisado: arquivo_teste.txt  
Local original: /home

---

## 3. METODOLOGIA

Foram adotados os seguintes procedimentos:

1. Identificação da evidência
2. Geração de hash MD5 e SHA256
3. Cópia preservada da evidência
4. Análise de metadados com `stat`
5. Reconstrução de timeline com `ls -lt`
6. Extração de conteúdo com `strings`
7. Aplicação de checklist de cadeia de custódia

As análises foram realizadas exclusivamente em cópia da evidência.

---

## 4. RESULTADOS

### 4.1 Hash da Evidência

MD5: 1afac99a140596e4d99b14921dfddeef  
SHA256: 71a399befd1536b83e4a43ca20a600b10626f6c9e95c77c3404e072179086572

A integridade do arquivo foi preservada durante todo o processo.

---

### 4.2 Metadados

Foram identificadas as seguintes informações relevantes:

- Data de modificação (mtime)
- Data de acesso (atime)
- Data de alteração de metadados (ctime)
- Identificador inode

Não foram observadas inconsistências temporais aparentes.

---

### 4.3 Timeline

A listagem ordenada por data indicou a sequência cronológica de modificação dos arquivos no diretório analisado.

O arquivo investigado encontra-se entre os mais recentes, compatível com o horário simulado do incidente.

---

### 4.4 Análise de Conteúdo

A extração de strings revelou:

- Texto legível presente no arquivo
- Possível indicação de endereço IP
- Presença de informação sensível em texto claro (simulado)

A técnica permitiu triagem preliminar sem execução do arquivo.

---

## 5. CADEIA DE CUSTÓDIA

Foi aplicada documentação formal de cadeia de custódia, contendo:

- Identificação da evidência
- Registro de coleta
- Geração de hash
- Controle de acesso
- Registro das etapas de análise

Não houve quebra de integridade.

---

## 6. CONCLUSÃO TÉCNICA

Com base nos procedimentos executados:

- A evidência foi preservada adequadamente.
- Os hashes confirmam integridade.
- A análise de metadados e timeline não apresentou inconsistências.
- A extração de strings indicou presença de conteúdo textual que poderia demandar investigação complementar em cenário real.

Este estudo demonstra aplicação prática de princípios básicos de perícia digital alinhados às boas práticas internacionais.

---

## 7. REFERÊNCIAS TÉCNICAS

- NIST SP 800-86 – Guide to Integrating Forensic Techniques into Incident Response
- NIST SP 800-61 Rev. 2 – Computer Security Incident Handling Guide
- Documentação oficial GNU Coreutils (stat, ls, strings)
