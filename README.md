# Ice videogames

## Descrição do Projeto
A loja online Ice vende videogames no mundo todo. As avaliações de usuários e especialistas, gêneros, plataformas (por exemplo, Xbox ou PlayStation) e dados históricos sobre vendas de jogos estão disponíveis em fontes abertas. Precisei identificar padrões que determinam se um jogo tem sucesso ou não. Isso permite identificações potenciais de grandes vencedores e planejar campanhas publicitárias.
Os dados remontam a 2016. Estamos em dezembro de 2016 e planejando uma campanha para 2017. O conjunto de dados contém a abreviatura ESRB. O Entertainment Software Rating Board avalia o conteúdo de um jogo e atribui uma classificação etária, como Adolescente ou Maduro.

## Pontos estudadados no projeto:
1. Preparar os dados: substituir os nomes das colunas (transformar tudo em minúsculos). Converta os dados para os tipos necessários. Lidar com valores ausentes.
2.	Calcular o total de vendas (a soma das vendas em todas as regiões) para cada jogo e coloque esses valores em uma coluna separada.
3. Analisar os dados:
- Quantos jogos foram lançados em anos diferentes Os dados de cada período são significativos?
-	Veja como as vendas variaram de plataforma para plataforma. Escolha as plataformas com as maiores vendas totais e construa uma distribuição com base em dados para cada ano. Encontre as plataformas que costumavam ser populares, mas agora não têm vendas. Quanto tempo leva para as novas plataformas aparecerem e as antigas desaparecerem?
-	Determine para qual período você deve pegar dados. Para fazê-lo, olhe para suas respostas para as perguntas anteriores. Os dados te deveriam permitir construir um modelo para 2017.
-	Trabalhar apenas com os dados que você decidiu que são relevantes. Desconsidere os dados de anos anteriores.
-	Quais plataformas estão liderando em vendas? Quais estão crescendo ou diminuindo? Selecione várias plataformas potencialmente lucrativas.
-	Construa um diagrama de caixa para as vendas globais de todos os jogos, divididos por plataforma. As diferenças nas vendas são significativas? E quanto às vendas médias em várias plataformas? Descreva suas descobertas.
-	Veja como as avaliações de usuários e profissionais afetam as vendas de uma plataforma popular (você escolhe). Construa um gráfico de dispersão e calcule a correlação entre revisões e vendas. Tire conclusões.
-	Tendo suas conclusões em mente, compare as vendas dos mesmos jogos em outras plataformas.
-	Dê uma olhada na distribuição geral de jogos por gênero. O que podemos dizer sobre os gêneros mais lucrativos? Você pode generalizar sobre gêneros com vendas altas e baixas?
4. Criar um perfil de usuário para cada região:
Para cada região (AN, UE, JP), determinei:
-	As cinco plataformas principais. Descreva as variações das suas quotas de mercado de região para região.
-	Os cinco principais gêneros. Explique a diferença.
-	As classificações do ESRB afetam as vendas em regiões individuais?
5. Teste as seguintes hipóteses:
- As classificações médias dos usuários das plataformas Xbox One e PC são as mesmas.
- As classificações médias de usuários para os gêneros Action (ação) e Sports (esportes) são diferentes.

## Descrição de dados:
- Name (nome)
- Platform (plataforma)
- Year_of_Release (Ano de lançamento)
- Genre(gênero)
- NA_sales (vendas norte-americanas em milhões de USD)
- EU_sales (vendas na Europa em milhões de USD)
- JP_sales (vendas no Japão em milhões de USD)
- Other_sales (vendas em outros países em em milhões de USD)
- Critic_Score - (Pontuação crítica) (máximo de 100)
- User_Score - (Pontuação do usuário) (máximo de 10)
- Classificação (ESRB)

