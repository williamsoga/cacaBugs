#solicitação do cliente
1. ## pagina inicial- visualizar o botão (funcionado)
    
    **verificação:** solicitação do usuario

    **Descrição:** [botão de ver produtos aparece na home ]
    
    **Localização:** [na pagina index do site ]
    
2. ## pagina inicial-direcionamento do botão ver produtos (funcionando)

     **verificação:** solicitação do usuario
    **Descrição:** [o botão leva para pagina do produto]
    
    
     3. ## nome dos produtos (funcionando)
    **verificação:** solicitação do usuario
     **Descrição:** [os nomes aparecem corretamente no site ]

    4. ## imagem dos produtos 
    **Tipo de Bug:** [Interface]
     **Descrição:** [as imagens esão fora de proporção , e falta uma imagem ]
     **localização** [ nos cards dos produtos]
      **Severidade:** [Média] 
     **Reprodução:** [após de clicar no botão ver os produtos , a pagina é direcionado a lista de produtos]

    5. ## Descrição do produto (funcionado)
        **verificação:** solicitação do usuario
          **Descrição:** [as descrições estão funcionado ]

     6. ## preço do produto (funcionado)
         **verificação:** solicitação do usuario
          **Descrição:** [os preços estão funcionado ]
    
    7. ## botão carrinho (funcionado)
       **verificação:** solicitação do usuario
       **descrição** [ao clicar no botão do carrinho o produto vai pro carrinho normalmente e é atualizado. porem o footer está bloqueando a visibilidade do botão do carrinho no 
       produto fone de ouvido. Além disso não aparece a mensagem de produto inserido no ]
      **Severidade:** [Média] 
      **localização** [ no card do produto: fone de ouvido]
       **Reprodução:** [após de clicar no botão ver os produtos , a pagina é direcionado a lista de produtos . e direcionar a pagina para baixo]

 7. ## botão carrinho -fone de ouvido
       **Tipo de Bug:** [Interface/usabilidade/validação]
         **descrição** [  o footer está bloqueando a visibilidade do botão do carrinho no 
       produto fone de ouvido. e ao clicar no botão   não aparece a mensagem de produto inserido na aba carrinho mas ele é atualizado]
        **Severidade:** [alta] 
      **localização** [ no card do produto: fone de ouvido]
       **Reprodução:** [após de clicar no botão ver os produtos , a pagina é direcionado a lista de produtos . e direcionar a pagina para baixo
       clique no botão ]  


   
    9. ## Campo de busca de produto 
      **Tipo de Bug:** [Interface/funcionalidade/validação]
      **descrição** [ não foi inserido o  campo de busca do produto]
       **Severidade:** [alta] 
       **localização** [pagina de produtos]
       **Reprodução**  [após de clicar no botão ver os produtos , a pagina é direcionado a lista de produtos ]

    10. ## carrinho -preços
     **verificação:** solicitação do usuario
     **descrição**: [ os nomes e os preços aparecem na pagina, alem da soma total dos preços]
    11. ## compra dos produtos
     **verificação:** solicitação do usuario
      **descrição**: [ após clicar finalizar as compras é mostrado uma mensagem de agradecimento e o contador do carrinho é zerado ]

    12. ## atualização da pagina de compra
    **tipo de bug**: [interface/usabilidade/validação]
    **descrição** :[ após a compra  o produto que ja foi comprado não desaparece ]
    **severidade**:[alta]
    **localização**: [pagina do carrinho]
    **Reprodução**[ após colocar os produtos no carrinho e apertar em finalizar a compra]

    13. ## campo de mensagem 
    **verificação:** solicitação do usuario
     **descrição**: [ campo de mensagem possui os itens colocados pelo usuario]
     
     14. ## envio da mensagem 
    **verificação:** solicitação do usuario
     **descrição**: [ após colocar email valido a mensagem foi enviado]

     
    ##  Verifucação aprofundada

    1. ## botão home 
    **tipo de bug**: [usabilidade]
    **descrição**:[após entrar nas paginaa : produtos , contato e carrinho não é possivel voltar para pagina inicial , e é emetido uma mensagem de pagina
    em manutenção]
    **severidade**[media]
    **localização**[header das paginas:produtos ,contato e carrinho  ]
    **reprodução**[na pagina de produtos ,contato e carrinho clique na aba Home]

    2. ##  pagina inicial 
    **tipo de bug**:[usabilidade]
    **descrição**:[ ao clicar no botão home em alguma pagina não direcionado é preciso fazer uma atualização da pagina para poder acessar ela] 
    **severidade**:[alta]
    **localização**[header das paginas:produtos ,contato e carrinho  ]
   **reprodução**[na pagina de produtos ,contato e carrinho clique na aba Home e aperta F15]


    4. ## versão para mobile
    **tipo de bug**:[usabilidade]
    **descrição**: [ao tentar redimensionar para um tamanho de um smartphone , o site não fica adequado para o dipositivo]
    **severidade**: [baixa]
    **localização**: [todas as paginas]
    **reprodução**:[aperta F12,acessa devtools, ao passar o mouse no painel devtools.
    aparecerá uma seta dupla , clique  e arrasta pros lados]

    5. ## pagina de produto 
    **tipo de bug**:[interface]
    **descrição**:[pagina de produto está totalmente desalinhada e sem organização ]
    **severidade**: [baixa]
    **localização** : [pagina de produto]
    **reprodução**[acessar a aba de produto]
    
    6. ## Organização do css
    **sugestão de organização**:[criar um arquivo css separado do html]

    *Adicione mais bugs conforme necessário*

### Resumo e Estatísticas

**Total de bugs encontrados:** [13]

**Distribuição por tipo:**

- Interface: [4]
- Funcionais: [1]
- Validação: [3]
- Usabilidade: [5]
- Outros: [Número]

### Classificação por Severidade

- Alta: [4] bugs
- Média: [2] bugs
- Baixa: [2] bugs

### Reflexão da Equipe

**Desafios encontrados:** [houve poucos desafios, pois a maioria dos bugs ja estava visiveis , alguns teve que testar o menu  que na primeira vez  ja foi encontrado ]

**Estratégias utilizadas:** [primeiramente foi seguir o que o usuario solicitou , após disso foi icrmentado com alguns testes a mais]

**Aprendizados:** [foi aprendido que a identificar diferetes tipos  problemas  , e testar o software]

### Sugestões de Melhorias

[a pagina inicial tem que ser identificado ao clicar , enquanto está  nas paginas de produto,contato e carrinho
as imagens dos produtos de tamanho terão que ajustar o tamanho ,inserir a imagem do smarthphone, organização da pagina de produtos : titulo  não muito grande e  centralizado , deixar os cards dos produtos em tamanhos medios e iguais , ajustar a pagina de produto para o desktop . Ajuste do menu para o mobile e as paginas de carrinho,contato e pagina inicial para o mobile ] 