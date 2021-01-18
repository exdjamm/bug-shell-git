# bug-shell-git
## Demostração de um bug de identificação de usuario no github.
É possivel fazer um commit como um outro usuario.

Primeiro é necessario fazer login no shell como um usuario que tem permissão de commit no repositorio.
No shell, coloque a config local com os valores do outro usuario:
- author.email
- user.name
- user.email

Faça o commit.

## O que acredito que seja
O servidor git não tem uma forma de teste se quem está fazendo o commit é o mesmo da informação passada.

O bug funciona com o clone https e acredito que funcione com o ssh.
Acho que isso pode abrir algumas falhas de segurança, mas não testei.

# Outras
A conta qual usei a info de email e nome de usuario são um amigo meu e tenho permissão para o ato.
