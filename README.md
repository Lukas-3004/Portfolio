<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Numérique - Lukas Osorio</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <link href="CSS/style_main.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body class="bg-light">
    
    <!-- Navigation Menu -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#accueil">Lukas Osorio</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#accueil">Accueil</a></li>
                    <li class="nav-item"><a class="nav-link" href="#profil">Profil</a></li>
                    <li class="nav-item"><a class="nav-link" href="#bts">BTS SIO</a></li>
                    <li class="nav-item"><a class="nav-link" href="#parcours">Parcours</a></li>
                    <li class="nav-item"><a class="nav-link" href="#stages">Stages</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projets">Projets</a></li>
                    <li class="nav-item"><a class="nav-link" href="#certifications">Certifications</a></li>
                    <li class="nav-item"><a class="nav-link" href="#veille">Veille</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
    
    <!-- Main -->
    <header id="accueil" class="text-white">
        <div class="overlay"></div>
        <div class="container position-relative">
            <div class="row align-items-center min-vh-100">
                <div class="col-lg-6 text-lg-start">
                    <h1 class="display-1 fw-bold mb-4 text-shadow">Lukas Osorio</h1>
                    <p class="lead mb-4 fs-2">Étudiant en BTS SIO option SISR</p>
                    <div class="d-flex gap-3 justify-content-lg-start justify-content-center">
                        <a href="#contact" class="btn btn-primary btn-lg px-4 fw-bold">Me contacter</a>
                        <a href="#projets" class="btn btn-outline-light btn-lg px-4 fw-bold">Mes projets</a>
                    </div>
                </div>
            </div>
        </div>
    </header>
    
    <section id="profil" class="container text-center">
        <h2 class="section-title">Mon Profil</h2>
        <div class="row">
             
            <!-- Carte 2 : Passions -->
            <div class="col-md-4">
                <div class="profile-card">
                    <i class="fas fa-heart"></i>
                    <h3>Mes Passions</h3>
                    <ul class="passion-list">
			<li><i class="fas fa-futbol"></i>Sport</li>
                        <li><i class="fas fa-book"></i> Manga</li>
                        <li><i class="fas fa-music"></i> Musique Latine</li>
                    </ul>
                </div>
            </div>
            <!-- Carte 1 : Présentation -->
            <div class="col-md-4">
                <div class="profile-card">
                    <i class="fas fa-user"></i>
                    <h3>Qui suis-je ?</h3>
                    <p>Étudiant en 2ᵉ année de BTS SIO option SISR, je me spécialise dans l'administration des systèmes et réseaux.  
                    Ayant toujours eu une curiosté vers l'informatique, j'ai donc décidé d'intégrer cette filière pour en faire mon metier.       
                    Grâce à mes expériences en support et en gestion de parc informatique, j’ai acquis des compétences en 
                    maintenance, sécurisation des systèmes et assistance aux utilisateurs.</p>
                </div>
            </div>
            <!-- Carte 3 : Objectifs -->
            <div class="col-md-4">
                <div class="profile-card">
                    <i class="fas fa-bullseye"></i>
                    <h3>Objectifs Professionnels</h3>
                    <p>J'ai pour ambition de continuer ma formation jusqu'au BAC +3, en acquierant mon Bachelor Systèmes, Réseaux et Cloud
                    et ensuite pouvoir continuer en Bac +5 en visant le RCNP Niveau 7. 
                    Cela me permettrais de pouvoir accéder a des postes comme Administrateur Système et Réseau ou Ingénieur Réseau</p>
                </div>
            </div>
        </div>
    </section>
       
    <!-- BTS SIO -->
    <section id="bts" class="container text-center">
        <h2 class="section-title">BTS SIO - Services Informatiques aux Organisations</h2>
        <p class="intro-text">
            Avant de parler de mon parcours, voici une présentation rapide de ma filière.
            Le <b class="neon2">BTS SIO</b> est une formation en deux ans qui prépare aux métiers de l'informatique,
            avec deux spécialités : administration des systèmes et réseaux (<b>SISR</b>) ou développement logiciel (<b>SLAM</b>).
        </p>

        <div class="row justify-content-center mt-5">
            <!-- Option SISR -->
            <div class="col-md-5">
                <div class="bts-option sisr">
                    <i class="fas fa-network-wired"></i>
                    <h3>Option SISR</h3>
                    <p>
                        L’option Solutions d’Infrastructure, Systèmes et Réseaux forme des experts en gestion et sécurisation des infrastructures informatiques.
                        Cette spécialisation est idéale pour ceux qui souhaitent travailler dans la mise en place, la maintenance et la sécurisation des réseaux.
                    </p><br>
                    <h4>Compétences apprises :</h4><br>
                    <ul class="competences-list">
                        <li><i class="fas fa-server"></i> Stormshield (Firewall & Sécurité)</li>
                        <li><i class="fas fa-shield-alt"></i> HAProxy (Load Balancing & Proxy)</li>
                        <li><i class="fas fa-cogs"></i> Iptables (Pare-feu Linux)</li>
                        <li><i class="fas fa-cloud"></i> Active Directory (Gestion des utilisateurs & GPO)</li>
                        <li><i class="fas fa-laptop-medical"></i> PowerShell (Scripts d'automatisation)</li>
                        <li><i class="fas fa-network-wired"></i> Réseaux TCP/IP (Configuration & Sécurité)</li>
                        <li><i class="fas fa-code"></i> Linux (Debian, Kali Linux, Administration système)</li>
                        <li><i class="fas fa-cloud-upload-alt"></i> Virtualisation (VMware, PfSense)</li>
                    </ul><br>
                    <h4>Débouchés :</h4><br>
                    <ul class="list-unstyled">
                        <li><i class="fas fa-server"></i> Administrateur systèmes et réseaux</li>
                        <li><i class="fas fa-shield-alt"></i> Consultant en cybersécurité</li>
                        <li><i class="fas fa-cogs"></i> Ingénieur systèmes et réseaux</li>
                        <li><i class="fas fa-cloud"></i> Architecte Cloud</li>
                        <li><i class="fas fa-laptop-medical"></i> Technicien SOC (Sécurité informatique)</li>
                    </ul>
                </div>
            </div>
            <!-- Option SLAM -->
            <div class="col-md-5">
                <div class="bts-option slam">
                    <i class="fas fa-code"></i>
                    <h3>Option SLAM</h3>
                    <p>
                        L’option Solutions Logicielles et Applications Métiers est destinée aux étudiants qui veulent se spécialiser dans la conception, le développement et la maintenance.
                        Cette option permet d’acquérir des compétences en programmation, gestion de bases de données et cybersécurité des applications.
                    </p><br>
                    <h4>Compétences apprises :</h4><br>
                    <ul class="competences-list">
                        <li><i class="fas fa-code"></i> Développement Web (HTML, CSS, JavaScript, PHP)</li>
                        <li><i class="fas fa-database"></i> Gestion de bases de données (MySQL, SQL Server)</li>
                        <li><i class="fas fa-laptop-code"></i> Programmation Orientée Objet (Java, C#)</li>
                        <li><i class="fas fa-cogs"></i> Frameworks (Symfony, Laravel, Spring)</li>
                        <li><i class="fas fa-cloud"></i> Développement d'applications mobiles(Android, iOS)</li>
                        <li><i class="fas fa-server"></i> Serveurs et Hébergement (Apache, Nginx, Docker)</li>
                        <li><i class="fas fa-users"></i> Gestion de projet (Méthodes agiles, Scrum, Git)</li>
                        <li><i class="fas fa-tools"></i> Intégration continue (GitHub, GitLab)</li>
                    </ul><br>
                    <h4>Débouchés :</h4><br>
                    <ul class="list-unstyled">
                        <li><i class="fas fa-laptop-code"></i> Développeur d'applications</li>
                        <li><i class="fas fa-database"></i> Administrateur de bases de données</li>
                        <li><i class="fas fa-cogs"></i> Ingénieur DevOps</li>
                        <li><i class="fas fa-shield-alt"></i> Expert en cybersécurité des applications</li>
                        <li><i class="fas fa-cloud"></i> Architecte logiciel</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>


    <!-- Parcours -->
    <section id="parcours" class="container text-center">
        <h2 class="section-title">Parcours</h2>
            <div class="container pt-5">
                <div class="row">
                    <!-- Formations -->
                    <div class="col-md-6">
                        <h2 class="for">Formations</h2>
                        <ul class="timeline">
                            <li>
                                <div class="title">2023</div>
                                <div class="details">
                                    <h5>ENC Bessières</h5>
				                    <b><small>Septembre 2023 - Juillet 2025</small></b></br>
                                    <small>BTS SIO option SISR</small>
                                    <p>Paris 17ème</p>
                                </div>
                            </li>
                            <li>
                                <div class="title">2020</div>
                                <div class="details">
                                <h5>Lycée Gustave Ferrié</h5>
                                <b><small>Septembre 2020 - Juillet 2023</small></b></br>
                                <small>Baccalauréat Professionnel SN option RISC (Mention Bien)</small>
                                <p>Paris 10ème</p>
                                </div>
                            </li>
                            <li>
                                <div class="title">2019</div>
                                <div class="details">
                                <h5>Lycée Les Cotes de Villebon</h5>
                                <b><small>Septembre 2019 - Juillet 2020</small></b></br>
                                <small>Baccalauréat Professionnel SN</small>
                                <p>Meudon La Forêt</p>
                            </div>
                            </li>
                        </ul>
                    </div>
                    <!-- Expériences -->
                    <div class="col-md-6">
                    <h2 class="exp">Expériences</h2>
                        <ul class="timeline">
                            <li>
                                <div class="title">2024</div>
                                <div class="details">
                                    <h5>Rectorat de Paris</h5>
				                    <b><small> janvier 2025 -  mars 2025 (8 semaines)</small></b></br>
                                    <small>Stage - Technicien Support</small>
                                    <p>Maintenance, support utilisateurs, clonage de machines, gestion réseau.</p>
                                </div>
                            </li>
                            <li>
                                <div class="title">2024</div>
                                <div class="details">
                                    <h5>ENC Bessières</h5>
				                    <b><small> Mai 2024 -  Juin 2024 (5 semaines)</small></b></br>
                                    <small>Bénévolat - Support IT</small>
                                    <p>Gestion d'un parc de 800 machines, assistance et résolution de problèmes.</p>
                                </div>
                            </li>
                            <li>
                                <div class="title">2023</div>
                                <div class="details">
                                    <h5>Carrefour Market</h5>
                                    <b><small>Novembre 2023 - ...</small></b></br>
                                    <small>CDI - Employé polyvalent</small>
                                    <p>Accueil client, mise en rayon, gestion de la trésorerie.</p>
                                </div>
                            </li>
                            <li>
                                <div class="title">2023</div>
                                <div class="details">
                                    <h5>BNP Paribas</h5>
                                    <b><small>Octobre 2022 - Decembre 2022 (5 seamines)</small></b></br>
                                    <small>Stage Terminal</small>
                                    <p>Analyse de bases de données, programmation des systèmes.</p>
                                </div>
                            </li>
                            <li>
                                <div class="title">2022</div>
                                <div class="details">
                                    <h5>Geodis</h5>
                                    <b><small>Avril 2022 - Mai 2022(5 semaines)</small></b></br>
                                    <small>Stage Première</small>
                                    <p>Analyse et gestion des données clients (Data Quality).</p>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
    </section>
    
    <!-- Stages -->
    <section id="stages" class="container text-center">
        <h2 class="section-title">Stages</h2>
    <p class="lead">Découvrez mes expériences professionnelles lors de mes stages en entreprise</p><br>
        <div class="row justify-content-center">
            <div class="col-md-5">
                <div class="stage-card">
                    <img src="Images/Logo_ENC.jpg" alt="Logo Stage" class="stage-logo">
                    <h3 class="stage-title">Stage de 1ère année</h3>                      
                    <p>Expérience en tant que Technicien Support a l'ENC Bessières</p>
                    <a href="Stage1_V2.html"><button class="btn-project">Voir plus</button></a> 
                </div>
            </div>
            
    
            <!-- Stage de 2ème année -->
            <div class="col-md-5">
                <div class="stage-card">
                    <img src="Images/Logo_rect.png" alt="Logo Stage" class="stage-logo">
                    <h3 class="stage-title">Stage de 2ème année</h3>                       
                    <p>Expérience en tant que Technicien Support au Rectorat de Paris</p>
                    <a href="Stage2_V2.html"><button class="btn-project">Voir plus</button></a>
                </div>
            </div>
        </div>
    </section>

    
<!-- Section Projets -->
<section id="projets" class="container text-center">
    <h2 class="section-title">Projets</h2>
    <p class="lead">Découvrez quelques-uns de mes projets techniques</p>
    <br>
    <div class="row">
        <div class="col-md-4 d-flex align-items-stretch">
            <div class="project-card">
                <img src="Images/Logo_Pro1.png" alt="Projet 1" class="project-logo">
                <h3 class="stage-title">Myhouse</h3>
                <p>Infrastructure réseau complète avec PfSense</p>
                <a href="Projet1.html" class="btn-project">Voir plus</a>
            </div>
        </div>

        <div class="col-md-4 d-flex align-items-stretch">
            <div class="project-card">
                <img src="Images/Logo_Pro2.jpg" alt="Projet 2" class="project-logo">
                <h3 class="stage-title">Active Directory</h3>
                <p>Scripts d'automatisations de l'Active Directory avec PowerShell</p>
                <a href="Projet2.html" class="btn-project">Voir plus</a>
            </div>
        </div>

        <div class="col-md-4 d-flex align-items-stretch">
            <div class="project-card">
                <img src="Images/Logo_Pro3.png" alt="Projet 3" class="project-logo">
                <h3 class="stage-title">Cloud Omada</h3>
                <p>Déploiement d'un réseau WiFi avec contrôleur centralisé</p>
                <a href="Projet3.html" class="btn-project">Voir plus</a>
            </div>
        </div>
    </div>
</section>
    
    <!-- Certificats -->
<section id="certifications" class="container text-center">
    <div class="container">
        <div class="section-title">
            <h2>Certifications</h2>
        </div>
        <div class="pmy">
            <p class="lead">Mes certifications et formations complémentaires</p><br>
        </div>
        <!-- Une seule row pour toutes les certifications -->
        <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
            <!-- Certification 1 -->
            <div class="col">
                <div class="card h-100 fade-in">
                    <div class="card-body text-center">
                        <i class="fas fa-certificate fa-3x text-primary mb-3"></i>
                        <h5 class="card-title">CCNA1</h5>
                        <p class="card-text">Certification Cisco Networking</p>
                        <a href="Images/Certificat_CCNA1_OSORIO.pdf" class="btn btn-outline-primary" target="_blank">
                            <i class="fas fa-eye me-2"></i> Voir le certificat
                        </a>
                    </div>
                </div>
            </div>
            
            <!-- Certification 2 -->
            <div class="col">
                <div class="card h-100 fade-in">
                    <div class="card-body text-center">
                        <i class="fas fa-shield-alt fa-3x text-success mb-3"></i>
                        <h5 class="card-title">Cybersécurité</h5>
                        <p class="card-text">Les bases de la cybersécurité</p>
                        <a href="Images/Certificat_Cybersecurite_Osorio.pdf" class="btn btn-outline-success" target="_blank">
                            <i class="fas fa-eye me-2"></i> Voir le certificat
                        </a>
                    </div>
                </div>
            </div>
            
            <!-- Certification 3 -->
            <div class="col">
                <div class="card h-100 fade-in">
                    <div class="card-body text-center">
                        <i class="fas fa-lock fa-3x text-warning mb-3"></i>
                        <h5 class="card-title">MOOC ANSSI</h5>
                        <p class="card-text">Certification : MOOC ANSSI</p>
                        <a href="Images/Attestation_MOOC_OSORIO.pdf" class="btn btn-outline-warning" target="_blank">
                            <i class="fas fa-eye me-2"></i> Voir le certificat
                        </a>
                    </div>
                </div>
            </div>
            
            <!-- Certification 4 -->
            <div class="col">
                <div class="card h-100 fade-in">
                    <div class="card-body text-center">
                        <i class="fab fa-linux fa-3x text-info mb-3"></i>
                        <h5 class="card-title">Linux</h5>
                        <p class="card-text">Les bases de Linux</p>
                        <a href="Images/Attestation_Decouverte_Osorio.pdf" class="btn btn-outline-info" target="_blank">
                            <i class="fas fa-eye me-2"></i> Voir le certificat
                        </a>
                    </div>
                </div>
            </div>
            
            <!-- Certification 5 -->
            <div class="col">
                <div class="card h-100 fade-in">
                    <div class="card-body text-center">
                        <i class="fas fa-network-wired fa-3x text-danger mb-3"></i>
                        <h5 class="card-title">CCNAv7</h5>
                        <p class="card-text">Introduction au réseau</p>
                        <a href="Images/CCNAv7_Osorio.pdf" class="btn btn-outline-danger" target="_blank">
                            <i class="fas fa-eye me-2"></i> Voir le certificat
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>



<!-- Veille Informatique -->
<section id="veille" class="container text-center">
    <div class="container">
        <div class="section-title">
            <h2>Veille Informatique</h2>
            <p>Mes sources pour rester informé et développer mes compétences</p><br>
        </div>

        <div class="veille-grid">
            <!-- Carte Reddit -->
            <div class="veille-card">
                <img src="Images/Logo_Reddit.png" alt="Reddit">
                <div class="veille-content">
                    <h3>Reddit</h3>
                    <p>Une communauté active et des forums pour suivre les dernières tendances IT.</p>
                    <a href="https://www.reddit.com/r/sysadmin/" target="_blank" class="btn-veille">Visiter</a>
                </div>
            </div>

            <!-- Carte X (Twitter) -->
            <div class="veille-card">
                <img src="Images/Logo_Twitter.jpg" alt="Twitter/X">
                <div class="veille-content">
                    <h3>X (Twitter)</h3>
                    <p>Suivi des experts IT, des actualités et des tendances tech.</p>
                    <a href="https://twitter.com" target="_blank" class="btn-veille">Visiter</a>
                </div>
            </div>

            <!-- Carte LinkedIn -->
            <div class="veille-card">
                <img src="Images/Logo_Link.jpg" alt="LinkedIn">
                <div class="veille-content">
                    <h3>LinkedIn</h3>
                    <p>Réseautage professionnel et partage de connaissances IT.</p>
                    <a href="https://www.linkedin.com" target="_blank" class="btn-veille">Visiter</a>
                </div>
            </div>

            <!-- Carte IT Connect -->
            <div class="veille-card">
                <img src="Images/Logo_ITC.png" alt="IT Connect">
                <div class="veille-content">
                    <h3>IT Connect</h3>
                    <p>Articles techniques et tutoriels sur l'administration IT.</p>
                    <a href="https://www.it-connect.fr/" target="_blank" class="btn-veille">Visiter</a>
                </div>
            </div>
        </div>
    </div>
</section>





<!--Contact-->
<section id="contact" class="container text-center">
    <div class="container">
        <div class="section-title">
            <h2>Contact</h2>
        </div>

        <div class="contact-info">
            <p>
                <i class="fas fa-envelope"></i>
                <a href="mailto:lukasosori@gmail.com">lukasosori@gmail.com</a>
            </p>
            <p>
                <i class="fas fa-phone"></i>
                <a href="tel:+330695743962">+33 06 95 74 39 62</a>
            </p>
        </div>
        

        <!-- Formulaire de contact -->
        <form class="contact-form">
            <input type="text" name="name" placeholder="Votre nom" required>
            <input type="email" name="email" placeholder="Votre email" required>
            <textarea name="message" placeholder="Votre message" required></textarea>
            <button type="submit" class="btn-contact">Envoyer</button>
        </form>

        <!-- Bouton Télécharger CV -->
        <a href="Images/CV_OSORIO_V7.pdf" download class="btn-cv">
            <i class="fas fa-file-download"></i> Télécharger mon CV
        </a>
    </div>
</section>


    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2024 Lukas OSORIO. Tous droits réservés.</p>
    </footer>
    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
