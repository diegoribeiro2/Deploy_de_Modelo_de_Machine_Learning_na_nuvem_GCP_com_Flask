Introduçâo:

Neste case abordei o deploy de modelos de machine learning na nuvem utilizando a plataforma Google Cloud Platform (GCP). 
Foi utilizado o modelo de regressâo, para estimar o valor de umseguro (plano de saúde).
O objetivo é demonstrar como servir um modelo treinado localmente para que outros usuários, os stakeholders, possam acessar suas funcionalidades remotamente através de APIs.

Utilizando Flask:

O modelo foi empacotado e disponibilizado na nuvem GCP (Google Cloud Platform) para que qualquer pessoa possa requisitar predições em tempo real.
O Flask é um microframework web Python muito utilizado para construção de aplicações web devido a sua facilidade, flexibilidade e praticidade.
Ele permite criar APIs REST de forma rápida, integrando facilmente com bibliotecas Python como Pandas, NumPy e Scikit-Learn para manipulação de dados e machine learning.

Consideração Final:

Neste case vimos como realizar o deploy de modelos de machine learning treinados localmente na nuvem GCP, utilizando Flask para disponibilizar uma API que retorna predições em tempo real.
O processo é bastante simples e abstrato, permitindo focarmos na lógica das aplicações sem nos preocuparmos com toda a complexa infraestrutura de nuvem por trás.
