# CONECTA CONCURSOS
CONECTA CONCURSOS é:  "É uma ferramenta simples e direta para quem busca concursos públicos. Basta informar sigla do estado de origem
e eu te mostro os concursos disponíveis dentro daquele estado, com informações como nível, datas importantes e o link direto para a banca organizadora."  
Ponto chave: Simplicidade e foco na informação essencial por estado e banca. 😉


Como funciona o CONECTA CONCURSOS:

Armazenamento de Dados: O sistema funciona como um catálogo digital de concursos. As informações sobre cada concurso são guardadas de forma estruturada, 
como em uma tabela. Para cada concurso, armazenamos os seguintes detalhes:

Nome do Concurso: O título oficial do concurso (ex: Concurso Polícia Federal).
Estado: A unidade federativa onde o concurso está sendo realizado (ex: RJ para Rio de Janeiro, SP para São Paulo). Essa informação é crucial para a busca.
Nível: O grau de escolaridade exigido (ex: Médio, Superior).
Data do Concurso: A data prevista para a realização das provas ou etapas principais.
Início das Inscrições: A data em que os candidatos podem começar a se inscrever.
Banca Responsável: A instituição ou empresa organizadora do concurso (ex: Fundação Cesgranrio, Cebraspe, Vunesp).
Link da Banca Responsável: Um endereço de internet (link) que leva diretamente ao site oficial da banca organizadora, onde os candidatos podem encontrar
o edital completo e outras informações.
Valor da Inscrição: O custo para se inscrever no concurso.
Quantidade de Vagas: O número de vagas disponíveis para os cargos.
Adição de Concursos: Para alimentar o sistema com informações, existe uma função chamada "adicionar_concurso". Essa função permite inserir os dados de um 
novo concurso, preenchendo todos os detalhes que mencionei acima. Cada novo concurso adicionado é armazenado em uma lista dentro do sistema.

Busca por Estado: A principal funcionalidade do CONECTA CONCURSOS é a busca por estado. O usuário (no caso, vocês ou os alunos que utilizarem a ferramenta) 
informa o estado de interesse (por exemplo, digitando "RJ" para Rio de Janeiro).

Processamento da Busca: O sistema pega o estado digitado e compara com o estado de cada concurso armazenado. Ele não se importa se o estado foi digitado em 
letras maiúsculas ou minúsculas, pois converte tudo para maiúsculo para garantir que a busca funcione corretamente.

Exibição dos Resultados: Se forem encontrados concursos para o estado especificado, o sistema exibe uma lista com as seguintes informações de cada concurso:

O nome do concurso.
O nível de escolaridade exigido.
A quantidade de vagas disponíveis.
O valor da inscrição.
A data do concurso (formatada em dia-mês-ano).
A data de início das inscrições (também formatada em dia-mês-ano).
Um link direto para o site da banca responsável (se o link estiver disponível). Caso contrário, informa que o link não está disponível.
Mensagem de Não Encontrado: Se nenhum concurso for encontrado para o estado pesquisado, o sistema informa ao usuário que não há concursos disponíveis para 
aquele estado no momento.

Em resumo, o CONECTA CONCURSOS é como um catálogo de concursos online que permite aos usuários encontrar oportunidades de forma rápida e filtrada por estado, 
fornecendo informações essenciais e um link direto para a fonte oficial (a banca organizadora).


