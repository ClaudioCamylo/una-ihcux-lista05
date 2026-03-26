Resumo das heurísticas aplicadas:
1. Visibilidade do Status do Sistema (Heurística #1)
O código mantém o usuário informado sobre o que está acontecendo "nos bastidores".
Aplicação: As mensagens [SISTEMA]: Conectando... e a animação dos pontos (...) dão feedback imediato de que o programa não travou e está processando os dados.

2. Correspondência entre o Sistema e o Mundo Real (Heurística #2)
O sistema utiliza uma linguagem e lógica que fazem sentido para o contexto financeiro do usuário.
Aplicação: Uso de termos familiares como "Cotação", "Dólar" e "Reais", além de exibir o resultado final com o símbolo monetário padrão ($).

3. Prevenção de Erros (Heurística #5)
O design tenta evitar que o usuário cometa deslizes antes mesmo que eles aconteçam.
Aplicação: A instrução clara no Console.Write indicando o formato esperado — (ex: 5,20) — ajuda o usuário a não digitar o separador decimal incorreto.

4. Reconhecimento em vez de Memorização (Heurística #6)
As instruções e o contexto estão sempre visíveis, reduzindo a carga cognitiva.
Aplicação: O cabeçalho fixo e as perguntas diretas eliminam a necessidade de o usuário lembrar o que deve fazer ou qual é o objetivo do programa.

5. Estética e Design Minimalista (Heurística #8)
O console evita poluição visual e foca no que é importante.
Aplicação: O uso de Console.Clear(), linhas divisórias (====) e cores contrastantes (Amarelo para títulos, Verde para resultados, Vermelho para erros) organiza a hierarquia visual da informação. 

6. Ajuda aos usuários a reconhecerem, diagnosticarem e recuperarem-se de erros (Heurística #9)
Quando algo dá errado, o sistema não "crasha" silenciosamente; ele explica o problema.
Aplicação: O bloco catch captura a exceção e exibe uma mensagem em português claro, indicando exatamente por que o erro ocorreu ("Entrada inválida! Use apenas números...") em vez de mostrar um código técnico indecifrável. 
