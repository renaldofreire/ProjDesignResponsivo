# Projeto - Criar uma página de documentação técnica

Atenda às especificações de usuário abaixo para passar em todos os testes. Dê à página o seu próprio estilo pessoal.

Você pode usar HTML, JavaScript e CSS para completar este projeto. É recomendado utilizar CSS puro, pois é disso que trataram as lições até agora. É bom você adquirir alguma prática com CSS. Você pode usar Bootstrap ou SASS se quiser. Outras tecnologias (como, por exemplo, jQuery, React, Angular ou Vue) não são recomendadas para este projeto. Use-as por sua conta e risco. Outros projetos te darão uma chance de trabalhar com diferentes bibliotecas, como o React. Vamos aceitar e tentar corrigir todos os relatórios de problemas que usem a stack de tecnologias sugerida para esse projeto. Boa programação!

Especificação de usuário nº 1: deve haver um elemento main com um id="main-doc", que contém o conteúdo principal da página (documentação técnica).

Especificação de usuário nº 2: dentro do elemento #main-doc, deve haver várias seções (section), cada uma com a classe main-section. Deve haver um mínimo de 5.

Especificação de usuário nº 3: o primeiro elemento de cada .main-section deve ser um elemento de cabeçalho (header) que contém o texto que descreve o tópico desta seção.

Especificação de usuário nº 4: cada section com a classe main-section também deve ter um id que corresponda ao texto de cada header contido dentro dela. Os espaços existentes devem ser substituídos por sublinhados (por exemplo, a section que contém o cabeçalho "JavaScript e Java" deve ter um id="JavaScript_and_Java").

Especificação de usuário nº 5: os elementos .main-section devem conter, juntos, pelo menos 10 elementos p no total (não 10 para cada elemento).

Especificação de usuário nº 6: os elementos .main-section devem conter, juntos, pelo menos 5 elementos code no total (não 5 para cada elemento).

Especificação de usuário nº 7: os elementos .main-section devem conter, juntos, pelo menos 5 elementos li no total (não 5 para cada elemento).

Especificação de usuário nº 8: deve haver uma barra de navegação (nav) com um id="navbar".

Especificação de usuário nº 9: o elemento de barra de navegação (nav) deve conter um elemento header que contém o texto que descreve o tópico da documentação técnica.

Especificação de usuário nº 10: além disso, a barra de navegação (nav) deve conter elementos de âncora (a) com a classe nav-link. Deve haver um para cada elemento com a classe main-section.

Especificação de usuário nº 11: o elemento header na barra de navegação deve aparecer antes de qualquer elemento de âncora (a).

Especificação de usuário nº 12: cada elemento com a classe nav-link deve conter um texto que corresponda ao texto do header dentro de cada section (exemplo: se você tem uma seção/cabeçalho "Olá mundo", sua barra de navegação deve ter um elemento que contém o texto "Olá mundo").

Especificação de usuário nº 13: quando um elemento da barra de navegação for clicado, a página deve navegar para a seção correspondente ao elemento main-doc (exemplo: se eu clicar em um elemento nav-link que contém o texto "Olá mundo", a página deve navegar para o elemento section que tem esse id e contém o header correspondente.

Especificação de usuário nº 14: em dispositivos com tamanho regular (laptops, desktops), o elemento com id="navbar" deve ser mostrado no lado esquerdo da tela e deve sempre estar visível para o usuário.

Especificação de usuário nº 15: a página deve ter pelo menos uma media query.
