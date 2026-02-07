# Procedimento de Coleta de Evidência

## Objetivo

Realizar cópia preservando integridade da evidência digital.

---

## 1. Identificação do Arquivo Suspeito

Exemplo:

/home/usuario/Downloads/arquivo_suspeito.exe

---

## 2. Geração de Hash

MD5:

md5sum arquivo_suspeito.exe

SHA256:

sha256sum arquivo_suspeito.exe

---

## 3. Registro dos Hashes

Os valores de hash devem ser registrados no relatório técnico para garantir integridade futura.

---

## 4. Cópia da Evidência

cp arquivo_suspeito.exe /evidencias/

---

## Considerações

Nunca analisar o arquivo diretamente no ambiente original. Sempre trabalhar em cópia.
