# Comando importantes para saber
**Observação:** Esse documento não tem o intuito de servir como uma documentação do git, e sim só como uma lista com os comandos mais básicos do git. Para um melhor aprofundamento na tecnologia git ***use o link para a documentação***.

## | 🕹️ Comandos Básicos e para que servem! |
- `git init`: 
    - Esse comando inicia um repositório.
- `git clone url` :
    - Copia para seu repositório local um outro repositório existente.
- `git commit -m"" ` :
    - Salva alterações feitas no repositório local;
    - O `-m""` serve para adicionar uma mensagem sobre o commit.
- `git commit --amend -m""` :
    - Permite a alteração da mensagem do último commit realizado.
- `git push -u origin main` :
    - Manda as altereações feitas no repositório local para o remoto.
- `git pull`:
    - Puxa alterações feitas no repositório remoto para o local.
- `git add nome da pasta/arquivo`
    - Prepara aquivos alterados que foram citados para serem commitados.
- `git add .` :
    - Prepara todos os arquivos alterados para serem commitados.
- `git status` :
    - Mostra arquivos que foram alterados;
    - Mostra arquivos prontos para serem commitados.
- `git log` :
    - Mostra todos os commits realizados.
- `git remote add origin url`
    - Utilizado quando é necessário adicionar um repositório remoto para o local. 
- `touch` :
    - Cria arquivos nas pastas do repositório
- `git restore arquivo`:
    - Descarta as alterações que foram feitas;
    - Precisa que informe o nome do arquivo que você quer descartar as alterações.
- `git reset --tipo-do-reset hash-do-commit` :
    - Desfaz um commit e retorna a um anterior:
    - Possui 3 tipos: `soft`, `mixed` e `hard`;
    - `soft`: volta ao commit anterior e manda os arquivos do commit excluído para a área de preparação para commitar;
    - `mixed`: é o tipo padrão do reset, ele pega os arquivos e coloca na área onde são mostradas como alterados;
    - `hard`: reseta e descarta os arquivos do commit excluído.

## |🧩 Dicas Git |

- Quando você usar o `git log`, para voltar a digitar aperte a letra ***q***; 

## |📚 Referências |

Recomendo muito ver o curso abaixo, a professora explica muito bem e o conhecimento adquirido já é o bastante para começar a usar o Git e GitHub!
- [Curso Versionamento de código com Git e GitHub](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/f3cbaa66-efbd-4c25-842e-2069c188c066?back=/track/potencia-tech-ifood-desenvolvimento-de-jogos&tab=undefined&moduleId=undefined)
