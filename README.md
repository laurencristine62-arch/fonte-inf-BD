# fonte-inf-BD
atividades da disciplina fonte de dados
## Apresentação em equipe
Descrição...
https://www.canva.com/design/DAHSQ7I3CmY/xUpW03vKDc82RiS_js6OgA/view?utm_content=DAHSQ7I3CmY&utm_campaign=designshare&utm_medium=link&utm_source=viewer

## multimodais
1-qual é o estado (UF) com a maior quantidade de empresas habilitadas para o transporte mutimodal? resposta: São paulo, com 569 empresas. =CONT.SE(in!F:F;respostas!A7)

2-Qual é o percentual de empresas que aderiram ao Decreto 1.563/95? situação quantidade de empresas sim 275 =CONT.SE(in!J:J;"sim") não 1107 =CONT.SE(in!J:J;"não") total 1382 =SOMA(B42:B43

percentual de empresas que aderiram: 19,90% =B42/B44

https://github.com/laurencristine62-arch/fonte-inf-BD/blob/main/operador_transporte_multimodal%20(2).xlsx


<img width="482" height="291" alt="image" src="https://github.com/user-attachments/assets/624f406d-a90b-4e3c-a57a-38651dd7f1f0" />


<img width="486" height="297" alt="image" src="https://github.com/user-attachments/assets/2a90b881-bffc-43de-87ce-86dff6a4adf9" />

## Planilhas eletronicas e dados abertos
1- qual foi o preço médio da gasolina no 1º semestre de 2026 6,563056209 =MÉDIASE(in!K:K;"gasolina";in!M:M) resposta: no primeiro semestre de 2026, o preço médio da gasolina foi de aproximadamente R$ 6,56 por litro.

2- qual foi o preço médio do etanol no 1 semestre de 2026 4,709594645 =MÉDIASE(in!K:K;"etanol";in!M:M) resposta: no primeiro semestre de 2026, o preço médio do etanol foi de aproximadamente R$ 4,70 por litro.

3- qual combustível apresentado o maior preço médio no 1º semestre de 2026

combustível preço médio

gasolina 6,563056209 =MÉDIASE(in!K:K;"gasolina";in!M:M)

<img width="454" height="215" alt="image" src="https://github.com/user-attachments/assets/d4ef0166-1528-4c01-af91-5a353bc947ce" />

etanol 4,709594645 =MÉDIASE(in!K:K;"etanol";in!M:M)
diesel 6,760092985 =MÉDIASE(in!K:K;"diesel";in!M:M) diesel S10 6,887436137 =MÉDIASE(in!K:K;"diesel s10";in!M:M) gasolina aditivada 6,76022776 =MÉDIASE(in!K:K;"gasolina aditivada";in!M:M) GNV 4,538153372 =MÉDIASE(in!K:K;"gnv";in!M:M) resposta: o combustível que apresentou o maior preço médio no primeiro semestre foi o diesel s10, com preço médio de aproximadamente R$ 6,88 por litro.

4- qual estado apresentou o maior preço médio da gasolina

Estado média da gasolina AC 7,478528428 BA 7,020079461 ES 6,496094756 TO 6,923530806

<img width="480" height="294" alt="image" src="https://github.com/user-attachments/assets/03ff40f5-e087-45e5-9d8e-9478e2b532f2" />

MA 6,505531136
MG 6,335679913
PA 6,711133652 PE 6,84390958 PI 6,39610951 PR 6,659243892 RJ 6,554545455 RS 6,446282697 SP 6,423757319 PB 6,344294258 RN 6,754543762 AL 6,680080375 AM 7,305191612 CE 6,731663701 DF 6,433608661

7,478528428 =MÁXIMO(B25:B44) resposta: o estado que apresentou o maior preço médio da gasolina no primeiro semestre de 2026 foi o Acre (AC) , com aproximadamente R$ 7,48 por litro.

5- como o preço médio da gasolina variou entre janeiro e junho de 2026

mes preço médio da gasolina
janeiro 6,325559491 =MÉDIASES(in!M:M;in!K:K;"gasolina";in!L:L;">="&DATA(2026;1;1);in!L:L;"<"&DATA(2026;2;1)) fevereiro 6,311746227 =MÉDIASES(in!M:M;in!K:K;"gasolina";in!L:L;">="&DATA(2026;2;1);in!L:L;"<"&DATA(2026;3;1))

março 6,602841909 =MÉDIASES(in!M:M;in!K:K;"gasolina";in!L:L;">="&DATA(2026;3;1);in!L:L;"<"&DATA(2026;4;1))


<img width="485" height="304" alt="image" src="https://github.com/user-attachments/assets/30a03844-c6d1-406a-86cf-5c9de9754ce8" />
abril 6,762000435 =MÉDIASES(in!M:M;in!K:K;"gasolina";in!L:L;">="&DATA(2026;4;1);in!L:L;"<"&DATA(2026;5;1))
maio 6,677873461 =MÉDIASES(in!M:M;in!K:K;"gasolina";in!L:L;">="&DATA(2026;5;1);in!L:L;"<"&DATA(2026;6;1)) junho 6,656689063 =MÉDIASES(in!M:M;in!K:K;"gasolina";in!L:L;">="&DATA(2026;6;1);in!L:L;"<"&DATA(2026;7;1))

resposta:o preço médio da gasolina apresentou uma pequena queda de janeiro para fevereiro, passando de R$6,32 para R$6,31. A partir de março, houve aumento, chegando ao maior valor em abril com R$6,76.

https://centropaulasouza-my.sharepoint.com/:x:/r/personal/lauren_santos01_aluno_cps_sp_gov_br/Documents/Pre%C3%A7os%20semestrais%20-%20AUTOMOTIVOS_2026.01.xlsx?d=w4ae5a98cb9114af4a45d155f2d1d0462&csf=1&web=1&e=GgygiX

## empresas multimodais no power bi

<img width="1319" height="816" alt="image" src="https://github.com/user-attachments/assets/3fcbd522-9ddd-4c3f-bcc1-391fc901b976" />


## Análise de Dados – Educação Superior
onte: INEP – Censo da Educação Superior.
Pergunta 1: Como evoluiu o número de matrículas entre 2019 e 2024?

Resposta: O número de matrículas passou de 2.031.349 em 2019 para 2.440.800 em 2024, apresentando crescimento no período.

Pergunta 2: Qual rede de ensino possui mais matrículas?
Resposta: A rede privada, com 11.042.668 matrículas no período analisado.
Pergunta 3: Qual modalidade possui mais matrículas?
Resposta: A modalidade presencial, com 7.822.249 matrículas.
Pergunta 4: Qual grau acadêmico possui mais matrículas?



Resposta: O bacharelado, com 8.022.755 matrículas.
Pergunta 5: Qual é a distribuição das matrículas por sexo?
Resposta: Foram registradas 7.543.178 matrículas femininas e 5.557.991 masculinas
<img width="1310" height="739" alt="image" src="https://github.com/user-attachments/assets/cf5c5234-f309-4c91-ae9b-c1e466e93879" />
