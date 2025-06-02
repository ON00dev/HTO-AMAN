# HTO-AMAN
Repositório dedicado para apresentar o projeto de **Registro de Hóspedes** do **Hotel de trânsito de Oficiais** da AMAN.
-----------------------------------------------------------------------------------------------------------------------
Para reservar um quarto, o hóspede deve preencher uma ficha onde é solicitado diversas informações pessoais e militares.
Para isso, ao acessar https://hto-aman-recep.up.railway.app/form , o hóspede poderá fazer sua ficha a qualquer momento e lugar, facilitando a experiência do mesmo.
### Veja um Exemplo:
[![Assistir ao video](https://github.com/ON00dev/HTO-AMAN/blob/main/exemplos/miniatura-form.PNG)](https://github.com/ON00dev/HTO-AMAN/blob/main/exemplos/criando%20ficha.mp4) *clique para assisir*

------------------------------------------------------------------------------------------------------------------------

O usuáio preenche o furmulário e envia para fazer a reserva. No painel da Recepção, o militar recepcionista poderá executar 4 ações importantes:
- Carregar fichas;
- Salvar identidade selecionada;
- Excluir;
- Criar Planilha.


  ### Veja um Exemplo:
  [![Assistir ao video](https://github.com/ON00dev/HTO-AMAN/blob/main/exemplos/miniatura-recep.PNG)](https://github.com/ON00dev/HTO-AMAN/blob/main/exemplos/painel%20recepcao.mp4) *clique para assistir*

  ## O que faz cada Ação?

 PAINEL RECEPÇAO - HTO/AMAN
|---------------------------------------------|
| **Carregar Fichas:** carrega fichas existentes  |
| **Salvar identidade selecionada:** Salva localmente a identidade anexada pelo hóspede|
| **Excluir:** Deleta a ficha da lista|
| **Criar Planilha:** Cria um planilha pré-preenchida com os dados do hóspede|

-------------------------------------------------------------------------------------------------------------------------------

Caso tente acessar ao painel da Recepção, será retornado a você 'Acesso negado: IP nao autorizado'. Isso porque, a rota é somente acessada por endereços IPs permitidos, sendo eles especificados no código do projeto. Faça um teste aí, https://hto-aman-recep.up.railway.app/ .

## Modelo de Planilha Seguido:
[![planilha modelo](https://github.com/ON00dev/HTO-AMAN/blob/main/exemplos/planilhar.PNG)]

------------------------------------------------------------------------------------------------------------------------------

Logo após o preenchimento na planilha e salvamento local, a mesma pode ser imprimida e usada conforme a necessidade da recepção.
