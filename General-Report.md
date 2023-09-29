//////////////////////////////////////////////////PORTUGUÊS-BR///////////////////////////////////////////////////////////////

**Relatório de Atividades**

**Perfil de Cartão Interativo**

Este projeto consiste em um perfil de cartão interativo que destaca informações sobre mim, Guilherme Ferreira, um programador júnior. O cartão possui duas faces (frente e verso) que podem ser alternadas por meio de um clique.

**Funcionalidades Implementadas:**
1. **Rotação do Cartão:** Ao clicar no cartão, ele gira para exibir o verso, onde são fornecidas informações adicionais sobre mim.

2. **Imagem Superior Interativa:** A imagem superior do cartão aumenta de tamanho quando o usuário passa o mouse sobre ela, criando um efeito visual agradável.

3. **Botões de Rede Social:** Foram adicionados botões que levam às minhas redes sociais, incluindo LinkedIn, TikTok e GitHub.

4. **Texto Explicativo:** Na parte traseira do cartão, há um texto que descreve minha experiência em programação Python e Javascript, bem como meu entusiasmo pelo aprendizado contínuo.

5. **Botão "Clique Aqui para Mais Informações":** Esse botão na frente do cartão convida o usuário a clicar para saber mais sobre mim.

**Tecnologias Utilizadas:**
- **HTML:** A estrutura da página foi criada em HTML para definir os elementos do cartão e a organização da página.

- **CSS:** O estilo do cartão e a animação de rotação foram definidos em CSS para criar uma aparência atraente.

- **JavaScript:** A interatividade do cartão foi implementada com JavaScript para alternar a classe que controla a rotação do cartão.

- **Font Awesome:** Ícones de redes sociais foram incorporados usando a biblioteca Font Awesome.

Estrutura Principal:

HTML: O arquivo HTML (index.html) define a estrutura geral do documento. Ele contém os elementos HTML que compõem o cartão de perfil, incluindo a imagem do perfil, informações pessoais, botões de redes sociais e o cartão de volta (back).

CSS: O CSS é usado para estilizar o cartão de perfil e controlar sua aparência. Ele define as regras de estilo para o cartão de frente (front), o cartão de volta (back), a transição de rotação e outros estilos visuais.

JavaScript: O JavaScript (script na parte inferior do HTML) fornece a funcionalidade interativa do cartão. A função toggleRotation() é chamada quando o botão "clique aqui para mais informações" é pressionado. Essa função adiciona ou remove a classe .rotate do elemento .CARD, o que desencadeia a rotação do cartão.

Funcionalidade Principal:

Quando a página é carregada, o cartão é exibido com a frente voltada para o usuário. A frente do cartão contém a imagem do perfil e informações pessoais.
Quando o usuário clica no botão "clique aqui para mais informações", a função toggleRotation() é chamada. Isso adiciona ou remove a classe .rotate do elemento .CARD.
A classe .rotate controla a rotação do cartão, fazendo com que ele gire para revelar o conteúdo da parte de trás (back) do cartão.
A parte de trás do cartão contém informações adicionais sobre a pessoa, como uma descrição e um botão de link para o Instagram.
A transição de rotação é suave e controlada por CSS para criar um efeito de virada de cartão realista.
Em resumo, este projeto é um cartão de perfil interativo que permite ao usuário clicar em um botão para ver informações adicionais no verso do cartão. Ele usa HTML, CSS e JavaScript para criar uma experiência interativa.

**Como Usar:**
1. Clone este repositório para o seu ambiente local.
2. Abra o arquivo `index.html` em um navegador da web.
3. Clique no cartão para ver a rotação e obter mais informações.

Certamente! Personalizar o projeto do cartão de perfil é uma ótima maneira de torná-lo único e adaptá-lo às suas próprias necessidades. Aqui estão algumas dicas e orientações sobre como você pode personalizar o projeto:
Imagem do Perfil: Substitua a imagem do perfil (<img src="2eu.jpg">) pela sua própria imagem. Certifique-se de que a imagem tenha um tamanho e proporção adequados para se encaixar bem no cartão.
Informações Pessoais: No elemento "<.h2>", você pode substituir "Guilherme Ferreira" pelo seu próprio nome e a descrição de "Programador junior | Python | Javascript" por sua própria descrição ou título.
Redes Sociais: Atualize os links das redes sociais nos botões, como LinkedIn, TikTok e GitHub, para que apontem para seus próprios perfis. Substitua os links nas âncoras <a href.="#"> pelos URLs corretos.
Conteúdo do Back (Verso): Personalize o conteúdo do verso do cartão (<div class="back">) com suas próprias informações. Substitua o texto e adicione detalhes relevantes sobre você, suas habilidades, experiência, interesses, etc. Além disso, você pode adicionar mais botões ou links conforme necessário.
Estilos CSS: Modifique o CSS no <style> para personalizar as cores, fontes, tamanhos e estilos do texto, botões e outros elementos. Isso permitirá que você adapte a aparência do cartão ao seu gosto pessoal.
Tamanho do Cartão: Você pode ajustar o tamanho do cartão alterando as propriedades de largura e altura em .CARD e .imgBx, bem como a altura máxima no estado de hover.
Outras Personalizações: Sinta-se à vontade para adicionar outros elementos, como ícones, imagens de fundo, animações ou quaisquer outros elementos visuais que desejar.
Comentários: Se quiser manter uma referência sobre as modificações que fez, adicione comentários em seu código para que você ou outras pessoas possam entender facilmente as alterações feitas.

