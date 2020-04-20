# Requisitos de Software

Antigamente dizia-se que requisitos eram sinônimos de funções, ou seja, tudo que o software deveria fazer funcionalmente. No entanto, atualmente assumiu-se que requisitos de software é muito mais do que apenas funções. Requisitos são, além de funções, objetivos, propriedades, restrições que o sistema deve possuir para satisfazer contratos, padrões ou especificações de acordo com o(s) usuário(s). De forma mais geral um requisito é uma condição necessária para satisfazer um objetivo.

Portanto, um requisito é um aspecto que o sistema proposto deve fazer ou uma restrição no desenvolvimento do sistema. Vale ressaltar que em ambos os casos devemos sempre contribuir para resolver os problemas do cliente e não o que o programador ou um arquiteto deseja. Dessa forma, o conjunto dos requisitos como um todo representa um acordo negociado entre todas as partes interessadas no sistema. Isso também não significa que o programador, arquiteto ou um analista bem entendido no assunto de tecnologia não possam contribuir com sugestões e propostas que levem em conta o desejo do cliente.

Além disso, ainda temos um documento de requisitos que é uma coleção dos requisitos.

Por fim, os requisitos possuem alguns objetivos centrais como estabelecer e manter uma concordância com os clientes e outros envolvidos sobre o que o sistema deve fazer, deve oferecer aos desenvolvedores, projetistas e testadores do sistema uma compreensão melhor dos requisitos do sistema, definir fronteiras do sistema definindo o que deve ser incluído e o que não deve fazer parte do sistema, fornecer uma base para estimar o custo e o tempo de desenvolvimento do sistema e por fim definir uma interface de usuário para o sistema.

Classificação dos Requisitos
Existem dois tipos de classificação de requisitos, são eles: Requisitos Funcionais (RF) e Requisitos Não-Funcionais (RNF).

Os requisitos funcionais referem-se sobre o que o sistema deve fazer, ou seja, suas funções e informações. Os requisitos não funcionais referem-se aos critérios que qualificam os requisitos funcionais. Esses critérios podem ser de qualidade para o software, ou seja, os requisitos de performance, usabilidade, confiabilidade, robustez, etc. Ou então, os critérios podem ser quanto a qualidade para o processo de software, ou seja, requisitos de entrega, implementação, etc.

Evidentemente que as prioridades podem variar conforme a natureza do software. Isso quer dizer que um software para uma plataforma de celular terá diferentes requisitos de um software que roda num browser na web. Assim como um software de tempo real que precisa ser executado em 1 segundo é diferente de outro software que pode ter um tempo maior para execução de uma determinada tarefa.

Portanto, requisitos funcionais preocupam-se com a funcionalidade e os serviços do sistema, ou seja, as funções que o sistema deve fornecer para o cliente e como o sistema se comportará em determinadas situações. Segue abaixo alguns exemplos de requisitos funcionais:

[RF001] O Sistema deve cadastrar médicos profissionais (entrada)
[RF002] O Sistema deve emitir um relatório de clientes (saída)
[RF003] O Sistema deve passar um cliente da situação "em consulta" para "consultado" quando o cliente terminar de ser atendido (mudança de estado)
[RF004] O cliente pode consultar seus dados no sistema
Por fim, os requisitos não funcionais definem propriedades e restrições do sistema como tempo, espaço, linguagens de programação, versões do compilador, SGBD, Sistema Operacional, método de desenvolvimento, etc. Uma dica importante é que os requisitos não funcionais são geralmente mensuráveis e assim devemos preferencialmente associar uma medida ou referência para cada requisito não funcional.
