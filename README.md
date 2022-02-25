# Projeto DIO   
## ProjetoDIO_Desafio21dias21Artigos  

Objetivo : Acolhimento aos padawans

Em 23 de Fevereiro de 2021, iniciei minha jornada como aluno na Digital Innovation One

Para comemorar este evento que mudou a minha vida. Apresento a proposta de Projeto.

### DESAFIO WEB.DIO.ME 21 dias 21 artigos

Uma forma de atrair, acolher, integrar e aprimorar a experiencia educacional em nossa plataforma, inumeros estudos confirmam que ao escrevermos sobre um assunto especifico a taxa de retençao do conhecimento é aumentada em 35% e a longo prazo as sinapses neurais nao desfragmentam-se mantendo o conhecimento adquirido por mais tempo. Incentivando a escrita iremos aprimorar a experiencia.

Nossa comunidade baseada numa plataforma Gameficada com milestones e objetivos, ao meu ponto de vista, tornara-se mais divertida com este DESAFIO, nos ultimos meses plantei a sementinha, diuvlgando constantemente nas Redes Sociais e no Forum da Comunidade o DESAFIO.

Extraoficialmente o DESAFIO 21 Artigos existe, porem falta o reconhecimento oficial e atribuiçao de premios reais. Primeiramente, a ideia original nao foi minha e infelizmente nao conheço o autor, mas estava eu, apos a saida do boteco online, andando aleatoriamente na Clear Web, quando o Google me alertou sobre alguem abandonado. Era um projeto do passado, triste, sozinho e solitario, conversei com ele e quando notei estava me seguindo. Alimentei o danado e o meme cresceu.

Numa comunidade beirando  os 700.000 DEVs inscritos, meu publico é 30% dos antigos e 100% dos novos inscritos. Na primeira fase aspiro atingir 210.000 pessoas, que ao publicarem 21 Artigos, ao final de 6 meses, teremos aproximadamente 441.000 artigos publicados. Imaginemos o alcanse,  a repercussao nos motores de busca, o grau de compartilhamento nas redes sociais. Teremos um engajamento lendario.  Afinal serao pessoas compartilhando textos, iremos incrementar o trafego em Lingua Portuguesa e criar uma mini-wikipedia.

Claro que existe reveses, iremos criar demanda de servidores e aumentar o  gasto per-capita em alojamento, poderao surgir problemas legais em LGPD e Direitos autorais. Mas solucionaveis, criando um plus e incentivo ao aluno a participar ativamente da Comunidade DIO.

#### Custos envolvidos

Custos de analise, desenvolvimento e deploy
Custos de aumento de trafego
Custos de aumento no alojamento
Custos de LOGs e chamadas ao HelpDesk

#### Premiaçao

Ira inflacionar o ecossistema, porem como é aberto a todos e sem data de expiraçao, no final ninguem sera prejudicado.

A cada artigo 100 XP e 10 Reputaçao ( 2100 XP e 210 Reputacao)

Badge 21 Artigos Start e Diploma Inicio do Desafio 40 XP

Badge 21 Artigos Champion e diploma Conclusao do Dasafio 

Padawan Badge 42 artigos publicados 40 XP 10 Reputaçao

Jedi Badge 84 artigos publicados 40 XP 10 Reputaçao

Mestre Jedi Badge 168 artigos publicados 40 XP 10 Reputaçao

Anciao Jedi Badge 336 artigos publicados 40 XP 10 Reputaçao

#### Controle e algoritmo

Sera criado uma pagina web semelhante a estrutura dos LABS, onde teremos alguns videos informativos. ( Gostaria de apresentar um deles  :)  )

Serao 21 linhas de input para inclusao da url do artigo, sistema CRUD

Apos inserir a url e salvar as alteraçoes, sera startado um processo batch para validaçao.

Devera validar url valida
Devera validar se o artigo  em questao pertence ao aluno
Devera validar minimo de 400 palavras
Devera validar existencia de palavras da Black List
Devera validar a existencia de hastags
Outras valiçoes que julgarem necessaria

Apos processo OK, efetivar pontos no Score

Em caso de Delete do Artigo, remover pontos do Score
Em caso de Update revalidar artigo

As tarefas serao encadeadas, liberando uma a uma, apos conclusao com sucesso da anterior, em caso de Delete a proxima é bloqueada.