Lembre-se de que a chave para a personalização é adaptar o projeto de acordo com suas próprias preferências e necessidades. Experimente diferentes estilos e elementos até que o cartão de perfil represente da melhor forma quem você é ou o que deseja destacar.

**Créditos:**
Este projeto foi criado como uma demonstração de habilidades de programação e design. Sinta-se à vontade para explorar e personalizar conforme desejado. Agradeço aos criadores dos seguintes tutoriais que me ajudaram no desenvolvimento deste projeto:

- [Tutorial 1](https://www.youtube.com/watch?v=kdF9fdA4vtU)
- [Tutorial 2](https://www.youtube.com/watch?v=daAVTmsMXeI)

Por favor, ao usar este código como inspiração, certifique-se de fornecer os créditos apropriados.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
////////////////////////////////////////////////////////////////////////////////////////////////////////////////English//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
**Activity Report**

**Interactive Profile Card**

This project consists of an interactive profile card that highlights information about me, Guilherme Ferreira, a junior programmer. The card has two sides (front and back) that can be toggled with a click.

**Implemented Features:**
1. **Card Rotation:** Clicking on the card causes it to flip to display the back, where additional information about me is provided.

2. **Interactive Top Image:** The top image of the card enlarges when the user hovers over it, creating a pleasing visual effect.

3. **Social Media Buttons:** Buttons leading to my social media profiles, including LinkedIn, TikTok, and GitHub, have been added.

4. **Explanatory Text:** On the back of the card, there is text describing my experience in Python and JavaScript programming, as well as my enthusiasm for continuous learning.

5. **"Click Here for More Information" Button:** This button on the front of the card invites the user to click for more information about me.

**Technologies Used:**
- **HTML:** The page structure was created in HTML to define the card's elements and page layout.

- **CSS:** CSS was used to style the card and control its appearance, including the rotation animation.

- **JavaScript:** JavaScript was used to implement card interactivity by toggling the class that controls card rotation.

- **Font Awesome:** Social media icons were incorporated using the Font Awesome library.

Main Structure:

HTML: The HTML file (index.html) defines the overall document structure. It contains the HTML elements that make up the profile card, including the profile image, personal information, social media buttons, and the card's back.

CSS: CSS is used to style the profile card and control its appearance. It defines styling rules for the front and back of the card, rotation transition, and other visual styles.

JavaScript: JavaScript (script at the bottom of the HTML) provides the interactive functionality of the card. The `toggleRotation()` function is called when the "click here for more information" button is pressed. This function adds or removes the `.rotate` class from the `.CARD` element, triggering the card's rotation.

Key Functionality:

- When the page loads, the card is displayed with the front facing the user. The front of the card contains the profile image and personal information.
- When the user clicks the "click here for more information" button, the `toggleRotation()` function is called. This adds or removes the `.rotate` class from the `.CARD` element.
- The `.rotate` class controls the card's rotation, causing it to flip to reveal the content on the back of the card.
- The back of the card contains additional information about the person, such as a description and a link button to Instagram.
- The rotation transition is smooth and controlled by CSS to create a realistic card flip effect.

In summary, this project is an interactive profile card that allows users to click a button to view additional information on the card's back. It uses HTML, CSS, and JavaScript to create an interactive experience.

**How to Use:**
1. Clone this repository to your local environment.
2. Open the `index.html` file in a web browser.
3. Click on the card to see the rotation and get more information.

Certainly! Customizing the profile card project is a great way to make it unique and tailor it to your own needs. Here are some tips and guidelines on how you can customize the project:
Profile Image: Replace the profile image (`<img src="2eu.jpg">`) with your own image. Make sure the image has an appropriate size and aspect ratio to fit well on the card.
Personal Information: In the `<h2>` element, you can replace "Guilherme Ferreira" with your own name and the description of "Junior Programmer | Python | JavaScript" with your own description or title.
Social Media: Update the social media links on the buttons, such as LinkedIn, TikTok, and GitHub, to point to your own profiles. Replace the links in the `<a href="#">` anchors with the correct URLs.
Back Content: Customize the content on the back of the card (`<div class="back">`) with your own information. Replace the text and add relevant details about yourself, your skills, experience, interests, etc. Additionally, you can add more buttons or links as needed.
CSS Styles: Modify the CSS in the `<style>` to customize the colors, fonts, sizes, and styles of text, buttons, and other elements. This will allow you to adapt the card's appearance to your personal preferences.
Card Size: You can adjust the card's size by changing the width and height properties in `.CARD` and `.imgBx`, as well as the maximum height in the hover state.
Other Customizations: Feel free to add other elements, such as icons, background images, animations, or any other visual elements you desire.
Comments: If you want to keep a reference of the modifications you've made, add comments in your code so that you or others can easily understand the changes made.

Remember that the key to customization is to tailor the project to your own preferences and needs. Experiment with different styles and elements until the profile card represents who you are or what you want to highlight.

**Credits:**
This project was created as a demonstration of programming and design skills. Feel free to explore and customize it as desired. I would like to thank the creators of the following tutorials that helped me in the development of this project:

- [Tutorial 1](https://www.youtube.com/watch?v=kdF9fdA4vtU)
- [Tutorial 2](https://www.youtube.com/watch?v=daAVTmsMXeI)

Please, when using this code as inspiration, be sure to provide appropriate credits.

## License

This project is licensed under the [MIT License](LICENSE).
