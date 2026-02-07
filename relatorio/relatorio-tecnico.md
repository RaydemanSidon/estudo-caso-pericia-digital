# Relatório Técnico – Análise Forense Digital

## 1. Identificação da Evidência

Arquivo: arquivo_teste.txt  
Localização original: /home  

---

## 2. Hashes Calculados

MD5:
1afac99a140596e4d99b14921dfddeef

SHA256:
71a399befd1536b83e4a43ca20a600b10626f6c9e95c77c3404e072179086572

---

## 3. Procedimento Realizado

- Identificação da evidência
- Geração de hash
- Cópia preservada
- Registro documental

---

## 4. Análise de Metadados

Foi realizada análise utilizando o comando `stat` para extração de metadados.

Os registros de tempo (atime, mtime e ctime) foram avaliados para verificar coerência temporal.

Não foram identificadas inconsistências entre os registros.

---

## 5. Análise de Timeline

Foi realizada listagem ordenada por data de modificação utilizando `ls -lt`.

A ordenação dos arquivos permitiu identificar a sequência cronológica de alterações no diretório analisado.

Arquivos modificados próximos ao horário do incidente foram priorizados para análise.

---

## 6. Análise de Conteúdo com Strings

Foi executado o comando `strings` para extração de conteúdo legível do arquivo analisado.

Foram identificadas sequências textuais que podem indicar:

- Comunicação de rede
- Dados sensíveis
- Possíveis indicadores de comprometimento

A técnica permite triagem rápida antes de análises mais aprofundadas.

---

## 7. Cadeia de Custódia

Foi aplicado controle formal de cadeia de custódia conforme checklist documentado.

Todos os procedimentos foram registrados, incluindo:

- Identificação da evidência
- Geração de hash
- Registro cronológico
- Documentação das etapas

Não houve quebra de integridade durante o processo.

---

## 8. Conclusão

A integridade da evidência foi preservada mediante geração de hash antes e após cópia.

Não foram identificadas alterações no arquivo analisado.
