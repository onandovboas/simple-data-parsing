# 🧹 Pipeline de Higienização de Leads

## 📌 O Problema de Negócio
A escola usada no programa realiza campanhas de captação de novos alunos, mas os dados dos leads (exportados em JSON) chegam de forma desestruturada, com inconsistências de digitação e campos omissos. Isso geraria horas de retrabalho para a secretaria, caso fosse utilizar um excel, inviabilizando a ligação direta com um banco de dados e ferramentas de BI.

## 💡 A Solução
Desenvolvimento de um pipeline de dados em Python puro (sem uso de bibliotecas externas) para higienização e exportação de uma base estruturada e limpa em formato `.csv`, pronta para análise. O conjunto de dados utilizados é apenas um exemplo, para não expor dados pessoais.

## 🛠️ Ferramentas Utilizadas
* Python (Manipulação nativa de Strings, Loops, Funções e Dicionários)
* Bibliotecas: `json`, `csv`

## ⚙️ Funcionalidades do Script
* Padronização de nomes (Capitalização correta).
* Higienização e validação estrutural de e-mails.
* Tratamento de erros para dados omissos (Idades não preenchidas).

