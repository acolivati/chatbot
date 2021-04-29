# CURADORIA Chatbot
## Briefing
Nosso cliente atua com e-commerce e quer implementar um bot de
atendimento para seus clientes, tanto via Whatsapp como via webchat em seu
site.
A inteligência artificial estará presente neste projeto para que a experiência
possa ser mais completa para os usuários, trazendo respostas específicas e
mais assertivas
Classificação de linguagem natural
Como parte do desenvolvimento, um dos processos que aplicamos em NLU
chama-se classificação de linguagem natural, que é dividido em 4 etapas:
1 - Selecionar frases de perguntas frequentes
2 - Classificá-las em grupos
3 - Criar intenções e entidades*
4 - Cadastrar frases de treinamento para as intenções
* entidades são opcionais
Para iniciarmos essa classificação, nosso cliente extrai e nos envia uma massa
de dados com as frases que seus usuários costumam falar na central de
atendimento. Esse material passa pela nossa equipe de ciência de dados que,
após rodar um algoritmo, nos entrega uma planilha conhecida como Clusters.
Sua tarefa será:
Acessar a planilha, analisar as mensagens com base nos agrupamentos
pré-organizados pelo algoritmo e, numa nova aba, separar as mais relevantes
(para este exercício selecione entre 6 a 10 mensagens por assunto) por
assunto. Essas mensagens selecionadas serão as frases de treinamento do
nosso chatbot.
Lembre-se que cada assunto deverá ser associado a uma intenção, que você
vai criar, no formato #verbo_substantivo. Exemplo: #alterar_cadastro
Se achar válido, crie entidades também, no formato
@substantivo_substantivo. Exemplo: @tipo_dados
