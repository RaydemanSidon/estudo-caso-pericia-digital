# Análise de Timeline com LS -LT

## Objetivo

Reconstruir a sequência temporal de arquivos no diretório investigado.

---

## Comando Utilizado

ls -lt

---

## Saída Obtida

-rw-r--r-- 1 usuario usuario  20 Feb  7 14:09 arquivo_teste.txt
-rw-r--r-- 1 usuario usuario 200 Feb  7 13:55 outro_arquivo.log
-rw-r--r-- 1 usuario usuario 500 Feb  6 18:10 relatorio_antigo.txt

---

## Interpretação Técnica

- O arquivo `arquivo_teste.txt` é o mais recentemente modificado.
- A ordenação permite identificar possível sequência de eventos.
- Arquivos criados ou modificados próximos ao incidente merecem prioridade na análise.

---

## Relevância Forense

A análise de timeline permite:

- Identificar atividades suspeitas próximas ao horário do incidente
- Correlacionar com logs do sistema
- Reconstruir eventos
- Priorizar evidências para análise aprofundada
