Estou aprendendo um pouco mais sobre versionamento de código e também como usar a plataforma github!

Junto do terminal Linux. 

Em seguida aprendi a salvar o tolkien de acesso em uma credential cache, pois desta forma não vou precisar utilizar meu usuário e senha o tempo todo:
utilizei o comando 

git config --global credential.helper cache

e em seguida:

git config --global credential.helper 'cache --timeout=3600' (uma hora)

git push em seguida e pronto