# Curso_ABAP_SAP
Curso SAP ABAP 
# SAP ABAP

# **CRIAR UM REPORT SIMPLES**

                                 **Transação – SE38 (Link, Programa SAP para criar)**

Nomenclatura para criação de um programa SAP, quando não é STANDARD deve iniciar com Z (Programa executável) ou Y (Um teste local)

                             **REPORT – é conhecido pelo tipo 1 para programa Executável**

# CRIANDO UM PACOTE

Pacote é como se fosse uma pasta no Windows por exemplo. Pacote é uma pasta para armazenar o objeto (Programa é um objeto).

Objeto Local é um objeto que não queremos mandar para outro servidor.

                                                  **TRANSAÇÃO – SE80**

É o Workbench da SAP para criar toda a estrutura de um programa em ABAP!

# TRABALHANDO COM REQUEST

REQUEST – é uma forma de registrar tudo que estamos alterando no sistema. (DEV – QS – PR)
TRABALHANDO COM REQUEST (BÁSICO)

Serve para identificar todo objeto dentro do ambiente.
1 – Ambiente Desenvolvimento - Cria os Objetos
2 – Ambiente Qualidade            -  É validado a criação do Objeto
3 – Ambiente Produção             -  Após validado é o ambiente que todos usuários tem acesso

                                                 **Conferir REQUEST – SE10**

Depois de criar a REQUEST no programa (SE38), basta ir até a SE10 para verificar as requests.  

# COMENTÁRIOS E IDENTAÇÃO DO CÓDIGO

                                          **Identação é para organizar o código.
                        Comentário é para entender partes complexas do programa.**

START OF SELECTION usado para que o programa entenda onde começara a executar.

Para identar o código basta clicar em “Pretty Printer”.

Para comentar quando está encostado da coluna começar com *

Para comentar da linha de código usar “

# TRABALHANDO COM VARIÁVEIS

Variável usado para armazenar uma informação temporariamente! 

                    Para declarar uma variável no SAP ABAP é através do **DATA**

                       **Obs: L é uma variável local - G é uma variável global** 

Após informar **DATA** informar o **TYPE** que é o tipo dessa variável. 

# **Tipos de Dados Padrão ABAP**

- **i** – integer 4 byte número inteiro + / – 2,1 bilhões
- **f** – floar 8 bytes, 15-16 dígitos significativos
- **c** – string de até 65 mil caracteres
- **n** – numeric string até 65 mil caracteres (número não-matemático)
- **string** – de comprimento dinâmico até 2 GB de comprimento!
- **xstring** – hex string seqüêncial de byte comprimento de dinâmico
- **x** – byte seqüêncial de até 65k bytes
- **d** – Data 8 caracteres de formato AAAAMMDD
- **t** – tempo 6 caracteres de HHMMSS
- **p**  – packed number preciso ou número flutuante de até 16 bytes

# TRABALHANDO COM CONSTANTES

A constante precisa definir o valor na própria linha. Exemplo no print abaixo: 

Quando a variável for constante declarar da seguinte forma: **LC - Local Constante**

# CONCATENANDO TEXTOS

A instrução **CONCATENATE** para juntar, usar o **INTO** (onde vou jogar o texto). 

# TELA DE SELEÇÃO COM PARÂMETRO
