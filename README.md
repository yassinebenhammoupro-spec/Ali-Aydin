<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><span class="lang-en">Op. Dr. Ali AYDIN - Urology & Andrology Specialist</span><span class="lang-fr hidden">Op. Dr. Ali AYDIN - Spécialiste en Urologie et Andrologie</span><span class="lang-tr hidden">Op. Dr. Ali AYDIN - Üroloji ve Androloji Uzmanı</span></title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Font Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f9fc;
        }
        .section-heading {
            border-left: 6px solid #0056b3;
            padding-left: 1rem;
            margin-bottom: 2rem;
            color: #1f2937;
        }
        .card-shadow {
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
        }
        .primary-color {
            color: #0056b3;
        }
        .bg-primary-color {
            background-color: #0056b3;
        }
        /* Hide all language content by default */
        .lang-en.hidden, .lang-fr.hidden, .lang-tr.hidden {
            display: none !important;
        }
        /* Flag styling */
        .flag-button {
            cursor: pointer;
            padding: 0.5rem;
            border-radius: 0.5rem;
            transition: transform 0.1s ease-in-out;
            /* New styles for text buttons */
            font-weight: 600;
            font-size: 0.875rem;
            line-height: 1.25rem;
            min-width: 2.5rem; /* 40px */
            text-align: center;
            border: 1px solid #e5e7eb; /* light gray border */
            background-color: #ffffff; /* white bg */
            color: #374151; /* gray text */
        }
        .flag-button:hover {
            transform: scale(1.05);
            background-color: #f9fafb; /* light gray hover */
        }
        .flag-button.active {
            box-shadow: 0 0 0 3px #0056b3, 0 0 0 5px #fff;
            /* New active styles */
            background-color: #0056b3;
            color: #ffffff;
            border-color: #0056b3;
        }
    </style>
