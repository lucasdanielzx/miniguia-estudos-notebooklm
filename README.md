# NotebookLM Recommendation Systems

🎯 Contexto e Objetivos
Contexto: Os algoritmos de recomendação são a força motriz por trás das maiores plataformas digitais do mundo, moldando o consumo de conteúdo, e-commerce e redes sociais. Este caderno temático utiliza o NotebookLM para explorar o funcionamento matemático, os desafios éticos (como as bolhas de filtro) e as arquiteturas de engenharia por trás desses sistemas.
Objetivos de Estudo:
- Compreender as diferenças fundamentais entre Filtragem Colaborativa e Filtragem Baseada em Conteúdo.
- Analisar o problema de Cold Start (Início Frio) e como os sistemas modernos o contornam.
- Avaliar o impacto dos algoritmos na retenção de usuários e a ética na recomendação.

📚 Curadoria de Fontes
1 - "Item-Based Collaborative Filtering Recommendation Algorithms" (O famoso artigo da Amazon que revolucionou o e-commerce).
2 - IBM: https://www.ibm.com/br-pt/think/topics/recommendation-engine
3 - Geekhunter: https://blog.geekhunter.com.br/algoritmos-de-recomendacao-o-que-sao-e-como-implementa-los/

🚀 Miniguia de Estudo: Glossário Técnico
- Filtragem Colaborativa (Collaborative Filtering): Método que faz recomendações com base no comportamento de usuários parecidos. Se o Usuário A e B gostam dos mesmos filmes, e o Usuário A gostou de um filme novo, o sistema recomenda esse filme para o Usuário B.
- Filtragem Baseada em Conteúdo (Content-Based): Recomenda itens parecidos com os que o usuário já gostou no passado, analisando as características do próprio item (ex: gênero do filme, diretor, palavras-chave).
- Cold Start (Início Frio): A dificuldade que o algoritmo enfrenta para recomendar algo para um usuário novo (sem histórico) ou quando um item novo é adicionado ao catálogo (sem interações).
- Matriz de Fatoração (Matrix Factorization): Técnica matemática (como SVD) usada para decompor grandes matrizes de interações usuário-item e descobrir padrões ocultos de preferência.

🛠️ Prompts Reutilizáveis para colocar no NotebookLM
1. "Aja como um Engenheiro de Machine Learning sênior. Com base nos textos fornecidos, explique de forma didática, usando uma analogia simples, como funciona o algoritmo de Fatoração de Matrizes para alguém que não entende de matemática."

2. "Quais são os principais dilemas éticos apontados nas fontes em relação ao viés de recomendação e ao vício em plataformas? Resuma em 3 pontos críticos."
