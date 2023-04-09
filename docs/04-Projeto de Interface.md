
# Projeto de Interface

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Documentação de Especificação</a></span>

Visão geral da interação do usuário pelas telas do sistema e protótipo interativo das telas com as funcionalidades que fazem parte do sistema (wireframes).

 Apresente as principais interfaces da plataforma. Discuta como ela foi elaborada de forma a atender os requisitos funcionais, não funcionais e histórias de usuário abordados nas <a href="2-Especificação do Projeto.md"> Documentação de Especificação</a>.

## Diagrama de Fluxo

O diagrama apresenta o estudo do fluxo de interação do usuário com o sistema interativo e  muitas vezes sem a necessidade do desenho do design das telas da interface. Isso permite que o design das interações seja bem planejado e gere impacto na qualidade no design do wireframe interativo que será desenvolvido logo em seguida.

O diagrama de fluxo pode ser desenvolvido com “boxes” que possuem internamente a indicação dos principais elementos de interface - tais como menus e acessos - e funcionalidades, tais como editar, pesquisar, filtrar, configurar - e a conexão entre esses boxes a partir do processo de interação. Você pode ver mais explicações e exemplos https://www.lucidchart.com/blog/how-to-make-a-user-flow-diagram.

![Exemplo de Diagrama de Fluxo](img/diagramafluxo2.jpg)

As referências abaixo irão auxiliá-lo na geração do artefato “Diagramas de Fluxo”.

> **Links Úteis**:
> - [Fluxograma online: seis sites para fazer gráfico sem instalar nada | Produtividade | TechTudo](https://www.techtudo.com.br/listas/2019/03/fluxograma-online-seis-sites-para-fazer-grafico-sem-instalar-nada.ghtml)

## Wireframes

Conforme o diagrama de fluxo do projeto, apresentado no item anterior, as telas do sistema são apresentadas em detalhes nos itens que se seguem. Para visualizar o wireframe interativo, acesse o [PRONTCLINIC – login1 (marvelapp.com)](https://marvelapp.com/prototype/9fj13ad/screen/91212877)

As telas do sistema apresentam uma estrutura comum que é apresentada na Figura X. Nesta estrutura, existem 3 grandes blocos, descritos a seguir. São eles:
⦁	Cabeçalho - local onde são dispostos elementos fixos de identidade (logo) e navegação secundaria do site, menu de login de usuario;
⦁	Conteúdo - apresenta o conteúdo das informações solicitadas;
⦁	Barra lateral - apresenta os elementos de navegação principal,  associados aos elementos do bloco de conteúdo.
![Capturar12](https://user-images.githubusercontent.com/114547158/230796602-6fd6d603-7e86-48e0-9f98-f828c1848a5a.PNG)


Tela - Home- Recepção-Financeiro-Corpo Clinico
A tela de home  mostra  os caminhos a seguir em busca das informações que se deseja. 
Com base na estrutura padrão, o bloco conteúdo vai mostrar todas as informações solicitadas. O bloco da Menu Lateral traz três elementos distintos:
⦁	Componente de Paciente que permite ir para a o conteúdo de todas as informações dos pacientes;
⦁	Componente de Agendamento  que leva o usuário para a tela de Agendamentos;
⦁	Componente de Financeiro que dá acesso às telas pertinente ao setor financeiro.
⦁	Componente de Exames que dá acesso as telas de solicitação de exames.
Os componentes variam conforme o login de acesso!
[Capturar 3](https://user-images.githubusercontent.com/114547158/230796664-73364679-0631-4cee-9d9b-99a26e59d695.PNG)


Tela - Pacientes
A tela de pacientes  apresenta, no Bloco de Conteúdo, as informações referentes a um paciente especifico, escolhida pelo usuário. O Bloco de Barra Lateral apresenta os mesmos elementos da Home. 
![Capturar4](https://user-images.githubusercontent.com/114547158/230796682-ed618a3e-d032-49d4-bff7-b46033381d1d.PNG)
![Capturar 5](https://user-images.githubusercontent.com/114547158/230796705-4c12373f-f0a6-4214-a42f-f408b6f1f4c4.PNG)

Tela - Financeiro
Assim que entra em financeiro,  ele é direcionado para uma sequencia de  telas que traz a relação de consultas e exames associadas a pessoa informado. Este resultado é apresentado na Figura a seguir

 ![Capturar6](https://user-images.githubusercontent.com/114547158/230796761-49c57bbb-c1d3-413d-9756-9dfc5b3c029c.PNG)

 Tela - Agendamento
A tela de Agendamento apresenta, no Bloco de Conteúdo, um agendamento expecifico. O Bloco de Barra Lateral apresenta os mesmos elementos da Home. 
![Capturar7](https://user-images.githubusercontent.com/114547158/230796784-a2139b23-e048-433f-bd49-da3949e72c7f.PNG)

Tela - Exames
A tela que permite o agendamento de exames. Ela precisa primeiro cadastrar um id de paciente para então gerar a possibilidade de marcar exames
 
 ![Capturar8](https://user-images.githubusercontent.com/114547158/230796822-a5f4d9ca-b113-4e0a-b315-18c4a836646e.PNG)
![Capturar9](https://user-images.githubusercontent.com/114547158/230796859-5ed654fa-bf3d-4e9b-93de-88e1f8c5ae38.PNG)

Tela - Colaborador
A tela de Colaborador pode ser acessada, clicando no icone superior direito, onde vai estar o nome do colaborador. Com ela é possivel acessar os dados pertinentes do usuario logado. A primeira tela mostra os dados basicos de login de acesso. Já clicando no perfil id, mostra os dados de colaborador da empresa, como valor hora e especialidade.

![Capturar10](https://user-images.githubusercontent.com/114547158/230796880-dce18203-ae47-4539-90fe-d519952889c5.PNG)
![Capturar11](https://user-images.githubusercontent.com/114547158/230796884-cd9f1c7b-49fc-4001-bca4-2f93fa481af8.PNG)



 
> **Links Úteis**:
> - [Protótipos vs Wireframes](https://www.nngroup.com/videos/prototypes-vs-wireframes-ux-projects/)
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [Axure](https://www.axure.com/edu) (Licença Educacional)
> - [InvisionApp](https://www.invisionapp.com/) (Licença Educacional)
