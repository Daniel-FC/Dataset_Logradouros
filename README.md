_Status: em Desenvolvimento_

### ✔️ Proposta e objetivo:

Esse Dataset possui dados de todos os logradouros de Natal. A ideia é que esse banco de informações sirva de auxílio para aplicativos que sofrem influência do fluxo de trânsito na geração do percurso e necessitam de dados históricos sobre as ruas. Como:

- Horários aos quais evitar (trânsito lento);
- Bairro a qual pertence, e bairros conectados;
- E índice de prioridade (notabilidade).

Esse banco de informações foi desenvolvido filtrando informações dos logradouros a partir do site dos correios. O conhecimento dos horários a serem evitados foram gerados a partir do cruzamento de dados dos site da prefeitura de Natalncom o aplicativo “Google Maps”. Trabalhar por logradouro (cep) e não por “rua” é de suma importância para essa categorização, pois, existem avenidas que ficam lentas apenas em determinados trechos.

Ruas muito compridas por exemplo, podem pertencer a vários bairros e também podem possuir diversos CEP’s a depender de várias características: pode ser dividida por númeração; pode ser dividida também pelo lado da rua; pontos de referências podem possuir CEP’s únicos; assim como a combinação dos dois primeiros métodos. Dessa forma a sedimentação de uma rua pode ajudar na precisão das informações do banco de informações.

Além disso, o índice de prioridade leva em consideração quais ruas possuem mais recursos para o trânsito, na seguinte ordem de sobrepujança: rodovias; avenidas; ruas; alamedas; travessas; e outros.

### 🚧 Futuras Atualizações:

- Informações sobre a pavimentação da rua: "asfaltada", "paralelepípedo", "areia"...
- Adicionar a cidade próximas: Parnamirim, São Gonçalo do Amarante, Macaíba e Extremoz.
