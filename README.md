# ⚽ Liga-Portugal-21-22 
Dados relativos ao Campeonato de Futebol Masculino Português, relativos à época 2021-2022.

![image](https://user-images.githubusercontent.com/103261052/171031369-f8b31329-0b46-4eff-9683-ffc7e9bf7afe.png)

⚽ Este repositório tem como objetivo analisar estatisticamente a época 2021/22 da 1ª liga portuguesa de futebol.

# 🤔Contexto

Com este repositório pretendemos fornecer, a todos aqueles que estiverem interessados, um conjunto de dados sobre a época 2021/22 da Liga Portugal (1ª Liga Portuguesa de Futebol Masculino). 

Apesar de atualmente dispormos de bastantes referências que nos podem informar sobre os campeonatos de futebol a nível global, queremos que este repositório sirva para fundamentar uma análise mais estatística e aprofundada do passado Campeonato Nacional para fins de registos estatístico-históricos.

Neste repositório, poderemos averiguar diferentes vertentes estatísticas que consideramos importantes para o estudo analítico dos jogadores, das equipas e do campeonato em si. Com este repositório, obteremos um registo que poderá ser usado para estudos analíticos ou estatísticos do nosso campeonato.

# 🧱Estrutura

Este repositório está organizado da seguinte forma:

+ `cartoes.csv`: Registo dos cartões amarelos e vermelhos durante a época, extraído do site [ESPN](https://www.espn.com.br/futebol/estatisticas/_/liga/POR.1/vista/cartoes)
+ `classificação.csv`: Classificação final da época 21/22 da Liga Portugal, extraída do site [MaisFutebol](https://maisfutebol.iol.pt/liga/resultadoseclassificacao)
+ `classificacao_casa.csv`: Classificação final, apenas contabilizando os jogos em que as equipas jogaram em casa, extraído do site [Footy Stats](https://footystats.org/portugal/liga-nos/home-away-league-table)
+ `classificacao_fora.csv`: Classificação final, apenas contabilizando os jogos em que as equipas jogaram fora, extraído do site [Footy Stats](https://footystats.org/portugal/liga-nos/home-away-league-table)
+ `classificacao_intervalo.csv`: Classificação final, apenas contabilizando os jogos até ao final do primeiro tempo, extraído do site [Footy Stats](https://footystats.org/portugal/liga-nos/half-time-table)
+ `classificacao_intervalo_casa.csv`: Classificação final, apenas contabilizando os jogos até ao final do primeiro tempo em que as equipas jogaram em casa, extraído do site [Footy Stats](https://footystats.org/portugal/liga-nos/half-time-table)
+ `classificacao_intervalo_fora.csv`: Classificação final, apenas contabilizando os jogos até ao final do primeiro tempo em que as equipas jogaram fora de casa, extraído do site [Footy Stats](https://footystats.org/portugal/liga-nos/half-time-table)
+ `defesas_guarda_redes.csv`: Top 20 dos guarda-redes com maior número de defesas ao longo da época, extraído do site [Liga Portugal](https://www.ligaportugal.pt/pt/liga/estatisticas/20212022/ligaportugalbwin/defesas)
+ `jogos.csv`: Registo total de todos os jogos da época 21/22 da Liga Portugal, extraído do site [Football-Data.co.uk](https://www.football-data.co.uk/portugalm.php)
+ `melhores_marcadores.csv`: Top 20 dos melhores marcadores ao longo da época, extraído do site [Liga Portugal](https://www.ligaportugal.pt/pt/liga/estatisticas/topmarcadores/20212022/ligaportugalbwin)

# 📔 Dicionário dos dados

Explicações em `cartoes.csv`

| Nome da coluna        | Significado
| ------------- |:-------------:|
| `clube` | Respetivo clube do campeonato português
| `partidas_efetuadas` | Quantidade de jogos que o clube disputou
| `cartoes_amarelos` | Número de cartões amarelos que o clube cometeu durante a época
| `cartoes_vermelhos` | Número de cartões vermelhos que o clube cometeu durante a época

Explicações em `classificação.csv`

| Nome da coluna        | Significado
| ------------- |:-------------:|
| `equipa` | Respetiva equipa do campeonato português
| `jogos_jogados` | Respetivo número total de jogos que a equipa jogou (contam os jogos em casa e fora)
| `vitorias` | Número de vitórias da equipa no campeonato
| `empates` | Número de empates da equipa no campeonato
| `derrotas` | Número de derrotas da equipa no campeonato
| `golos_marcados` | Número de golos marcados pela equipa durante o campeonato
| `golos_sofridos` | Número de golos sofridos pela equipa durante o campeonato
| `diferenca_golos` | Diferença entre os golos marcados e os golos sofridos pela equipa durante o campeonato
| `pontos` | Pontuação final da equipa no campeonato

Explicações em `classificação_casa.csv`

| Nome da coluna        | Significado
| ------------- |:-------------:|
| `equipa` | Respetiva equipa do campeonato português
| `jogos_jogados` | Respetivo número total de jogos que a equipa jogou (contam epenas os jogos feitos em casa)
| `vitorias` | Número de vitórias caseiras da equipa no campeonato
| `empates` | Número de empates caseiras da equipa no campeonato
| `derrotas` | Número de derrotas caseiras da equipa no campeonato
| `golos_marcados` | Número de golos marcados em casa pela equipa durante o campeonato
| `golos_sofridos` | Número de golos sofridos em casa pela equipa durante o campeonato
| `diferenca_golos` | Diferença entre os golos marcados e os golos sofridos em casa pela equipa durante o campeonato
| `pontos` | Pontuação final (apenas contabilizando os jogos em casa) da equipa no campeonato

Explicações em `classificação_fora.csv`

| Nome da coluna        | Significado
| ------------- |:-------------:|
| `equipa` | Respetiva equipa do campeonato português
| `jogos_jogados` | Respetivo número total de jogos que a equipa jogou (contam epenas os jogos fora)
| `vitorias` | Número de vitórias fora da equipa no campeonato
| `empates` | Número de empates fora da equipa no campeonato
| `derrotas` | Número de derrotas fora da equipa no campeonato
| `golos_marcados` | Número de golos marcados fora pela equipa durante o campeonato
| `golos_sofridos` | Número de golos sofridos fora pela equipa durante o campeonato
| `diferenca_golos` | Diferença entre os golos marcados e os golos sofridos fora pela equipa durante o campeonato
| `pontos` | Pontuação final (apenas contabilizando os jogos fora) da equipa no campeonato

Explicações em `classificação_intervalo.csv`

| Nome da coluna        | Significado
| ------------- |:-------------:|
| `equipa` | Respetiva equipa do campeonato português
| `jogos_jogados` | Respetivo número total de jogos que a equipa jogou (contam os jogos em casa e os jogos fora)
| `vitorias` | Número de vitórias ao intervalo da equipa no campeonato 
| `empates` | Número de empates ao intervalo da equipa no campeonato
| `derrotas` | Número de derrotas ao intervalo da equipa no campeonato
| `golos_marcados` | Número de golos marcados até ao final do 1º tempo pela equipa durante o campeonato
| `golos_sofridos` | Número de golos sofridos até o final do 1º tempo pela equipa durante o campeonato
| `diferenca_golos` | Diferença entre os golos marcados e os golos sofridos até ao final do 1º tempo pela equipa durante o campeonato
| `pontos` | Pontuação final (apenas contabilizando os jogos até o intervalo) da equipa no campeonato

Explicações em `classificação_intervalo_casa.csv`

| Nome da coluna        | Significado
| ------------- |:-------------:|
| `equipa` | Respetiva equipa do campeonato português
| `jogos_jogados` | Respetivo número total de jogos que a equipa jogou (contam apenas os jogos em casa)
| `vitorias` | Número de vitórias caseiras ao intervalo da equipa no campeonato 
| `empates` | Número de empates caseiros ao intervalo da equipa no campeonato
| `derrotas` | Número de derrotas caseiras ao intervalo da equipa no campeonato
| `golos_marcados` | Número de golos marcados pela equipa da casa até ao final do 1º tempo pela equipa durante o campeonato
| `golos_sofridos` | Número de golos sofridos pela equipa da casa até o final do 1º tempo pela equipa durante o campeonato
| `diferenca_golos` | Diferença entre os golos marcados e os golos sofridos em casa até ao final do 1º tempo pela equipa durante o campeonato
| `pontos` | Pontuação final (apenas contabilizando os jogos em casa até o intervalo) da equipa no campeonato

Explicações em `classificação_intervalo_fora.csv`

| Nome da coluna        | Significado
| ------------- |:-------------:|
| `equipa` | Respetiva equipa do campeonato português
| `jogos_jogados` | Respetivo número total de jogos que a equipa jogou (contam apenas os jogos fora)
| `vitorias` | Número de vitórias fora ao intervalo da equipa no campeonato 
| `empates` | Número de empates fora ao intervalo da equipa no campeonato
| `derrotas` | Número de derrotas fora ao intervalo da equipa no campeonato
| `golos_marcados` | Número de golos marcados pela equipa a jogar fora até ao final do 1º tempo pela equipa durante o campeonato
| `golos_sofridos` | Número de golos sofridos pela equipa a jogar fora até o final do 1º tempo pela equipa durante o campeonato
| `diferenca_golos` | Diferença entre os golos marcados e os golos sofridos fora até ao final do 1º tempo pela equipa durante o campeonato
| `pontos` | Pontuação final (apenas contabilizando os jogos fora até o intervalo) da equipa no campeonato

Explicações em `defesas_guarda_redes.csv`

| Nome da coluna        | Significado
| ------------- |:-------------:|
| `nome_guarda_redes` | Nome do respetivo guarda-redes
| `clube` | Clube que o guarda-redes representa
| `numero_defesas` | Número total de defesas que o guarda-redes fez ao longo da época 

Explicações em `jogos.csv`

| Nome da coluna        | Significado
| ------------- |:-------------:|
| `divisão` | Divisão da liga 
| `data` | Data em que o jogo se realizou
| `horario` | Horário em que o jogo se realizou
| `equipa_da_casa` | Equipa que jogou em casa no respetivo jogo
| `equipa_de_fora` | quipa que jogou fora no respetivo jogo
| `golos_equipa_da_casa_final` | Número de golos marcados pela equipa da casa durante a totalidade do jogo
| `golos_equipa_de_fora_final` | Número de golos marcados pela equipa a jogar fora durante a totalidade do jogo
| `resultado_final` | Resultado final do jogo
| `golos_equipa_da_casa_intervalo` | Número de golos marcados pela equipa da casa até o intervalo do jogo
| `golos_equipa_de_fora_intervalo` | Número de golos marcados pela equipa de fora até o intervalo do jogo
| `resultado_intervalo` | Resultado do jogo ao intervalo
| `remates_equipa_casa` | Remates efetuados pela equipa da casa durante a totalidade do jogo
| `remates_equipa_fora` | Remates efetuados pela equipa de fora durante a totalidade do jogo
| `remates_baliza_equipa_casa` | Remates à baliza efetuados pela equipa da casa durante a totalidade do jogo
| `remates_baliza_equipa_fora` | Remates à baliza efetuados pela equipa de fora durante a totalidade do jogo
| `faltas_casa` | Faltas cometidas pela equipa da casa durante a totalidade do jogo
| `faltas_fora` | Faltas cometidas pela equipa de fora durante a totalidade do jogo

Explicações em `defesas_guarda_redes.csv`

| Nome da coluna        | Significado
| ------------- |:-------------:|
| `nome_jogador` | Nome do respetivo jogador
| `clube` | Clube que o jogador representa
| `numero_golos` | Número total de golos que o jogador marcou ao longo da época












