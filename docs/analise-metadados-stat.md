# Análise de Metadados com STAT

## Objetivo

Realizar análise técnica de metadados do arquivo coletado como evidência digital.

---

## Comando Utilizado

stat arquivo_teste.txt

---

## Saída Obtida

File: arquivo.teste.txt
Size: 17              Blocks: 8          IO Block: 4096   regular file
Device: 0,136   Inode: 19468       Links: 1
Access: (0644/-rw-r--r--)  Uid: (    0/    root)   Gid: (    0/    root)
Access: 2026-02-07 23:56:20.638930311 +0000
Modify: 2026-02-07 23:56:03.009459588 +0000
Change: 2026-02-07 23:56:03.009459588 +0000
Birth: 2026-02-07 23:56:03.009459588 +0000

---

## Interpretação Técnica

- **Size**: Indica o tamanho do arquivo em bytes.
- **Blocks**: O sistema alocou 8 blocos de 512 bytes (padrão POSIX), totalizando 4096 bytes fisicamente reservados.
- **IO Block**: Tamanho do bloco lógico do sistema de arquivos (4 KB), que define a unidade mínima de alocação.
- **Inode**: Identificador único no sistema de arquivos.
- **Access (atime)**: Última vez que o arquivo foi acessado.
- **Modify (mtime)**: Última modificação do conteúdo.
- **Change (ctime)**: Última alteração nos metadados.

A análise das timestamps auxilia na reconstrução da linha temporal dos eventos.

---

## Relevância Forense

A verificação de metadados é essencial para:

- Identificação de manipulações
- Construção de timeline
- Correlação com logs do sistema
- Validação da integridade contextual da evidência
