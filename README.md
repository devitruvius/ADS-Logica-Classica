# Conceitos de Lógica Clássica

## Objetivo

Este repositório contém questões de lógica clássica resolvidas como parte das atividades relacionadas à disciplina de Introdução à Lógica de Computação, do curso Análise e Desenvolvimento de Sistemas (ADS) pela Universidade Federal do Cariri (UFCA). As questões foram elaboradas para explorar e consolidar os conceitos fundamentais da lógica clássica e sua aplicação em problemas práticos.

## Estrutura do Repositório

O conteúdo está organizado em tópicos correspondentes a cada conjunto de questões. Cada tópico inclui as questões específicas resolvidas para aquela atividade. A estrutura do repositório foi pensada para facilitar a navegação e revisão das questões, proporcionando uma experiência intuitiva aos usuários.

## Questionário

1. **Como um silogismo é estruturado e qual sua aplicação na lógica?**

   ```python
   class Silogismo:
    def __init__(self, premissa_maior, premissa_menor, conclusao):
        self.premissa_maior = premissa_maior
        self.premissa_menor = premissa_menor
        self.conclusao = conclusao

    def validar_silogismo(self):
        # Verifica se as premissas implicam na conclusão
        return self.premissa_maior and self.premissa_menor == self.conclusao


   # Exemplo de Silogismo utilizando FBFS
   premissa_maior = True   # P -> Q
   premissa_menor = True   # Q -> R
   conclusao = True        # P -> R
   
   silogismo = Silogismo(premissa_maior, premissa_menor, conclusao)
   print("Silogismo é válido:", silogismo.validar_silogismo())


2. **O que afirma o princípio da identidade na lógica clássica?**

   ```python

3. **Qual é o principal problema da falácia do apelo à ignorância?**

   ```python

4. **Qual é o significado do princípio da não contradição na lógica clássica?**

   ```python

5. **O que caracteriza a falácia do espantalho?**

   ```python
  
6. **Como o princípio do terceiro excluído é aplicado na lógica clássica?**

   ```python
  
7. **Qual é a principal preocupação ao identificar a falácia do apelo à autoridade?**

   ```python
  
8. **Como podemos definir a inferência indutiva?**

   ```python

9. **Como podemos definir a lógica formal?**

   ```python

10. **Qual é a relação entre silogismo e falácia na estrutura argumentativa?**

    ```python

11. **O que caracteriza uma falácia em um argumento?**

    ```python

12. **Como a proposição se diferencia de premissa em um argumento lógico?**

    ```python
