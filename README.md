# Desafio IFood
![image](https://github.com/user-attachments/assets/50cbc4da-ceb5-4202-bed0-94034f6edcd3)

## 📌 Visão Geral
Esse projeto visa fazer a análise exploratória dos dados da empresa Ifood, para identificarmos o perfil e os gastos dos clientes com a plataforma.

Desafio proposto no curso da professora Renata Biaggi, EBA - Estatística do Básico ao Avançado no módulo de Estatística Descritiva.

## 💼 Entendimento do Negócio
Enteder o perfil do consumidor e como ele gasta seu dinheiro na plataforma da empresa, é um ponto crucial, para melhorar a experiência do usuário e
para técnicas de marketing melhor otimizadas.

**Tipos de Análise Realizados:**
- Análise Exploratória dos Dados
- Análise Descritiva: Correlacão entre estado civil e o número de filhos
- Análise Descritiva: Correlação entre quanto maior o salário maior o gasto

## 🛠 Pré-processamento
_Considerações Importantes:_
1. Os dados vão ser mantidos anônimos por boa prática a respeito da proteção dos dados

_Etapas do Pré-Processamento de Dados:_
1. Importação das libs necessárias
2. Carregamento e leitura do CSV
3. Tratar dados nulos e duplicados
4. Análise Descritiva
5. Correlação dos dados

## 📈 Insights e Conclusões
Um dos objetivos da análise era identificar o perfil dos clientes, cujo se mostrou bem interessante, a maioria deles tem alto nível de escolaridade sendo grande parte deles graduados,
outro fator que pudemos ver foi a relação entre a quantidade de filhos e o gasto na plataforma, pela análise pudemos ver que os clientes sem filhos são os que mais gastam na plataforma,
e os clientes com 2 ou mais filhos gastam muito pouco. Também conseguimos observar a relação entre o salário e o gasto dos cliente que quanto mais ganham mais tendem a gastar.

Conclusão: Para o ifood manter os clientes que gastam mais, eles devem oferecer algum tipo de benefício, como cupons exclusivos de alto desconto, ou até cupons que possam dar desconto cumulativos,
quanto mais produtos a serem comprados maior o desconto mesmo se o produto for do mesmo estabelecimento.  
Agora para converter os clientes que gastam pouco, podemos trabalhar com algumas opções, dado que grande parte dos que gastam menos são pais de 2 ou mais filhos, podemos focar em outras áreas que o Ifood oferece
como por exemplo, mercado ou farmácia, oferecer alto desconto para que esses pais não precisem se deslocar no dia a dia, vai ajudar a gastarem mais na plataforma e até converter clientes que não usem a mesma, outro
caminho que podemos seguir seria oferecer descontos em franquias de fast food, tanto crianças quanto adolescentes tendem a ter interesse por lanches, porém o preço elevado dos mesmos fazem famílias com mais filhos
acabarem evitando os gastos, um maior desconto nessas franquias direcionado para esses clientes pode ajudar a fazer com que eles acabem gastando mais.

## 📜 Estrutura do Projeto
```
├── notebooks  
├── .gitignore  
├── .python-version  
├── README.md  
├── poetry.lock  
├── pyproject.toml
```
