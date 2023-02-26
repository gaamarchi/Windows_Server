# Shadow Copy
O Shadow Copy do Windows Server é uma ferramenta que permite a criação de cópias instantâneas, sem a necessidade de interromper o acesso ou a operação do sistema. Essas cópias podem ser usadas para restaurar arquivos ou pastas caso ocorra algum problema ou perda de dados.  

## como fazer o shadow copy
primeiro vamos iniciar a maquina  
abrir o explorador de arquivo (win+e)  
![imagem_2023-02-26_131647583](https://user-images.githubusercontent.com/101679723/221422500-6286b165-5a82-4c65-b179-4475b9ed58c4.png)  
clicando em "this pc" achamos o disco local  
clicando com o botão direito nele 
![imagem_2023-02-26_131750447](https://user-images.githubusercontent.com/101679723/221422568-0eaa34dc-8769-40f6-ba1e-8374f5030222.png)  
achamos a opção "configure shadow copies", clicando nela  
![imagem_2023-02-26_131925302](https://user-images.githubusercontent.com/101679723/221422667-a41decda-4f4d-45fe-b5ee-22a9249f337c.png)
selecionado o disco c, clique em enable aceite  
- nota podemos fazer o shadow copy do disco c usando um outro hd mas por ser um backoup de arquivo simples optei por usar o mesmo disco, caso queira adicionar outr disco [clique aqui]()  
clicando em settings  
![imagem_2023-02-26_132241981](https://user-images.githubusercontent.com/101679723/221422860-6f5080b4-25f9-44eb-a50b-8834a1e580b9.png)
maximum size vamos deixar em "no limits", clicando em schedule  
![imagem_2023-02-26_132413323](https://user-images.githubusercontent.com/101679723/221422959-f8eb66c1-ecc9-45e2-bc7a-85477b51f9e7.png)  
abrimos esta tela onde podemos configurar quando os snapshot serão feitos  
  
  

## como recuperar uma informação
![imagem_2023-02-26_132630563](https://user-images.githubusercontent.com/101679723/221423088-aa738944-5b9d-4abc-a8bb-1eda26d5086b.png)  
nossa pasta principal esta assim e a snapshot ja foi feita  
deletando a pasta financiero  
![imagem_2023-02-26_132805069](https://user-images.githubusercontent.com/101679723/221423196-c7aebcc6-dd1b-4330-a55e-96d57350173d.png)  
agora vamos recuperar, clicando com o botão direito em cima do disoc c  
![imagem_2023-02-26_132900104](https://user-images.githubusercontent.com/101679723/221423247-f92834f5-49ae-4555-b70b-b4f4390c5971.png)  
achamos a opção "restoure previus version"  
clicando nela, vai abrir uma tela com todas as nossas snapshots escolhermos qual queremos abrir e damos dois cliques  
após fazer isso vai abrir uma tela com a snap antiga escolha a pasta que quer recuperar e arraste para o local da original  
