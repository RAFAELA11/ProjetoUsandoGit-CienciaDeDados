# Projeto Avaliativo Bootcamp de Ciência de Dados



## Disciplina: Noções de Git e GitHub



#### Elaboração do escopo e início do Projeto

- [x] Levantamento da necessidade do Projeto Macro;
- [x] Levantamento das necessidades específicas dentro do projeto;
- [x] Levantamento de requisitos referentes as modificações requeridas;
- [x] Refinamento e Testes;
- [x] Definições das novas regras aplicadas;
- [x] Apresentação das novas regras 
- [ ] Aprovação do avaliador.

#### Definição e plano do projeto

1. ##### Levantamento da necessidade do Projeto Macro;

   O objetivo deste projeto é avaliar o desempenho do programador em aprender os conceitos, definições e utilização do Git e GitHub para que no futuro possa hospedar seu portfólio nesta plataforma (GitHub).

2. ##### Levantamento das necessidades específicas dentro do projeto;

   Há a necessidade de modificar alguns comandos para a realização das atividades, visto que a máquina usada durante o curso, não suporta alguns formatos e programas. Também existe discrepância entre as versões Git usada atualmente na máquina e a versão usada didaticamente.

3. ##### Levantamento de requisitos referentes as modificações requeridas;

   Usando como base o site do GitHub, as documentações disponibilizam os comandos mais atuais referentes a cada passo explicado durante o curso. Estarei citando as diferenças que existiram entre o conteúdo administrado entre as aulas e a minha máquina:

   

   3.1. Chave SSD - A chave suportada pela máquina é:

   ###### SSH-keygen -t rsa -b 4096 -C "E-mail do Github" 

   Na fase de ativação do Token de segunça, diretório das chaves públicas e privadas, vão ser em um formato específico, para identificá-lo, use:

   ###### ls -al ~/.ssh

   A chave pública terá a extensão .pub.

   

   3.2. Para iniciar um repositório Git, após o uso do Git Init, devido minha versão, teremos que converter de (master) para (main), para isso, usamos o comando:

   ###### Git branch -m main

   Em seguida, o comando de ativação será:

   ###### Git add .

   Em seguida, o comando de commitar será o mesmo expressado no curso. Isto porque é importante reforçar que o repositório local precisa ser populado apenas por commits, para que ele seja apontado para um repositório remoto.

   ###### Git commit -m "texto identificador da versão usada"

   Para colocar o repositório local em Staged no repositório remoto (servidor).

   ######  Git remote add origin git@github.com:RAFAELA11/Primeiro-Repositorio-Dio.git

   Para associar o repositório local ao repositório remoto:

   ###### Git push -u origin main

   Para atualizar a versão do conteúdo no GitHub, consultamos o status com o Git Status e commitamos com o comando:

   ###### Git commit -m "texto identificador da versão usada"

   Novamente teremos que repetir o processo de associar o repositório local ao repositório remoto:

   ###### Git push -u origin main

   Finalização do processo. A versão mais atual já estará no GitHub

4. ##### Refinamento e Testes;

   Os comandos foram testados e validados.

5. ##### Definições das novas regras aplicadas;

   Estas definições serão estabelecidas através da documentação do projeto avaliativo.

6. ##### Apresentação das novas regras e aprovação do avaliador.

   Esta comunicação será feita através do projeto avaliativo.

   

#### Controle e desempenho do Projeto

O projeto foi feito em paralelo com a realização das aulas e as referências usadas foram as documentações disponibilizadas pelos sites oficiais com as devidas traduções.

#### Fechamento do projeto

Aguardando Aceite do projeto.

