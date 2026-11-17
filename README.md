# DSM5-MDDO
---
DSM5-MDDO é uma ontologia de domínio sobre o Transtorno Depressivo Maior (TDM), 
construída a partir dos critérios do DSM-5. 
Ela está organizada em visões complementares: Pessoa (fases de vida, papéis, traço de 
neuroticismo e eventos estressantes); Sintomas (os nove critérios do DSM-5, divididos em 
cardeais e secundários); Condição de saúde e Comorbidade (transtornos mentais e 
condições clínicas associadas ao TDM); e Diagnósticos (episódio depressivo maior, curso, 
remissão, gravidade e especificadores). 
---
### Pessoa 
É o centro do modelo. Pessoa é um kind com duas formas de variação: as fases de vida 
(criança, adolescente, adultos e idoso, que mudam com o tempo) e os papéis (paciente, 
profissional de saúde e parente, que dependem do contexto). A pessoa também recebe o 
traço de neuroticismo, que o DSM-5 associa à predisposição, e participa de eventos: 
experiências adversas na infância e eventos estressantes de vida. É aqui que estão os 
fatores de risco individuais e ambientais. 
### Sintoma 
Sintoma é um mode, porque só existe como característica de uma pessoa. Está dividido 
em sintoma Primário (humor deprimido e perda de interesse ou prazer) e sintoma 
secundário (os outros sete critérios do DSM-5). Cada um dos nove é um subkind. A 
estrutura permite saber quais sintomas existem, quais são obrigatórios e quantos entram 
na regra dos cinco. 
### Condição de Saúde e Comorbidade 
Condição de saúde é um mode da pessoa, com dois ramos: transtorno mental 
(ansiedade, uso de substâncias, personalidade borderline e o próprio TDM) e condição 
clínica (diabetes e doença cardiovascular). Uma condição é comorbidade só em relação 
ao TDM na mesma pessoa, por isso Comorbidade é um role, ligado ao TDM por um relator 
(Coocorrência clínica) e pela relação “é comorbidade de”. 
### Diagnóstico 
É a visão dos critérios. O Episódio depressivo maior é um event em que a pessoa participa 
e que manifesta o TDM e os sintomas (de 1 a 2 cardeais e até 7 secundários). Gravidade, 
características psicóticas e especificadores são atributos do episódio, tipados por 
enumerações. O TDM tem fases: curso (episódio único ou recorrente) e status clínico (em 
episódio, remissão parcial ou completa). 

---
Pessoa é o fio condutor. Uma pessoa pode ter sintomas e condições de saúde (modes), 
participar de eventos de risco e de um episódio. O episódio reúne os sintomas e se 
manifesta no TDM. Assim, dá para responder se um conjunto de sintomas atinge o critério 
do DSM-5 e quais comorbidades e fatores acompanham os episódios. 
