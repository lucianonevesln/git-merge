# Estudos Git - Merge

## Objetivo:

### Criar passo a passo para simples para utilização do comando "git merge".

## Passo a Passo:

#### 0 - Criação de diretório;

#### 1 - Criação de arquivo para teste;

#### 2 - Inserção de texto qualquer para teste no arquivo criado;

#### 3 - Execução do comando "git init";

#### 4 - Execução do comando "git add .";

#### 5 - Execução do comando "git commit -m "<comentario>"";

#### 6 - Execução do comando "git -M main";

#### 7 - Execução do comando "git remote add origin <repositorio_externo>";

#### 8 - Execução do comando "git push -u origin main";

#### 9 - Execução do comando "git checkout -b branch1";

#### 10 - Alteração de texto na branch1 e execução de passos 4, 5 e 8;

#### 11 - Execução do comando "git merge", para o caso de não haver conflito, e execução de passos 5 e 8;

#### 12 - Execução do comando "git merge <nome_branch>", para os casos de haver conflito e execução de passos 4, 5 e 8;

#### 13 - OBS: execução do comando "git merge --abort", para os casos em haja decisão de desistência do merge;