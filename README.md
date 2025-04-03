# Análise de Sentimentos com Azure AI Language Studio

Este projeto demonstra como utilizar o Azure AI Language Studio para análise de sentimentos em textos.

## 📋 Pré-requisitos
- Conta no Azure
- Recurso de Language Service criado

## 🚀 Como executar
1. Acesse o [Language Studio](https://language.cognitive.azure.com/)
2. Selecione "Análise de Sentimento"
3. Insira o texto para análise
4. Visualize os resultados

## 📊 Resultados Exemplo
- Análise 1 - sentença positiva:
![image](https://github.com/user-attachments/assets/a7569acc-b023-4d72-a7c5-c46181455c61)
![image](https://github.com/user-attachments/assets/13b679d2-3980-4a2d-96dc-d1cd535f5e0f)
![image](https://github.com/user-attachments/assets/fabe93e5-276c-4323-be96-ebfee70c0a82)
![image](https://github.com/user-attachments/assets/20422232-c553-4939-a668-4057dde5d69b)
![image](https://github.com/user-attachments/assets/5155fe4f-a12f-42ab-bbd6-043ae5b6e205)
- Análise 2 - sentença negativa:
![image](https://github.com/user-attachments/assets/e68ac5d5-c85b-47f6-a51d-1b111af3d6d6)
![image](https://github.com/user-attachments/assets/375b6d01-8539-4bc1-83bf-77538aefdc4f)
![image](https://github.com/user-attachments/assets/8b0b362d-6308-4688-a279-dbbd87e12783)
![image](https://github.com/user-attachments/assets/7efbb78a-fe35-4527-b566-549c3f572cc6)
![image](https://github.com/user-attachments/assets/70546a7d-f890-440b-8f39-fc0fc4c4750e)

**Frases analisadas:**
- "Noite Inesquecível!
O restaurante superou todas as expectativas! A massa fresca do fettuccine alfredo derretia na boca, perfeitamente al dente. O chef veio à nossa mesa para explicar a origem dos ingredientes importados diretamente da Toscana. O tiramisu era divino - o equilíbrio entre café e mascarpone estava impecável. O som ambiente de ópera italiana e a decoração rústica criaram uma atmosfera autêntica. O serviço foi impecável; o garçom Luca fez recomendações perfeitas de vinhos. Voltaremos com certeza para experimentar o menu degustação!" → Positivo (0.93)
- "Frustração Total, não Recomendo!
Pior experiência gastronômica dos últimos anos, a "carbonara autêntica" vinha com creme de leite, uma heresia na culinária italiana, e o bacon estava queimado. Esperamos 50 minutos pelos pratos principais e quando reclamamos, o gerente foi grosseiro. O vinho estava oxidado e mesmo assim tentaram nos cobrar. O banheiro estava sujo e sem papel. Para completar, encontraram um fio de cabelo no meu risoto! Cobraram 10% de serviço obrigatório por um atendimento que foi péssimo em todos os aspectos. Nunca mais pisarei nesse lugar e alerto todos os amantes da verdadeira cozinha italiana a evitá-lo." → Negativo (1.0)

## 💡 Insights
- O serviço consegue identificar nuances mesmo em frases sem palavras óbvias
- O score é maior quando o sentimento é mais extremo
- Frases neutras podem ser desafiadoras para o modelo

## 📚 Aprendizados
- Como configurar serviços de IA na Azure.
- A importância do processamento de linguagem natural.
- Aplicações práticas de análise de sentimentos.
