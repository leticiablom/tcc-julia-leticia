# Don't Do That! Hunting Down Visual Design Smells in Complex UIs against Design Guidelines

Yang, Bo; Xing, Zhenchang; Xia, Xin; Chen, Chunyang; Ye, Deheng; Li, Shanping. "Don't Do That! Hunting Down Visual Design Smells in Complex UIs against Design Guidelines," in *2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE)*, 2021. Publicado em: [10.1109/ICSE43902.2021.00075](https://doi.org/10.1109/ICSE43902.2021.00075)

## 1. Fichamento de Conteúdo

Este artigo aborda o problema dos "odores de design de UI" (_UI design smells_), que são violações de diretrizes de design visual em interfaces de usuário, análogos aos "odores de código" (_code smells_) no desenvolvimento de _software_. O estudo foca nas diretrizes "não faça isso" do _Material Design_ do _Google_, que vão além da estética e cobrem dimensões como _layout_, tipografia e navegação. O problema central é a prevalência dessas violações em aplicativos reais e a falta de ferramentas automáticas para detectá-las. Para solucionar isso, os autores desenvolveram uma ferramenta automatizada chamada UIS-Hunter, que analisa _screenshots_ de UIs para extrair informações multimodais (metadados de componentes, tipografia, cor, etc.) e as valida contra 71 diretrizes do _Material Design_. A ferramenta foi avaliada em um grande conjunto de dados com mais de 60.000 UIs de aplicativos _Android_, demonstrando alta precisão e _recall_. Estudos com usuários confirmaram que a detecção automatizada pelo UIS-Hunter é mais eficaz que a manual e que os problemas encontrados têm um impacto negativo severo na experiência do usuário.

## 2. Fichamento Bibliográfico

* **_UI design smells_ (odores de design de UI)** são definidos como interfaces de usuário mal projetadas que violam boas diretrizes de design. Eles são análogos aos *code smells* e podem prejudicar a usabilidade e a experiência do usuário, como no caso de textos truncados ou botões ilegíveis.
* **_Don't-do-that guidelines_ (diretrizes "não faça isso")** são recomendações explícitas em sistemas de design, como o Material Design, que instruem os desenvolvedores sobre práticas de design a serem evitadas. O estudo analisou 93 dessas diretrizes, que abrangem sete dimensões gerais de design e quatro aspectos de design de componentes.
* **_UIS-Hunter_** é a ferramenta automatizada desenvolvida no trabalho para detectar UI design smells. Ela opera extraindo cinco tipos de informações atômicas da UI (metadados, tipografia, iconografia, cor e borda) e as valida contra um conjunto de regras predefinidas baseadas nas diretrizes do _Material Design_.
* **_Atomic UI information_ (informação atômica de UI)** refere-se aos cinco tipos de dados fundamentais que a ferramenta extrai para validar as diretrizes: metadados do componente (tipo, posição, hierarquia), tipografia (aparência do texto renderizado), iconografia (presença de ícones/imagens), cor (cor primária de elementos) e borda (para formas e divisores).
* **_Component Design Aspects_ (Aspectos de Design de Componente)** são as quatro categorias nas quais o _Material Design_ organiza suas diretrizes: anatomia (composição do componente), posicionamento (localização na tela), comportamento (interação) e uso (cenários de aplicação). A maior parte das diretrizes (68%) está relacionada à anatomia dos componentes.

## 3. Fichamento de Citações

* _"Just like code smells that indicate violations of good software design guidelines, UI design smells violate good UI design guidelines."_ 
* _"In a study of 60,756 UIs of 9,286 Android apps, we find that 7,497 UIs of 2,587 apps have at least one violation of some Material Design guidelines."_ 
* _"The detection accuracy of UIS-Hunter is high (precision = 0.81, recall = 0.90) on the 60,756 UIs of 9,286 apps."_ 
* _"Our user studies show that UIS-Hunter is more effective than manual detection of UI design smells, and the UI design smells that are detected by UIS-Hunter have severely negative impacts on app users."_ 
* _"Manual detection of UI design smells is less effective than automated detection, especially when multiple pieces of information need to be integrated or there are component-variant-sensitive guidelines."_ 