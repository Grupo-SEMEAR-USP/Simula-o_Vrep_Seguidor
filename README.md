# Simulação CoppeliaSim - Seguidor de Linha

### Descrição
Repositório utilizado para apresentar os conceitos básicos de simulação robótica utilizando o simulador CoppeliaSim. Utilizado no treinamento aplicado para o Grupo SEMEAR.

### Requisitos:
Os requisitos para conseguir compilar e executar as implementações são:
- CMake Version 3.5.1
- GCC 5.4.0
- C11 Standard Version

### Como usar:
- Clone o repositório e entre na pasta **build**, onde ficará os arquivos de configuração CMake: 
```console
username@user-computer:~$ cd Simulação_Vrep_Seguidor/build
```
- Apague os arquivos atuais na build
```console
username@user-computer:~/Simulação_Vrep_Seguidor/build$ rm -rf ./*
```
- Execute o comando cmake para configurar o ambiente:
```console
username@user-computer:~/Simulação_Vrep_Seguidor/build$ cmake ..
```
- Chame o make para compilar:
```console
username@user-computer:~/Open_2020/build$ make
```
- Abra a simulação **Seguidor_Simulaçao.ttt** no CoppeliaSim
- Aperte em START/RESUME para iniciar a simulação

- O arquivo executável gerado ao compilar se chama **cppremoteapi.exe**, para executá-lo faça:
```console
username@user-computer:~/Open_2020/build$ ./cppremoteapi
```

