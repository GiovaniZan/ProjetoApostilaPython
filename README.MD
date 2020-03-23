# Apostila Python Versão em LATEX e versionamento em GIT

<h2> Objetivo deste trabalho </h2>

Apostila para ensino de Python básico para pessoas sem conhecimento prévio de coisa alguma mas que querem fazer coisas para as quais é necessário saber de um monte de coisas, mas sem precisar aprender este monte de coisas. Credo!  

Apostila para ensino de Python básico para pessoas sem conhecimento prévio de programação ou de matemática avançada mas que querem resolver problemas práticos através de programação: Automação de planilhas, cálculos estatísticos, gráficos simples. Guia de receitas e modelos para resolução de problemas numéricos.
(Referenciar tudo na literatura na esperança que o aluno se aprofunde e deixe de ser um simples usuário)

--- 
## TO DO
  - Arrumar um ilustrador... Melhor alguém com habilidades de desenho... 
  - Decidir o nível do texto de introdução à linguagem 
  - Treinamento básico ao uso de módulos... 
  - Treinamento mais avançado - SciPy e NumPy
  - Fazer banco de problemas a serem resolvidos através de Python para elaborar um "cookbook" 
  - Separar capítulos em arquivos individuais quando o troço ficar grande.
  - 
## DONE
   - Troço iniciado
   - Projeto no GitHub 

---

## "O Estado da coisa" 
 ### 22/03/2020
   1. Iniciado a apostila 2, com arquivo principal : "Apostila_Python_CookBook_Parte2.tex", usando mesmo arquivo de referências bibliográficas  "Apostila_Python_References.bib".
   2. O arquivo "Apostila_Python_CookBook_Parte2.tex" inclui ao ser compilado o arquivo "APC_Parte2_EstatiBasica_v1.tex", que contém apenas o conteúdo sob o capítulo de NumPy e Estatística básica.

 ### 21/03/2020
  1. Para usar o Visual Studio Code como GUI para o LaTex, é necessário instalar a extensão "LaTex Workshop". Recomendado também a "LaTex language support" e "LaTex Snippets". 
  2. Consertado referência no arquivo "Apostila_Python_References.bib". Múltiplos autores são separados pela palagra "and" e não por vírgula! (Muuula!)
  3. Projeto colocado no GitHub para compartilhamento / versionamento.   

 ### 21/03/2020
  1. Esqueleto da apostila em AbnTex2 funcionando. "Apostila_Python_CookBook.tex"
     1. Futuramente separamos os capítulos em arquivos individuais
  2. Iniciado arquivo de referências bibliográficas: "Apostila_Python_References.bib"
      1. gerenciado pelo software JabRef. ( As referências bibliográficas são chatas de gerenciar diretamente por LATEx devido a formatação. Este software torna as coisas mais fáceis. )
   3. Ainda não consegui descobrir como fazer o Visual Studio Code compilar corretamente o arquivo tex. Recomendo o TeXworks (padrão do MikTex) para edição. [utilizar utf8]     

 ### 15/03/2020 
  1. criação deste arquivo

---  
## Autores e colaboradores 

Giovani Zanelatto - LATEX guru 

Victor Bergossi - 

Gabriel Selow - 

Leo ?? 9687-1698

9846-7571


---
## Por que LATEX 

Resposta simples: 
 1. Porque o Word é uma porcaria em termos de tipografia de textos longos. 
 2. Grande liberdade aumenta muito a chance de fazer errado.

Resposta elaborada: 
 1. Porque LATEX oferece inúmeras vantagens de formatação e reformatação para textos longos. 
 2. Se você não tem medo de escrever um texto em markdown (este tipo de texto) ou HTML, não terá problema algum com LATEX.
 3. O posicionamento e numeração de figuras, tabelas e referências é feito de modo automático e seguindo as regras da tipografia internacional.  
 4. O uso do pacote ABNTEX coloca o documento no formato ABNT de forma indolor. Neste caso, documento feio é culpa da ABNT (Absurd Norms for Text).
 5. O texto em LATEX provilegia o conteúdo. Enquanto se digita um texto em LATEX não somos importunados ou distraídos pela formatação. 
 6. Aprendendo LATEX, você não vai querer usar outra coisa para seu TCC, Dissertação, Tese ou Artigo.


<h2> Por que GIT </h2>

 1. Por que em algum momento alguma merda vai acontecer.
    1. Perderemos o original...
    2. Faremos alguma modificação involuntária...
    3. Nos arrependeremos de alguma mudança...
 2. Por que o trabalho é conjunto. Todos devem opinar e sugerir.  
 3. Manteremos o controle das versões, que poderão ser modificadas a medida em que o material necessitar de atualização ou adequação.

## JabRef 
Este programa organiza a lista de bibliografia, gerando um arquivo .bib que o LaTex usa para resolver a bibliografia. Somente itens citados (referenciados) é que vão para o texto. Toda a organização e tipografia de citação é definida pelo LaTex / BibTex, de acordo com o formato escolhido - ABNT neste caso.
1. Nomes de autores devem ser separados pela palavra "and"
2. Nomes com mais de uma alternativa de esrita devem ser separados por "or" 
