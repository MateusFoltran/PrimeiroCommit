# PrimeiroCommit🙌
Aprendendo como comandos Git Funcionam!🤔

**Funcionalidades Git:**


**1- Git add origin**

git remote add origin <URL_do_repositório_remoto>

**Ex:** 
git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git

Para verificar que foi adicionado corretamente --> git remote -v


**2- Criar e fazer o checkout para uma nova branch**

git checkout -b NOME-DA-BRANCH

**Ex:**
git checkout -b funcionalidade_x


**3- Checkout de um commit específico**

git checkout id-do-commit-específico

**Ex:**
git checkout PrimeiroCommit

**4- Fazer o checkout de uma branch existente**

git checkout NOME-DA-BRANCH

**Ex:**
git checkout Galho 1

**5- Forçar um checkout**

-f ou --force

**EX:**
git checkout -f NOME-DA-BRANCH

**6- Desfazer alterações em seu diretório de trabalho**

git checkout -- NOME-DO-ARQUIVO

**Ex:**
git checkout -- PlanetaTerra
