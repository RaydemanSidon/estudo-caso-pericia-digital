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

## 6. Conclusão

A integridade da evidência foi preservada mediante geração de hash antes e após cópia.

Não foram identificadas alterações no arquivo analisado.
