# Análise de Strings em Arquivo Suspeito

## Objetivo

Extrair sequências de texto legível de um arquivo para identificar possíveis indícios de atividade suspeita.

---

## Comando Utilizado

No terminal

echo "Conexão suspeita para 192.168.1.50" > suspeito.bin

echo "Senha=123456" >> suspeito.bin


strings suspeito.bin

---

## Saída Obtida

Conexão suspeita para 192.168.1.50  
Senha=123456  

---

## Interpretação Técnica

A análise revelou:

- Presença de endereço IP interno
- Texto indicando possível conexão remota
- Informação sensível armazenada em texto claro

---

## Aplicabilidade Forense

A extração de strings auxilia na identificação de:

- Endereços IP
- URLs
- Comandos embutidos
- Credenciais expostas
- Caminhos de arquivos

Essa técnica é amplamente utilizada em triagem inicial de arquivos binários suspeitos.