</head>
<body class="text-gray-700">

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-50 bg-white shadow-lg">
        <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <a href="#home" class="flex items-center space-x-2">
                <!-- Branded Logo SVG -->
                <svg class="w-8 h-8 primary-color" viewBox="0 0 200 200" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                    <path d="M100 10 L190 190 L170 190 L100 50 L30 190 L10 190 Z"/>
                    <path d="M100 130 L130 190 L70 190 Z" fill="white"/>
                </svg>
                <span class="text-2xl font-bold primary-color">Op. Dr. Ali AYDIN</span>
            </a>

            <!-- Desktop Menu -->
            <div class="hidden md:flex items-center space-x-6 text-sm font-medium">
                <a href="#career" class="hover:primary-color transition duration-200"><span class="lang-en">Career</span><span class="lang-fr hidden">Carrière</span><span class="lang-tr hidden">Kariyer</span></a>
                <a href="#erectile-dysfunction" class="hover:primary-color transition duration-200"><span class="lang-en">Erectile Dysfunction</span><span class="lang-fr hidden">Dysfonction Érectile</span><span class="lang-tr hidden">Sertleşme Bozukluğu</span></a>
                <a href="#premature-ejaculation" class="hover:primary-color transition duration-200"><span class="lang-en">Premature Ejaculation</span><span class="lang-fr hidden">Éjaculation Précoce</span><span class="lang-tr hidden">Erken Boşalma</span></a>
                <a href="#peyronies-disease" class="hover:primary-color transition duration-200"><span class="lang-en">Peyronie's Disease</span><span class="lang-fr hidden">Maladie de La Peyronie</span><span class="lang-tr hidden">Peyronie Hastalığı</span></a>
                <a href="#llm-explainer" class="hover:primary-color transition duration-200"><span class="lang-en">AI Explainer</span><span class="lang-fr hidden">Explicateur IA</span><span class="lang-tr hidden">Yapay Zeka Açıklayıcı</span></a>
                <a href="#contact" class="px-4 py-2 bg-primary-color text-white rounded-lg shadow-md hover:bg-blue-700 transition duration-200">
                    <span class="lang-en">Contact Us</span><span class="lang-fr hidden">Contactez-nous</span><span class="lang-tr hidden">Bize Ulaşın</span>
                </a>
            </div>

            <!-- Language Switcher and Mobile Button -->
            <div class="flex items-center space-x-4">
                <div class="flex space-x-2">
                    <!-- English Button -->
                    <button id="lang-en-btn" class="flag-button" data-lang="en">
                        EN
                    </button>
                    <!-- French Button -->
                    <button id="lang-fr-btn" class="flag-button" data-lang="fr">
                        FR
                    </button>
                    <!-- Turkish Button -->
                    <button id="lang-tr-btn" class="flag-button" data-lang="tr">
                        TR
                    </button>
                </div>

                <!-- Mobile Menu Button -->
                <button id="mobile-menu-button" class="md:hidden p-2 text-gray-700 hover:text-blue-600 rounded-lg">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
                </button>
            </div>

        </nav>
        <!-- Mobile Menu Dropdown -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-inner pb-2">
            <a href="#career" class="block px-4 py-2 text-sm hover:bg-gray-100 transition duration-200"><span class="lang-en">Career Overview</span><span class="lang-fr hidden">Aperçu de la Carrière</span><span class="lang-tr hidden">Kariyer Özeti</span></a>
            <a href="#erectile-dysfunction" class="block px-4 py-2 text-sm hover:bg-gray-100 transition duration-200"><span class="lang-en">Erectile Dysfunction</span><span class="lang-fr hidden">Dysfonction Érectile</span><span class="lang-tr hidden">Sertleşme Bozukluğu</span></a>
            <a href="#premature-ejaculation" class="block px-4 py-2 text-sm hover:bg-gray-100 transition duration-200"><span class="lang-en">Premature Ejaculation</span><span class="lang-fr hidden">Éjaculation Précoce</span><span class="lang-tr hidden">Erken Boşalma</span></a>
            <a href="#peyronies-disease" class="block px-4 py-2 text-sm hover:bg-gray-100 transition duration-200"><span class="lang-en">Peyronie's Disease</span><span class="lang-fr hidden">Maladie de La Peyronie</span><span class="lang-tr hidden">Peyronie Hastalığı</span></a>
            <a href="#llm-explainer" class="block px-4 py-2 text-sm hover:bg-gray-100 transition duration-200"><span class="lang-en">AI Explainer</span><span class="lang-fr hidden">Explicateur IA</span><span class="lang-tr hidden">Yapay Zeka Açıklayıcı</span></a>
            <a href="#contact" class="block px-4 py-2 text-sm hover:bg-gray-100 transition duration-200"><span class="lang-en">Contact Us</span><span class="lang-fr hidden">Contactez-nous</span><span class="lang-tr hidden">Bize Ulaşın</span></a>
        </div>
    </header>

    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10">
        <!-- Hero Section -->
        <section id="home" class="py-16 md:py-24 bg-white rounded-xl card-shadow mb-16">
            <div class="md:flex md:items-center md:space-x-12">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold primary-color leading-tight">
                        Op. Dr. Ali AYDIN
                    </h1>
                    <h2 class="text-2xl sm:text-3xl text-gray-500 mt-2 font-light">
                        <span class="lang-en">Urology and Andrology Specialist</span>
                        <span class="lang-fr hidden">Spécialiste en Urologie et Andrologie</span>
                        <span class="lang-tr hidden">Üroloji ve Androloji Uzmanı</span>
                    </h2>
                    <p class="mt-6 text-lg text-gray-600">
                        <span class="lang-en">Offering specialized applications and advanced therapies for urological health, focusing on minimally invasive and patient-centered treatment options. Your health is our foremost concern.</span>
                        <span class="lang-fr hidden">Offrant des applications spécialisées et des thérapies avancées pour la santé urologique, axées sur des options de traitement peu invasives et centrées sur le patient. Votre santé est notre principale préoccupation.</span>
                        <span class="lang-tr hidden">Ürolojik sağlık için minimal invaziv ve hasta merkezli tedavi seçeneklerine odaklanarak uzmanlaşmış uygulamalar ve gelişmiş terapiler sunuyoruz. Sağlığınız bizim öncelikli endişemizdir.</span>
                    </p>
                    <div class="mt-8">
                        <a href="#contact" class="inline-block px-8 py-3 bg-primary-color text-white font-semibold rounded-full shadow-lg hover:bg-blue-700 transition duration-300 transform hover:scale-105">
                            <span class="lang-en">Book an Appointment</span>
                            <span class="lang-fr hidden">Prendre Rendez-vous</span>
                            <span class="lang-tr hidden">Randevu Alın</span>
                        </a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center items-center">
                    <!-- Branded Logo in Hero Section -->
                    <div class="w-48 h-48 sm:w-64 sm:h-64 bg-gray-200 rounded-full flex items-center justify-center border-4 border-primary-color p-8">
                         <svg class="w-full h-full primary-color" viewBox="0 0 200 200" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                            <path d="M100 10 L190 190 L170 190 L100 50 L30 190 L10 190 Z"/>
                            <path d="M100 130 L130 190 L70 190 Z" fill="#f7f9fc"/>
                        </svg>
                    </div>
                </div>
            </div>
        </section>

        <!-- Career Overview Section -->
        <section id="career" class="py-12 bg-white rounded-xl card-shadow p-6 sm:p-10 mb-16">
            <h3 class="text-3xl font-bold section-heading">
                <span class="lang-en">Education and Career Overview</span>
                <span class="lang-fr hidden">Aperçu de la Formation et de la Carrière</span>
                <span class="lang-tr hidden">Eğitim ve Kariyer Özeti</span>
            </h3>
            <div class="relative">
                <!-- Vertical Line -->
                <div class="absolute left-3 top-0 bottom-0 w-0.5 bg-gray-200 hidden sm:block"></div>

                <!-- Timeline Items -->
                <div class="space-y-8">
                    <div class="relative pl-6 sm:pl-10 pb-8">
                        <span class="absolute left-0 top-1.5 w-6 h-6 bg-primary-color rounded-full border-4 border-white hidden sm:block"></span>
                        <p class="text-sm font-semibold primary-color mb-1">1994-2001</p>
                        <h4 class="text-xl font-bold text-gray-800">
                            <span class="lang-en">Faculty of Medicine</span>
                            <span class="lang-fr hidden">Faculté de Médecine</span>
                            <span class="lang-tr hidden">Tıp Fakültesi</span>
                        </h4>
                        <p class="text-gray-600">
                            <span class="lang-en">Istanbul University Cerrahpaşa Faculty of Medicine</span>
                            <span class="lang-fr hidden">Faculté de Médecine Cerrahpaşa de l'Université d'Istanbul</span>
                            <span class="lang-tr hidden">İstanbul Üniversitesi Cerrahpaşa Tıp Fakültesi</span>
                        </p>
                    </div>
                    <div class="relative pl-6 sm:pl-10 pb-8">
                        <span class="absolute left-0 top-1.5 w-6 h-6 bg-primary-color rounded-full border-4 border-white hidden sm:block"></span>
                        <p class="text-sm font-semibold primary-color mb-1">2006-2012</p>
                        <h4 class="text-xl font-bold text-gray-800">
                            <span class="lang-en">Urological Specialization</span>
                            <span class="lang-fr hidden">Spécialisation en Urologie</span>
                            <span class="lang-tr hidden">Üroloji İhtisası</span>
                        </h4>
                        <p class="text-gray-600">
                            <span class="lang-en">Fatih Sultan Mehmet Training and Research Hospital Urology Department</span>
                            <span class="lang-fr hidden">Département d'Urologie de l'Hôpital de Formation et de Recherche Fatih Sultan Mehmet</span>
                            <span class="lang-tr hidden">Fatih Sultan Mehmet Eğitim ve Araştırma Hastanesi Üroloji Bölümü</span>
                        </p>
                    </div>
                    <div class="relative pl-6 sm:pl-10 pb-8">
                        <span class="absolute left-0 top-1.5 w-6 h-6 bg-primary-color rounded-full border-4 border-white hidden sm:block"></span>
                        <p class="text-sm font-semibold primary-color mb-1">2012-2015</p>
                        <h4 class="text-xl font-bold text-gray-800">
                            <span class="lang-en">Urologist (State Hospitals)</span>
                            <span class="lang-fr hidden">Urologue (Hôpitaux d'État)</span>
                            <span class="lang-tr hidden">Ürolog (Devlet Hastaneleri)</span>
                        </h4>
                        <p class="text-gray-600">
                            <span class="lang-en">Urology Specialist at Niğde State Hospital and Beykoz State Hospital</span>
                            <span class="lang-fr hidden">Spécialiste en Urologie à l'Hôpital d'État de Niğde et à l'Hôpital d'État de Beykoz</span>
                            <span class="lang-tr hidden">Niğde Devlet Hastanesi ve Beykoz Devlet Hastanesi Üroloji Uzmanı</span>
                        </p>
                    </div>
                    <div class="relative pl-6 sm:pl-10 pb-8">
                        <span class="absolute left-0 top-1.5 w-6 h-6 bg-primary-color rounded-full border-4 border-white hidden sm:block"></span>
                        <p class="text-sm font-semibold primary-color mb-1">2016 - <span class="lang-en">Present</span><span class="lang-fr hidden">Aujourd'hui</span><span class="lang-tr hidden">Günümüz</span></p>
                        <h4 class="text-xl font-bold text-gray-800">
                            <span class="lang-en">Private Practice</span>
                            <span class="lang-fr hidden">Pratique Privée</span>
                            <span class="lang-tr hidden">Özel Muayenehane</span>
                        </h4>
                        <p class="text-gray-600">
                            <span class="lang-en">Specialized applications and therapies at Aydın Clinic</span>
                            <span class="lang-fr hidden">Applications et thérapies spécialisées à la Clinique Aydın</span>
                            <span class="lang-tr hidden">Aydın Kliniği'nde uzmanlaşmış uygulamalar ve terapiler</span>
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Treatments Section -->
        <section id="treatments" class="py-12">
            <h3 class="text-4xl font-extrabold text-center primary-color mb-10">
                <span class="lang-en">Specialized Urological Treatments</span>
                <span class="lang-fr hidden">Traitements Urologiques Spécialisés</span>
                <span class="lang-tr hidden">Uzmanlaşmış Ürolojik Tedaviler</span>
            </h3>

            <!-- Erectile Dysfunction -->
            <div id="erectile-dysfunction" class="bg-white rounded-xl card-shadow p-6 sm:p-10 mb-12">
                <h4 class="text-2xl sm:text-3xl font-bold primary-color mb-6">
                    <span class="lang-en">Erectile Dysfunction Therapies</span>
                    <span class="lang-fr hidden">Thérapies contre la Dysfonction Érectile</span>
                    <span class="lang-tr hidden">Sertleşme Bozukluğu Tedavileri</span>
                </h4>
                <div class="grid md:grid-cols-2 gap-8">
                    <!-- ESWT Shockwave Therapy -->
                    <div class="bg-gray-50 p-6 rounded-lg border border-blue-100">
                        <h5 class="text-xl font-semibold mb-3 text-gray-800">
                            <span class="lang-en">ESWT Shockwave Therapy</span>
                            <span class="lang-fr hidden">Thérapie par Ondes de Choc ESWT</span>
                            <span class="lang-tr hidden">ESWT Şok Dalga Tedavisi</span>
                        </h5>
                        <p class="mb-4 text-sm text-gray-600">
                            <span class="lang-en">**Application Domains:** Erectile Dysfunction, Peyronie's Disease, Chronic Prostatitis.</span>
                            <span class="lang-fr hidden">**Domaines d'Application :** Dysfonction Érectile, Maladie de La Peyronie, Prostatite Chronique.</span>
                            <span class="lang-tr hidden">**Uygulama Alanları:** Sertleşme Bozukluğu, Peyronie Hastalığı, Kronik Prostatit.</span>
                        </p>
                        <ul class="space-y-1 text-sm text-gray-600 list-disc list-inside">
                            <li><span class="lang-en">Medication-free therapy</span><span class="lang-fr hidden">Thérapie sans médicaments</span><span class="lang-tr hidden">İlaçsız tedavi</span></li>
                            <li><span class="lang-en">Minimally invasive</span><span class="lang-fr hidden">Minimally invasive</span><span class="lang-tr hidden">Minimal invaziv</span></li>
                            <li><span class="lang-en">Brief session duration</span><span class="lang-fr hidden">Courte durée de session</span><span class="lang-tr hidden">Kısa seans süresi</span></li>
                            <li><span class="lang-en">No anesthesia necessary</span><span class="lang-fr hidden">Aucune anesthésie nécessaire</span><span class="lang-tr hidden">Anestezi gerektirmez</span></li>
                        </ul>
                    </div>

                    <!-- Stem Cell Applications -->
                    <div class="bg-gray-50 p-6 rounded-lg border border-blue-100">
                        <h5 class="text-xl font-semibold mb-3 text-gray-800">
                            <span class="lang-en">Stem Cell Applications in Penile Therapy</span>
                            <span class="lang-fr hidden">Applications de Cellules Souches en Thérapie Pénienne</span>
                            <span class="lang-tr hidden">Penil Tedavide Kök Hücre Uygulamaları</span>
                        </h5>
                        <p class="mb-4 text-sm text-gray-600">
                            <span class="lang-en">**Procedure:** Micrograft extraction (behind the ear) $\rightarrow$ Tissue preparation $\rightarrow$ Pain-free application to the penis.</span>
                            <span class="lang-fr hidden">**Procédure :** Extraction de microgreffe (derrière l'oreille) $\rightarrow$ Préparation des tissus $\rightarrow$ Application sans douleur au pénis.</span>
                            <span class="lang-tr hidden">**Prosedür:** Kulak arkasından mikrogreft alımı $\rightarrow$ Doku hazırlama $\rightarrow$ Penise ağrısız uygulama.</span>
                        </p>
                        <ul class="space-y-1 text-sm text-gray-600 list-disc list-inside">
                            <li><span class="lang-en">Brief application duration</span><span class="lang-fr hidden">Courte durée d'application</span><span class="lang-tr hidden">Kısa uygulama süresi</span></li>
                            <li><span class="lang-en">Regional anesthesia (pain-free)</span><span class="lang-fr hidden">Anesthésie régionale (sans douleur)</span><span class="lang-tr hidden">Bölgesel anestezi (ağrısız)</span></li>
                            <li><span class="lang-en">Resumption of daily activities on the same day</span><span class="lang-fr hidden">Reprise des activités quotidiennes le jour même</span><span class="lang-tr hidden">Aynı gün günlük aktivitelere devam edebilme</span></li>
                        </ul>
                    </div>
                    
                    <!-- Exosome Utilization -->
                    <div class="md:col-span-2 bg-gray-50 p-6 rounded-lg border border-blue-100">
                        <h5 class="text-xl font-semibold mb-3 text-gray-800">
                            <span class="lang-en">Exosome Utilization in Penile Therapy</span>
                            <span class="lang-fr hidden">Utilisation d'Exosomes en Thérapie Pénienne</span>
                            <span class="lang-tr hidden">Penil Tedavide Eksozom Kullanımı</span>
                        </h5>
                        <p class="mb-4 text-sm text-gray-600">
                            <span class="lang-en">Nanoscopic vesicles isolated and purified from platelet-derived plasma, which regulate cell renewal and tissue repair.</span>
                            <span class="lang-fr hidden">Vésicules nanoscopiques isolées et purifiées à partir de plasma dérivé de plaquettes, qui régulent le renouvellement cellulaire et la réparation tissulaire.</span>
                            <span class="lang-tr hidden">Hücre yenilenmesini ve doku onarımını düzenleyen, trombosit türevli plazmadan izole ve saflaştırılmış nanoskobik veziküller.</span>
                        </p>
                        <ul class="space-y-1 text-sm text-gray-600 list-disc list-inside">
                            <li><span class="lang-en">Brief application period</span><span class="lang-fr hidden">Courte période d'application</span><span class="lang-tr hidden">Kısa uygulama süresi</span></li>
                            <li><span class="lang-en">Pain-free administration using local anesthesia</span><span class="lang-fr hidden">Administration sans douleur utilisant une anesthésie locale</span><span class="lang-tr hidden">Lokal anestezi ile ağrısız uygulama</span></li>
                            <li><span class="lang-en">Does not necessitate general anesthesia</span><span class="lang-fr hidden">Ne nécessite pas d'anesthésie générale</span><span class="lang-tr hidden">Genel anestezi gerektirmez</span></li>
                            <li><span class="lang-en">Ability to maintain daily routines on the same day</span><span class="lang-fr hidden">Possibilité de maintenir les routines quotidiennes le jour même</span><span class="lang-tr hidden">Aynı gün günlük rutinlere devam edebilme</span></li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Premature Ejaculation -->
            <div id="premature-ejaculation" class="bg-white rounded-xl card-shadow p-6 sm:p-10 mb-12">
                <h4 class="text-2xl sm:text-3xl font-bold primary-color mb-6">
                    <span class="lang-en">Premature Ejaculation Therapy</span>
                    <span class="lang-fr hidden">Thérapie contre l'Éjaculation Précoce</span>
                    <span class="lang-tr hidden">Erken Boşalma Tedavisi</span>
                </h4>
                <div class="grid md:grid-cols-2 gap-8 items-center">
                    <div>
                        <h5 class="text-xl font-semibold mb-3 text-gray-800">
                            <span class="lang-en">Botulinum Toxin (Botox) Administration to the Glans Penis</span>
                            <span class="lang-fr hidden">Administration de Toxine Botulique (Botox) au Gland du Pénis</span>
                            <span class="lang-tr hidden">Penis Başına Botulinum Toksini (Botoks) Uygulaması</span>
                        </h5>
                        <p class="mb-4 text-sm text-gray-600">
                            <span class="lang-en">The toxin is injected into the glans penis area to treat premature ejaculation issues.</span>
                            <span class="lang-fr hidden">La toxine est injectée dans la zone du gland du pénis pour traiter les problèmes d'éjaculation précoce.</span>
                            <span class="lang-tr hidden">Toksin, erken boşalma sorunlarını tedavi etmek amacıyla penis başına enjekte edilir.</span>
                        </p>
                        <p class="font-semibold text-gray-700 mt-4">
                            <span class="lang-en">Operational Mechanism:</span>
                            <span class="lang-fr hidden">Mécanisme Opérationnel :</span>
                            <span class="lang-tr hidden">Operasyon Mekanizması:</span>
                        </p>
                        <ul class="space-y-1 text-sm text-gray-600 list-disc list-inside">
                            <li><span class="lang-en">Reduces nerve ending hypersensitivity.</span><span class="lang-fr hidden">Réduit l'hypersensibilité des terminaisons nerveuses.</span><span class="lang-tr hidden">Sinir ucu aşırı duyarlılığını azaltır.</span></li>
                            <li><span class="lang-en">Prolongs ejaculation duration.</span><span class="lang-fr hidden">Prolonge la durée de l'éjaculation.</span><span class="lang-tr hidden">Boşalma süresini uzatır.</span></li>
                            <li><span class="lang-en">Enhances ejaculatory control.</span><span class="lang-fr hidden">Améliore le contrôle de l'éjaculation.</span><span class="lang-tr hidden">Boşalma kontrolünü artırır.</span></li>
                        </ul>
                    </div>
                    <div class="bg-gray-50 p-6 rounded-lg border border-blue-100">
                        <p class="font-semibold text-gray-800 mb-2">
                            <span class="lang-en">Advantages:</span>
                            <span class="lang-fr hidden">Avantages :</span>
                            <span class="lang-tr hidden">Avantajlar:</span>
                        </p>
                        <ul class="space-y-1 text-sm text-gray-600 list-disc list-inside">
                            <li><span class="lang-en">Brief application duration</span><span class="lang-fr hidden">Courte durée d'application</span><span class="lang-tr hidden">Kısa uygulama süresi</span></li>
                            <li><span class="lang-en">Pain-free procedure with local anesthesia</span><span class="lang-fr hidden">Procédure sans douleur avec anesthésie locale</span><span class="lang-tr hidden">Lokal anestezi ile ağrısız prosedür</span></li>
                            <li><span class="lang-en">No requirement for general anesthesia</span><span class="lang-fr hidden">Aucune exigence d'anesthésie générale</span><span class="lang-tr hidden">Genel anestezi gerektirmez</span></li>
                            <li><span class="lang-en">Ability to resume daily activities on the same day</span><span class="lang-fr hidden">Possibilité de reprendre les activités quotidiennes le jour même</span><span class="lang-tr hidden">Aynı gün günlük aktivitelere devam edebilme</span></li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Peyronie's Disease -->
            <div id="peyronies-disease" class="bg-white rounded-xl card-shadow p-6 sm:p-10 mb-12">
                <h4 class="text-2xl sm:text-3xl font-bold primary-color mb-6">
                    <span class="lang-en">Peyronie's Disease Management</span>
                    <span class="lang-fr hidden">Gestion de la Maladie de La Peyronie</span>
                    <span class="lang-tr hidden">Peyronie Hastalığı Yönetimi</span>
                </h4>
                <div class="grid md:grid-cols-2 gap-8">
                    <!-- ESWT Shockwave Therapy for Peyronie's -->
                    <div class="bg-gray-50 p-6 rounded-lg border border-blue-100">
                        <h5 class="text-xl font-semibold mb-3 text-gray-800">
                            <span class="lang-en">ESWT Shockwave Therapy</span>
                            <span class="lang-fr hidden">Thérapie par Ondes de Choc ESWT</span>
                            <span class="lang-tr hidden">ESWT Şok Dalga Tedavisi</span>
                        </h5>
                        <p class="mb-4 text-sm text-gray-600">
                            <span class="lang-en">Non-invasive shock wave therapy technique for addressing penile curvature.</span>
                            <span class="lang-fr hidden">Technique de thérapie par ondes de choc non invasive pour traiter la courbure du pénis.</span>
                            <span class="lang-tr hidden">Penil eğriliği gidermeye yönelik non-invaziv şok dalgası terapi tekniği.</span>
                        </p>
                        <ul class="space-y-1 text-sm text-gray-600 list-disc list-inside">
                            <li><span class="lang-en">Non-pharmacological and non-surgical treatment</span><span class="lang-fr hidden">Traitement non pharmacologique et non chirurgical</span><span class="lang-tr hidden">İlaçsız ve cerrahi olmayan tedavi</span></li>
                            <li><span class="lang-en">Brief session duration</span><span class="lang-fr hidden">Courte durée de session</span><span class="lang-tr hidden">Kısa seans süresi</span></li>
                            <li><span class="lang-en">Does not necessitate anesthesia</span><span class="lang-fr hidden">Ne nécessite pas d'anesthésie</span><span class="lang-tr hidden">Anestezi gerektirmez</span></li>
                        </ul>
                    </div>

                    <!-- Intraplate Collagenase Enzyme Administration -->
                    <div class="bg-gray-50 p-6 rounded-lg border border-blue-100">
                        <h5 class="text-xl font-semibold mb-3 text-gray-800">
                            <span class="lang-en">Intraplate Collagenase Enzyme Administration</span>
                            <span class="lang-fr hidden">Administration d'Enzyme Collagénase Intra-plaque</span>
                            <span class="lang-tr hidden">Plak İçi Kolajenaz Enzim Uygulaması</span>
                        </h5>
                        <p class="mb-4 text-sm text-gray-600">
                            <span class="lang-en">A single injection that dissolves the plaque, correcting the curvature by breaking down Peyronie's plaque.</span>
                            <span class="lang-fr hidden">Une seule injection qui dissout la plaque, corrigeant la courbure en décomposant la plaque de La Peyronie.</span>
                            <span class="lang-tr hidden">Plağı çözen, Peyronie plağını parçalayarak eğriliği düzelten tek bir enjeksiyon.</span>
                        </p>
                        <ul class="space-y-1 text-sm text-gray-600 list-disc list-inside">
                            <li><span class="lang-en">Brief application period</span><span class="lang-fr hidden">Courte période d'application</span><span class="lang-tr hidden">Kısa uygulama süresi</span></li>
                            <li><span class="lang-en">Pain-free administration using local anesthesia</span><span class="lang-fr hidden">Administration sans douleur utilisant une anesthésie locale</span><span class="lang-tr hidden">Lokal anestezi ile ağrısız uygulama</span></li>
                            <li><span class="lang-en">The chance to maintain daily routines on the same day</span><span class="lang-fr hidden">La possibilité de maintenir les routines quotidiennes le jour même</span><span class="lang-tr hidden">Aynı gün günlük rutinlere devam edebilme</span></li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Penis Enlargement -->
            <div id="penis-enlargement" class="bg-white rounded-xl card-shadow p-6 sm:p-10 mb-16">
                <h4 class="text-2xl sm:text-3xl font-bold primary-color mb-6">
                    <span class="lang-en">Penis Enlargement through Non-Surgical Enzyme Therapy</span>
                    <span class="lang-fr hidden">Augmentation Pénienne par Thérapie Enzymatique Non Chirurgicale</span>
                    <span class="lang-tr hidden">Cerrahi Olmayan Enzim Tedavisi ile Penis Büyütme</span>
                </h4>
                <div class="grid md:grid-cols-2 gap-8 items-center">
                    <div>
                        <h5 class="text-xl font-semibold mb-3 text-gray-800">
                            <span class="lang-en">Lipase Enzyme Injection</span>
                            <span class="lang-fr hidden">Injection d'Enzyme Lipase</span>
                            <span class="lang-tr hidden">Lipaz Enzimi Enjeksiyonu</span>
                        </h5>
                        <p class="mb-4 text-sm text-gray-600">
                            <span class="lang-en">A non-surgical enzymatic approach to penile enlargement, yielding effective results after a single session.</span>
                            <span class="lang-fr hidden">Une approche enzymatique non chirurgicale de l'augmentation pénienne, donnant des résultats efficaces après une seule session.</span>
                            <span class="lang-tr hidden">Tek bir seans sonrasında etkili sonuçlar veren, penis büyütmede cerrahi olmayan enzimatik bir yaklaşım.</span>
                        </p>
                    </div>
                    <div class="bg-gray-50 p-6 rounded-lg border border-blue-100">
                        <p class="font-semibold text-gray-800 mb-2">
                            <span class="lang-en">Advantages:</span>
                            <span class="lang-fr hidden">Avantages :</span>
                            <span class="lang-tr hidden">Avantajlar:</span>
                        </p>
                        <ul class="space-y-1 text-sm text-gray-600 list-disc list-inside">
                            <li><span class="lang-en">Brief application duration</span><span class="lang-fr hidden">Courte durée d'application</span><span class="lang-tr hidden">Kısa uygulama süresi</span></li>
                            <li><span class="lang-en">Pain-free procedure with local anesthesia</span><span class="lang-fr hidden">Procédure sans douleur avec anesthésie locale</span><span class="lang-tr hidden">Lokal anestezi ile ağrısız prosedür</span></li>
                            <li><span class="lang-en">No requirement for general anesthesia</span><span class="lang-fr hidden">Aucune exigence d'anesthésie générale</span><span class="lang-tr hidden">Genel anestezi gerektirmez</span></li>
                            <li><span class="lang-en">Ability to resume daily activities on the same day</span><span class="lang-fr hidden">Possibilité de reprendre les activités quotidiennes le jour MêME</span><span class="lang-tr hidden">Aynı gün günlük aktivitelere devam edebilme</span></li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Gemini LLM Feature: Medical Explainer -->
        <section id="llm-explainer" class="py-12 bg-gray-100 rounded-xl card-shadow p-6 sm:p-10 mb-16">
            <h3 class="text-3xl font-bold primary-color mb-6">
                <span class="lang-en">Medical Terminology Explainer ✨</span>
                <span class="lang-fr hidden">Explicateur de Terminologie Médicale ✨</span>
                <span class="lang-tr hidden">Tıbbi Terminoloji Açıklayıcı ✨</span>
            </h3>
            <p class="text-lg text-gray-700 mb-6">
                <span class="lang-en">Need a complex medical term from this site or elsewhere simplified? Type it below, and our AI assistant will provide an easy-to-understand explanation, grounded with current information. The response will be in the language currently selected on the page.</span>
                <span class="lang-fr hidden">Besoin d'un terme médical complexe de ce site ou d'ailleurs simplifié ? Tapez-le ci-dessous, et notre assistant IA fournira une explication facile à comprendre, étayée par des informations actuelles. La réponse sera dans la language actuellement sélectionnée sur la page.</span>
                <span class="lang-tr hidden">Bu sitedeki veya başka bir yerdeki karmaşık bir tıbbi terimin basitleştirilmesine mi ihtiyacınız var? Aşağıya yazın, yapay zeka asistanımız güncel bilgilerle desteklenmiş, kolay anlaşılır bir açıklama sunacaktır. Cevap, sayfada seçili olan dilde olacaktır.</span>
            </p>

            <div class="space-y-4">
                <input type="text" id="term-input" 
                       placeholder="e.g., Exosome Utilization, Chronic Prostatitis, Ureter | Örn: Eksozom Kullanımı, Kronik Prostatit, Üreter" 
                       class="w-full p-3 border border-gray-300 rounded-lg focus:ring-blue-500 focus:border-blue-500 transition duration-150" aria-label="Medical term input">
                
                <button id="explain-button" class="w-full md:w-auto px-6 py-3 bg-green-600 text-white font-semibold rounded-lg shadow-md hover:bg-green-700 transition duration-200 flex items-center justify-center disabled:opacity-50" aria-controls="explanation-output" aria-live="polite">
                    <svg class="w-5 h-5 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.103a2.404 2.404 0 00-3.41 0L12 8.59l-2.208 2.208-2.208-2.208a2.404 2.404 0 00-3.41 3.41l4.208 4.208a2.404 2.404 0 003.41 0l4.208-4.208a2.404 2.404 0 000-3.41z"></path></svg>
                    <span class="lang-en">✨ Explain this Term</span>
                    <span class="lang-fr hidden">✨ Expliquer ce Terme</span>
                    <span class="lang-tr hidden">✨ Bu Terimi Açıkla</span>
                </button>
            </div>

            <div id="explanation-output" class="mt-6 p-4 bg-white rounded-lg border border-gray-200 hidden">
                <h4 class="text-xl font-bold primary-color mb-2">
                    <span class="lang-en">Explanation:</span>
                    <span class="lang-fr hidden">Explication :</span>
                    <span class="lang-tr hidden">Açıklama:</span>
                </h4>
                <p id="explanation-text" class="text-gray-700 leading-relaxed"></p>
                <div id="explanation-sources" class="text-sm mt-4 pt-2 border-t border-gray-100 hidden">
                    <p class="font-semibold text-gray-500">
                        <span class="lang-en">Sources (for grounding):</span>
                        <span class="lang-fr hidden">Sources (pour étayage) :</span>
                        <span class="lang-tr hidden">Kaynaklar (doğrulama için):</span>
                    </p>
                    <ul id="source-list" class="list-disc pl-5 text-gray-500 space-y-1"></ul>
                </div>
            </div>

            <div id="loading-indicator" class="mt-6 hidden flex items-center space-x-2 text-primary-color font-semibold">
                <svg class="animate-spin h-5 w-5 text-primary-color" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24">
                    <circle class="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" stroke-width="4"></circle>
                    <path class="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z"></path>
                </svg>
                <span class="lang-en">Analyzing term...</span>
                <span class="lang-fr hidden">Analyse du terme en cours...</span>
                <span class="lang-tr hidden">Terim analiz ediliyor...</span>
            </div>
            <p id="error-message" class="mt-4 text-red-500 font-semibold hidden"></p>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-12 bg-primary-color text-white rounded-xl card-shadow p-6 sm:p-10 mb-10">
            <h3 class="text-3xl font-bold mb-6 border-b border-blue-300 pb-3">
                <span class="lang-en">Contact Us</span>
                <span class="lang-fr hidden">Contactez-nous</span>
                <span class="lang-tr hidden">Bize Ulaşın</span>
            </h3>
            <p class="text-lg mb-6">
                <span class="lang-en">We invite you to reach out with any inquiries or to schedule an appointment. Your health is our foremost concern.</span>
                <span class="lang-fr hidden">Nous vous invitons à nous contacter pour toute question ou pour prendre rendez-vous. Votre santé est notre principale préoccupation.</span>
                <span class="lang-tr hidden">Tüm sorularınız veya randevu almak için bize ulaşabilirsiniz. Sağlığınız bizim öncelikli endişemizdir.</span>
            </p>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="flex items-center space-x-3">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                    <p class="font-semibold"><span class="lang-en">PHONE</span><span class="lang-fr hidden">TÉLÉPHONE</span><span class="lang-tr hidden">TELEFON</span> : +90 (538) 935 70 72</p>
                </div>
                <div class="flex items-center space-x-3">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                    <p class="font-semibold"><span class="lang-en">E-MAIL</span><span class="lang-fr hidden">E-MAIL</span><span class="lang-tr hidden">E-POSTA</span> : info@opdraliaydin.com</p>
                </div>
                <div class="flex items-center space-x-3">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 21h7a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-2.414-2.414a1 1 0 00-.707-.293H10a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                    <p class="font-semibold"><span class="lang-en">WEBSITE</span><span class="lang-fr hidden">SITE WEB</span><span class="lang-tr hidden">WEB SİTESİ</span> : www.opdraliaydin.clinic</p>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white p-6 text-center text-sm">
        &copy; 2025 Op. Dr. Ali AYDIN. 
        <span class="lang-en">All rights reserved.</span>
        <span class="lang-fr hidden">Tous droits réservés.</span>
        <span class="lang-tr hidden">Tüm hakları saklıdır.</span>
    </footer>

    <script>
        // --- Language Switcher Logic ---
        let currentLang = 'en';

        // --- Element Definitions moved to the top to resolve ReferenceError ---
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        const termInput = document.getElementById('term-input');
        const explainButton = document.getElementById('explain-button');
        const explanationOutput = document.getElementById('explanation-output');
        const explanationText = document.getElementById('explanation-text');
        const explanationSources = document.getElementById('explanation-sources');
        const sourceList = document.getElementById('source-list');
        const loadingIndicator = document.getElementById('loading-indicator');
        const errorMessage = document.getElementById('error-message');


        // Translations for UI elements and AI system prompts (Added Turkish 'tr')
        const uiTranslations = {
            'en': {
                'error-term': 'Please enter a medical term to explain.',
                'error-api': 'An error occurred: [ERROR]. Please try again.',
                'system-prompt': "You are a friendly, knowledgeable, and professional medical educator. Your task is to take a complex medical term provided by the user and explain it in simple, easy-to-understand language suitable for a general audience. The explanation must be concise (max 3-4 sentences). Please respond in English.",
                'error-generation': 'Could not generate an explanation. Please try a different term.',
            },
            'fr': {
                'error-term': 'Veuillez entrer un terme médical à expliquer.',
                'error-api': 'Une erreur est survenue : [ERROR]. Veuillez réessayer.',
                'system-prompt': "Vous êtes un éducateur médical amical, compétent et professionnel. Votre tâche consiste à prendre un terme médical complexe fourni par l'utilisateur et à l'expliquer dans un langage simple et facile à comprendre, adapté à un public général. L'explication doit être concise (max 3-4 phrases). Veuillez répondre en français.",
                'error-generation': "Impossible de générer une explication. Veuillez essayer un autre terme.",
            },
            'tr': {
                'error-term': 'Lütfen açıklanacak bir tıbbi terim girin.',
                'error-api': 'Bir hata oluştu: [ERROR]. Lütfen tekrar deneyin.',
                'system-prompt': "Sen güler yüzlü, bilgili ve profesyonel bir tıp eğiticisisin. Görevin, kullanıcı tarafından sağlanan karmaşık bir tıbbi terimi, genel bir kitle için uygun, basit ve anlaşılır bir dille açıklamaktır. Açıklama kısa ve öz olmalıdır (maksimum 3-4 cümle). Lütfen Türkçe yanıt verin.",
                'error-generation': 'Açıklama oluşturulamadı. Lütfen farklı bir terim deneyin.',
            }
        };

        function setLanguage(lang) {
            currentLang = lang;
            
            // Toggle visibility of language-specific elements
            document.querySelectorAll('.lang-en').forEach(el => el.classList.toggle('hidden', lang !== 'en'));
            document.querySelectorAll('.lang-fr').forEach(el => el.classList.toggle('hidden', lang !== 'fr'));
            document.querySelectorAll('.lang-tr').forEach(el => el.classList.toggle('hidden', lang !== 'tr')); // Added Turkish

            // Update flag button active state
            document.querySelectorAll('.flag-button').forEach(btn => {
                btn.classList.remove('active');
            });
            document.getElementById(`lang-${lang}-btn`).classList.add('active');
            
            // Close mobile menu
            if (mobileMenu) {
                mobileMenu.classList.add('hidden');
            }
            
            // Clear previous AI output/errors when switching language
            if (explanationOutput) {
                explanationOutput.classList.add('hidden');
                errorMessage.classList.add('hidden');
                loadingIndicator.classList.add('hidden');
            }
        }

        // Initial language setting
        setLanguage('en'); 

        // Add event listeners for language buttons
        document.getElementById('lang-en-btn').addEventListener('click', () => setLanguage('en'));
        document.getElementById('lang-fr-btn').addEventListener('click', () => setLanguage('fr'));
        document.getElementById('lang-tr-btn').addEventListener('click', () => setLanguage('tr')); // Added Turkish listener


        // --- Mobile Menu Toggle Logic Event Listeners ---
        if (mobileMenuButton && mobileMenu) {
            mobileMenuButton.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });
            
            // Close mobile menu when a link is clicked
            mobileMenu.querySelectorAll('a').forEach(link => {
                link.addEventListener('click', () => {
                    mobileMenu.classList.add('hidden');
                });
            });
        }
        
        // ----------------------------------------------------------------------------------
        // GEMINI API INTEGRATION LOGIC
        // ----------------------------------------------------------------------------------

        const MAX_RETRIES = 5;

        // Utility function for robust API calls with exponential backoff
        async function fetchWithExponentialBackoff(url, options, retries = 0) {
            try {
                const response = await fetch(url, options);
                if (response.status === 429 && retries < MAX_RETRIES) {
                    const delay = Math.pow(2, retries) * 1000;
                    // console.warn(`Rate limit hit, retrying in ${delay / 1000}s...`);
                    await new Promise(resolve => setTimeout(resolve, delay));
                    return fetchWithExponentialBackoff(url, options, retries + 1);
                }
                if (!response.ok) {
                    const errorBody = await response.json();
                    throw new Error(errorBody.error?.message || `HTTP error! status: ${response.status}`);
                }
                return response;
            } catch (error) {
                if (retries < MAX_RETRIES) {
                    const delay = Math.pow(2, retries) * 1000;
                    // console.warn(`Network error, retrying in ${delay / 1000}s...`);
                    await new Promise(resolve => setTimeout(resolve, delay));
                    return fetchWithExponentialBackoff(url, options, retries + 1);
                }
                throw error;
            }
        }

        explainButton.addEventListener('click', async () => {
            const term = termInput.value.trim();
            const currentLangUI = uiTranslations[currentLang];

            if (!term) {
                errorMessage.textContent = currentLangUI['error-term'];
                errorMessage.classList.remove('hidden');
                explanationOutput.classList.add('hidden');
                return;
            }

            // Reset UI state
            explanationOutput.classList.add('hidden');
            errorMessage.classList.add('hidden');
            loadingIndicator.classList.remove('hidden');
            explainButton.disabled = true;

            try {
                const systemPrompt = currentLangUI['system-prompt'];
                const userQuery = `Expliquer le terme médical: "${term}"`;
                const apiKey = ""; 
                const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-09-2025:generateContent?key=${apiKey}`;

                const payload = {
                    contents: [{ parts: [{ text: userQuery }] }],
                    tools: [{ "google_search": {} }], 
                    systemInstruction: {
                        parts: [{ text: systemPrompt }]
                    },
                };

                const response = await fetchWithExponentialBackoff(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });

                const result = await response.json();
                
                const candidate = result.candidates?.[0];

                if (candidate && candidate.content?.parts?.[0]?.text) {
                    const text = candidate.content.parts[0].text;
                    
                    // 1. Update generated text
                    explanationText.innerHTML = text.replace(/\n/g, '<br>'); // Preserve line breaks

                    // 2. Extract and display grounding sources
                    let sources = [];
                    const groundingMetadata = candidate.groundingMetadata;
                    sourceList.innerHTML = ''; // Clear previous sources

                    if (groundingMetadata && groundingMetadata.groundingAttributions) {
                        sources = groundingMetadata.groundingAttributions
                            .map(attribution => ({
                                uri: attribution.web?.uri,
                                title: attribution.web?.title,
                            }))
                            .filter(source => source.uri && source.title); 
                    }
                    
                    if (sources.length > 0) {
                        sources.forEach(source => {
                            const listItem = document.createElement('li');
                            const link = document.createElement('a');
                            link.href = source.uri;
                            link.target = '_blank';
                            link.rel = 'noopener noreferrer';
                            link.textContent = source.title;
                            link.classList.add('underline', 'hover:text-blue-600', 'truncate', 'block');
                            listItem.appendChild(link);
                            sourceList.appendChild(listItem);
                        });
                        explanationSources.classList.remove('hidden');
                    } else {
                        explanationSources.classList.add('hidden');
                    }

                    explanationOutput.classList.remove('hidden');

                } else {
                    errorMessage.textContent = currentLangUI['error-generation'];
                    errorMessage.classList.remove('hidden');
                }

            } catch (error) {
                console.error('Gemini API Error:', error);
                let displayError = currentLangUI['error-api'].replace('[ERROR]', error.message);
                errorMessage.textContent = displayError;
                errorMessage.classList.remove('hidden');
            } finally {
                loadingIndicator.classList.add('hidden');
                explainButton.disabled = false;
            }
        });
    </script>
</body>
</html>
