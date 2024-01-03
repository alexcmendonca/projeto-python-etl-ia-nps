# ETL | Python com Inteligência Artificial (IA) e NPS

Explorando Python e Inteligência Artificial (IA) neste projeto, com objetivo de analisar a satisfação de clientes em relação às experiências educacionais. Para isso, foi utilizado o cálculo do Net Promoter Score (NPS) e a aplicação de IA para analisar sentimentos dos comentários. 

## 🖥️ Funcionalidades
Inicialmente no projeto foi abordado os paradigmas de programação, com os seguintes estilos:

- Programação Imperativa - Falamos para o Python o passo-a-passo do que deve ser feito, ou seja, nós damos um comando e esperamos um resultado;
- Programação Funcional - Delegamos para o Python a execução de alguns blocos de códigos, buscamos manipular os dados, quebrando um problema em muitas e pequenas funções;
- Programação Orientada a Objetos - Que nos proporciona a capacidade de reutilizar código de maneira eficiente. Ao criar uma definição de objeto, podemos aplicá-la repetidamente em diferentes contextos, adaptando-a conforme necessário. Essa abordagem permite evitar a redundância de redefinir conceitos semelhantes várias vezes.

NPS - O Net Promoter Score é uma métrica de lealdade do cliente criada por Fred Heichheld em 2003
<img src="/assets/img/img-nps.png">

###### Imagem 1: Escala e Fórmula de NPS

ETL (Extração, Transformação e Carregamento) com Python, foi utilizado bibliotecas essenciais para a manipulação de dados, como Pandas para operações de limpeza e transformação dos dados e matplotlib para a visualização dos dados.
<img src="/assets/img/matplotlib-img.png">

###### Imagem 2: Gráfico com matplotlib

## 🔧 API OpenAI
<img src="/assets/img/openia-img.png">

Utilização da API da OpenAI para análise de sentimentos, com base nas informações da base de dados do projeto.

## 💡Análise de Dados - Insights

Resposta da I.A:
'A análise dos comentários indica que a percepção geral deste bootcamp é predominantemente positiva, com a maioria das respostas apresentando alta pontuação (notas entre 6 a 10), elogiando a qualidade e eficácia do programa. Sua importância para a educação aberta também foi ressaltada. Por outro lado, alguns feedbacks sugerem que há espaço para melhoria. De particular, os participantes gostariam de ver inclusos tópicos como Inteligência Artificial e linguagem de programação Python. Além disso, um feedback foi extremamente negativo (nota 0), mas não detalhou as razões específicas dessa insatisfação, tornando difícil identificar as áreas de melhoria diretamente desse comentário. No geral, embora haja espaço para melhorar algumas áreas, o bootcamp é altamente valorizado pelos seus participantes.'