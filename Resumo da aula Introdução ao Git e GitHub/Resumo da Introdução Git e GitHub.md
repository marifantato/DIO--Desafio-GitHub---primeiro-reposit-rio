Comandos Básicos Utilizados no GIT (windows):

- cd (mudar diretórios/pastas)
- ls (listar pastas)
- mkdir (criar diretórios/pastas)
- del/rmdir (deletar)
- ctrl+l (limpa o terminal)
- ls -a (mostra arquivos ocultos)
- cd ..(volta para pasta anterior)
- mv (para mover arquivo/pasta)
- md (markdown #)
- git add\* (commitar/joga para staged)
- git commit -m
- git init (iniciar repositório Git)
- git status (atualiza o que foi feito)
- git push origin master
- git pull origin master

INSTALAÇÃO DO GIT:

https://git-scm.com/

OBJETOS:

- Blob (guarda o SHA [dados de encriptação que gera um conjnto de 40 caractéries] do arquivo, insere um meta dado)
- Árvore (apontam Blobs ou outras árvores, retém informações de város arquivos)
- Commit (dá sentido ao que está sendo desenvolvido, aponta autor e mensagem, data e hora da sua criação)



CHAVES:

O GitHub aprsenta um sistema distribuído seguro onde o código representa a versão final de um sistema. É possível que cada pessoa obtenha uma versão do mesmo código.

- Chave SSH (o servidor é reconhecido ao configurar acesso)
- Chave Token (além da senha padrão, pedirá uma senha "rotativa", que se altera dentro de um determinado período de tempo)


CICLO DE VIDA DOS ARQUIVOS NO GIT:


TRACKED

UNTRACKED         UNMODIFIED         MODIFIED                STOGED

(arq. que não temos ciência)  (arq. s/ alteração)   (arq. modificado) (arq. vai entrar em cena)




GITHUB:

O arquivo compartilhado sobe de um servidor para a rede, onde outro servidor pode fazer um clone do arquivo e ambos trabalham neste mesmo arquivo.

Quando ambos servidores fazem alterações na mesma linha do arquivo é gerado um erro ao salvar. O servidor que compartilhou o arquivo irá receber uma notificação sobre as modificações que o outro servidor fez.

Manualemente o servidor que comportilhou o arquivo fará as alterações que julgar necessário e salavrá o arquivo novamente em rede.

Desta forma temos o controle  das versões dos arquivos, armazenamos eles em núvens, trabalhamos em equipe e melhoramos nosso código.
