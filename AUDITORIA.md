# Auditoria do simulado de Calorimetria

Auditoria de 2026-11-26. Fonte conferida: os 13 slides do professor André Lucas (fotos em `E:\estudos gabriel\calor\`) e o `calor_material_de_estudo` feito a partir deles.

## Resultado

- **Gabarito**: as 43 questões foram conferidas, inclusive todas as contas (Q18 a Q29, Q36, Q40, Q43). Nenhum gabarito errado.
- **Alternativas repetidas**: só **1 questão** tinha alternativas iguais (Q27: duas vezes "600 cal"). Corrigida. (Um relato anterior, de 27 questões repetidas, estava errado.)
- **Explicações erradas (`porque`) corrigidas em 14 alternativas** de cálculo e de teoria: várias diziam "saiu de X" com conta que não dava o número mostrado (Q20e, Q21a/c/d/e, Q22b/e, Q23b/e, Q24b/c, Q26a/e, Q27b); a Q28d dizia "usou c da água" mas o valor não batia (agora 20 000 cal); a Q21c chamava 40 °C de "média simples" (a média é 50); Q2b, Q4e e Q5d confusas ou ambíguas (a Q4e era parcialmente correta).
- **Aula**: typo "T_initial" na aula de sinal do calor.
- **Figuras**: os 3 diagramas SVG estavam sem acentos ("conducao", "radiacao", "dL", "alfa", "20 C"). Corrigidos (condução, convecção, radiação, ΔL, α, °C, sensível, mudança, até no vácuo) e conferidos por medição (nenhum texto fora do quadro).
- **Cobertura (+6 questões, 43 → 49)**: tempo a partir da potência; gelo a 0 °C até água a 20 °C (latente + sensível); capacidade térmica × massa; areia × água na praia; troca de calor com capacidades térmicas diferentes; dilatação superficial com número. Todas com bizu e ligadas à aula certa. O resto dos slides (calor, equilíbrio, sensível, latente, calor específico com a tabela, capacidade térmica, trocas, potência, mapa mental com dilatação e propagação) já estava coberto.
- **Ordem**: as questões agora seguem a ordem da matéria (teoria, depois contas por assunto, propagação, dilatação, unidades).
- **Tempo**: 1,5 min por questão: 49 × 1,5 = **73 min 30 s**.
- **Sorteio**: no máximo 2 respostas certas seguidas na mesma letra (300 sorteios testados: maior sequência 2; cada letra 9 ou 10 vezes em 49).

## Testes (navegador, servidor local)

`verificar.js` OK (49 questões, 15 aulas, 3 figuras); 300 sorteios sem perda de aula ou figura; 0 alternativas duplicadas; sem erro no console; cronômetro inicia em 73:30.

## Publicação

Não publicado. Para publicar: `bash publicar.sh "Auditoria: ..."`.
