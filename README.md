# Meu-Portifolio
<p align="center">Um site feito com HTML CSS e JavaScript no qual existem mais informações sobre mim e meus projetos pessoais😃</p>

/*CODIGO HTML*/
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--GOOGLE FONTES-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;
    0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;
    1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <!-- FIM GOOGLE FONTES-->
    <!--BOOTSTRAP-ICONS-->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.2/font/bootstrap-icons.min.css">
    <!--FIM BOOTSTRAP-ICONS-->
    <link rel="stylesheet" href="style.css">
    <script src="main.js" defer></script>
    <script src="menu.js" defer></script>
    <title>Site Bruno Burian</title>
</head>
<body>

    <header id="header">
        <div class="interface">
            <div class="lua-e-sol">
                <i class="bi bi-moon-fill"></i>
                <i class="bi bi-brightness-high-fill"></i>
            </div>
            <div class="trilho" id="trilho">
                <div class="indicador"></div>
            </div><!--trilho-->
            <nav class="menu-desktop">
                <ul>
                    <li><a href="#">Início</a></li>
                    <li><a href="#">Especialidades</a></li>
                    <li><a href="#">Sobre Mim</a></li>
                    <li><a href="#">Projetos</a></li>
                </ul>
            </nav><!--menu-desktop-->

            <div class="btn-contato">
                <a href="#">
                    <button>Contato</button>
                </a>
            </div><!--btn-contato-->

            <div class="btn-abrir-menu" id="btn-menu">
                <i class="bi bi-list"></i>
            </div><!--btn-abrir-menu-->

            <div class="menu-mobile" id="menu-mobile">
                <div class="btn-fechar">
                    <i class="bi bi-x-lg"></i>
                </div><!--btn-fechar-->
                <nav>
                    
                    <ul>
                        <li><a href="#">Início</a></li>
                        <li><a href="#">Especialidades</a></li>
                        <li><a href="#">Sobre Mim</a></li>
                        <li><a href="#">Projetos</a></li>
                        <li><a href="#">Contato</a></li>
                    </ul>
                </nav>
            </div><!--menu-mobile-->
            <div class="overlay-menu-mobile" id="overlay-menu-mobile">
            </div><!--overlay-menu-mobile-->
        </div><!--interface-->
    </header>

    <main>
        <section class="topo-do-site">
            <div class="interface">
                <div class="flex">
                    <div class="txt-topo-site">
                        <div class="txt-animado">
                            Olá, <span></span>
                        </div>
                        <p> Transformando códigos em conquistas, estou pronto para criar soluções inovadoras e 
                            desenvolver ideias que não apenas atendam, mas superem expectativas. Com uma mistura única de criatividade 
                            e lógica, busco não apenas resolver problemas, mas gerar resultados positivos.
                        </p>

                            <div class="btn-contato">
                                <a href="#">
                                    <button>Entre em contato</button>
                                </a>
                            </div>
                    </div><!--txt-topo-site-->

                    <div class="img-topo-site">
                        <img src="images/fotor-2024010817511.png" alt="foto-eu">

                    </div><!--txt-topo-site-->
                </div><!--flex-->
            </div><!--interface-->
        </section><!--topo-do-site-->

        <section class="redes-sociais">
            <div class="interface">
                <h2 class="titulo">MINHAS <span>ESPECIALIDADES.</span></h2>
                <div class="flex">
                    <div class="redes-sociais-box">
                        <i class="bi bi-code-square"></i>
                        <h3>Front-end</h3>
                        <p>Possuo habilidades em linguagens como HTML, CSS e Javascript, adquiridas por meio de prática nesses domínios.</p>
                    </div><!--redes-sociais-box-->
                    <div class="redes-sociais-box">
                        <i class="bi bi-braces"></i>
                        <h3>Back-end</h3>
                        <p> Com uso de lógica de programação desenvolvo programas e softwares nas linguagens Python e Java. </p>
                    </div><!--redes-sociais-box-->
                    <div class="redes-sociais-box">
                        <i class="bi bi-controller"></i>
                        <h3>Criação de jogos</h3>
                        <p>Usando muita criatividade consigo fazer jogos divertidos, tenho experiências com games feitos com JavaScript e C#</p>
                    </div><!--redes-sociais-box-->
                </div><!--flex-->
            </div><!--interface-->
        </section><!--redes-sociais-->

        <section class="sobre">
            <div class="interface">
                <div class="flex">
                    <div class="img-sobre">
                        <img src="images/fotor-2024010817511.png" alt="Minha foto">
                    </div><!--img-sobre-->

                    <div class="txt-sobre">
                        <h2>MUITO PRAZER, <span>SOU BRUNO BURIAN.</span></h2>
                        <p>Sou um estudante de Análise e Desenvolvimento de Sistemas apaixonado por transformar ideias em soluções práticas. 
                            Minha mente criativa está sempre em busca de oportunidades para crescer na área.
                            Possuo habilidades em <span>Python, HTML, CSS, Javascript e Java</span>, e meu objetivo é aplicar essas habilidades de forma inovadora. 
                            Estou constantemente aprendendo e evoluindo, pronto para colaborar em projetos desafiadores.</p></p>
                            <div class="btn-social">
                                <a href="https://www.linkedin.com/in/bruno-burian-264a64248/" target="_blank"><button><i class="bi bi-linkedin" ></i></button></a>
                                <a href="https://github.com/BruBurian" target="_blank"><button><i class="bi bi-github"></i></button></a>
                                <a href="https://web.whatsapp.com/send?phone=5511988185885" target="_blank"><button><i class="bi bi-whatsapp"></i></button></a>
                            </div><!--btn-social-->
                        </div><!--txt-sobre-->
                </div><!--flex-->
            </div><!--interface-->
        </section>

        <section class="portifolio">
            <div class="interface">
                <h2 class="titulo">MEU <span>PORTIFÓLIO.</span></h2>
                <div class="flex">
                    <div class="img-port" style="background-image: url(images/foto\ eu2.png);">
                        <div class="overlay">Projeto 1</div>
                    </div>
                    <div class="img-port" style="background-image: url(images/foto\ eu2.png);">
                        <div class="overlay">Projeto 2</div>
                    </div>
                    <div class="img-port" style="background-image: url(images/foto\ eu2.png);">
                        <div class="overlay">Projeto 3</div>
                    </div>
                </div><!--flex-->
            </div><!--interface-->
        </section><!--portifólio-->

        <section class="formulario">
            <div class="interface">
                <h2 class="titulo">FALA <span>COMIGO.</span></h2>

                <form action="">
                    <input type="text" class="text" placeholder="Seu nome completo:" required>
                    <input type="text" class="text" placeholder="Seu email:" required>
                    <input type="text" class="text" placeholder="Seu celular:">
                    <textarea name="" id="" placeholder="Sua mensagem:" required></textarea>
                    <div class="btn-enviar"><input type="submit" value="ENVIAR"></div>
                </form>
            </div><!--interface-->
        </section><!--formulario-->
    </main>

    <footer>
        <div class="interface">
            <div class="line-footer borda">
                <div class="flex">
                    <div class="btn-social">
                        <a href="https://www.linkedin.com/in/bruno-burian-264a64248/" target="_blank"><button><i class="bi bi-linkedin"></i></button></a>
                        <a href="https://github.com/BruBurian" target="_blank"><button><i class="bi bi-github"></i></button></a>
                        <a href="https://web.whatsapp.com/send?phone=5511988185885" target="_blank"><button><i class="bi bi-whatsapp"></i></button></a>
                    </div><!--btn-social--> 
            </div><!--flex-->
            </div><!--line-footer-->
            
            <div class="line-footer">
                <p><i class="bi bi-envelope-fill"></i> <a href="mailto:brunoburian@gmail.com">brunoburian@gmail.com</a></p>
            </div><!--line-footer-->
        </div><!--interface-->
    </footer>
</body>
</html>
