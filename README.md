## English

- [Mairo Vergara](http://www.mairovergara.com/)
- [Anki](https://apps.ankiweb.net/)
- [Grammarly](https://www.grammarly.com/)
- [Audible](https://www.audible.com/)
- [Cambly](https://www.cambly.com/)
- [iTalki](https://www.italki.com/)
   
## Roadmap Software Engineering

- [Teach Yourself Programming in Ten Years - Peter Norvig](http://norvig.com/21-days.html)
- [Coding Interview University](https://github.com/jwasham/coding-interview-university)
- [Teach Yourself CS](https://teachyourselfcs.com/)
- [Web Developer Roadmap](https://github.com/kamranahmedse/developer-roadmap)
- [CS50 Harvard](https://www.youtube.com/user/cs50tv/videos)
- [wiki.icmc.usp.br](http://wiki.icmc.usp.br/index.php/P%C3%A1gina_principal_CoteiaWIKI)
- [edx.org/computer-science](https://www.edx.org/course/subject/computer-science)
- [coursera.org/algorithms](https://pt.coursera.org/courses?query=algorithms)
- [Electrical Engineering and Computer Science - MIT](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/)

## Ferramentas Úteis

 - [Coursera - Learning How to Learn: Powerful Mental Tools to Help You Master Tough Subjects](https://www.coursera.org/learn/learning-how-to-learn)
 - [Stanford - Designing Your Life & Carrer](https://lagunita.stanford.edu/courses/course-v1:Engineering+DYL+Ongoing/course/)
 - [LastPass](https://www.lastpass.com/pt)
 - [Archive.org/web](https://archive.org/web/)
 - [12minutos](https://12min.com/br)
 - [Ngrok](https://ngrok.com/)
 - [Cheatsheet do git-flow](https://danielkummer.github.io/git-flow-cheatsheet/index.pt_BR.html)
 - [SubmarineCableMap](https://www.submarinecablemap.com/)
 - [EmojiPedia.org](https://emojipedia.org/search/?q=talks)
 - Sites
    - [Jornal Da USP](https://jornal.usp.br/)
    - [Bpiropo](http://www.bpiropo.com.br/es_fpc1.htm)
    - [Dev.to](https://dev.to/)
 - Dev Jobs
    - [hipsters.job](https://hipsters.jobs/)
    - [Revelo](https://www.revelo.com.br/)
    - [Vulpi](https://vulpi.com.br/)
    - [Programathor](https://programathor.com.br/)
    - [GeekHunter](https://www.geekhunter.com.br/)
 - [StackOverFlow](https://stackoverflow.com/)
    - [Insights StackOverFlow](https://insights.stackoverflow.com/)
    - [Jobs](https://stackoverflow.com/jobs)
    - [Trends StackOverFlow](https://insights.stackoverflow.com/trends?tags=r%2Cstatistics)
 - StickersDev
    - [Officeless Stickers](https://officeless-store.minestore.com.br/produtos/cartela-de-stickers-officeless)
    - [StickersDevs](https://www.stickersdevs.com.br/)
 - DevTools
    - [GitKraken](https://www.gitkraken.com/)
    - [Hyper.is](https://hyper.is/)
 
## Algoritmos e Estrutura de Dados

 - Bíblia Análise de Algoritmos :skull: 
    - [The Art of Computer Programming - Donald Yoda Knuth](https://www.amazon.com.br/Computer-Programming-Volumes-1-4a-Boxed/dp/0321751043?tag=goog0ef-20&smid=A1ZZFT5FULY4LN&ascsubtag=go_1157433115_58530734048_257324212232_pla-433354953279_c_)
 - YouTube
    - [Linguagem C Programação Descomplicada](https://www.youtube.com/user/progdescomplicada/videos)
 - Sites
    - [GeeksForGeeks](https://www.geeksforgeeks.org/)
    - [AssemblyProgressivo.net](https://www.assemblyprogressivo.net/)
- Treinamento de Código
    - [Project Euler](https://projecteuler.net/)
    - [HackerRank](https://www.hackerrank.com/)
    - [Edabit](https://edabit.com)
    - [URI Online Judge](https://www.urionlinejudge.com.br/judge/en/login)
- KhanAcademy 
   - [Computer Science](https://www.khanacademy.org/computing/computer-science)
   - [Notação assintótica](https://pt.khanacademy.org/computing/computer-science/algorithms/asymptotic-notation/a/asymptotic-notation)
- Recursão :skull:
   - [O que é recursão? Teste de Mesa com Fatorial - Softblue](https://www.youtube.com/watch?v=V60g61dhKmg)
- Visualização de Estruturas de Dados :skull:
   - [VisualGo](https://visualgo.net/en)
   - [University of San Francisco - CS](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)
- Big O Notation :skull: 
   - [bigocheatsheet.com](http://bigocheatsheet.com/)
   - [A coffee-break introduction to time complexity of algorithms](https://dev.to/vickylai/a-coffee-break-introduction-to-time-complexity-of-algorithms-160m?utm_source=digest_mailer&utm_medium=email&utm_campaign=digest_email)
   - O(1) Constant Time
      - Melhor caso possível
      - Se um algoritmo possui tempo constante, significa que sempre vai levar o mesmo tempo para produzir o resultado.
      - Exemplo: array.pop() -> tirar último item de um array, independente do tamanho, levará sempre o mesmo tempo!
   - Logarithms O(log n)
      - Preferível na maioria das vezes
      - Logaritimos são o inverso da exponenciação.
      - Exemplo: Algoritmo de busca binária -> dividir para conquistar
      - <img src="ologn.png" alt="ologn">
   - Linear time O(n)
      - Preferível na maioria das vezes
      - Se um algoritmo possui tempo linear, significa que o tempo de execução aumenta linearmente de acordo com o tamanho do input.
      - Exemplo: array.forEach() soma de todos os valores
   - Linear Logarithms O(n log n)
      - Aceitável
      ```
      x = n
      while ( x > 0 ) {
        y = x
        while ( y > 0 ) {
           y = y / 2
        }
        x -= 1
      }
      ```
      - Examples: Quicksort, Mergesort and Heapsort  -> dividir para conquistar
   - Quadratic time O(n²) :skull:
      - Bom evitar
      - O tempo de execução desse algoritmo é diretamente proporcional ao o quadrado do input.
      - Ou seja: 2->4  3->9  4->16  5->25 etc
      - Exemplo: Soma de matrizes
      ```
      for (var outer = 0; outer < elements.Count; outer++){
        for (var inner = 0; inner < elements.Count; inner++){
          ...
        }
      }
      ```
   - Exponential Time O(2^n) :skull: :skull:
      - Um dos piores casos, sempre é bom evitar
      - Indica um algoritmo cujo crescimento dobra a cada adição ao conjunto de dados de entrada. A curva de crescimento de uma função O (2N) é exponencial - começando muito rasa e depois subindo meteoricamente
      - Exemplo: recursive calculation of Fibonacci numbers
      ```
      int Fibonacci(int number){
          if (number <= 1) return number;
          return Fibonacci(number - 2) + Fibonacci(number - 1);
      }
      ```
   - Factorial Time O(n!) :skull: :skull: :skull:
     - Pior caso possível, sempre tente evitar!
     - Extremamente não perfomático
     - Vai executar em tempo fatorial para cada operação
     - Exemplo: Problema do vendedor viajante
        - "Dada uma lista de cidades e as distâncias entre cada par de cidades, qual é o caminho mais curto possível que visita cada cidade e retorna à cidade de origem?"
   - <strong>Resumo</strong>
      - <img src="big-o-names.jpeg" alt="Big(O) Names">
      - <img src="big-o-graphic.jpeg" alt="Big(O) Graphic">

## Cultura Maker

 - Work Hard, Have Fun & Make History
   - [RaspberryPi](https://www.raspberrypi.org/homepage-9df4b/)
      - [Noobs - Beginners should start with NOOBS – New Out Of the Box Software](https://www.raspberrypi.org/downloads/noobs/)
      - [MagPi Ebooks](https://www.raspberrypi.org/magpi-issues/)
      - [Lakka](https://www.lakka.tv/)
      - [RetroPie](https://retropie.org.uk/)
   - [Embarcados](https://www.embarcados.com.br/)
      - [Arduino](https://www.arduino.cc/)
         - [Manual Maker | Manual do Mundo - YouTube PlayList](https://www.youtube.com/watch?v=gcBN4NLqz_U&list=PLYjrJH3e_wDNLUTN32WittrpBxeleEqNp)
         - [create.arduino.cc - IDE Online](https://create.arduino.cc/)
         - [Tinkercard - Arduino Online](https://www.tinkercad.com/)
         - [Brasilino](https://otacilion.github.io/Brasilino/)
            - Uma biblioteca que permite programar em linguagem Arduino utilizando comandos facilitados em PT-BR.
      - [Hackster](https://www.hackster.io/)
   - [Portugol](http://lite.acad.univali.br/portugol/)
   - [MIT Scratch](https://scratch.mit.edu/projects/editor/) :video_game:
   - [Pico8](https://www.lexaloffle.com/pico-8.php) :video_game:
      - [NerdyTeachers](https://nerdyteachers.com/)
      - [NerdTeachers YouTube](https://www.youtube.com/channel/UCbMjF_cWciuBUZjILNL1fyA)
   - Internet Of Things
      - [Home-Assistant](https://www.home-assistant.io/)
      - [MQTT](https://mqtt.org/)
      - [Blynk.io](https://blynk.io/)
   - Code Online Having Fun
      - [CodeCombat](https://codecombat.com/) 
      - [Code.org](https://code.org/)
      - [CodeMonkey](https://www.playcodemonkey.com/)
   - Cartoons
      - [MonkeyUser](https://www.monkeyuser.com/)
      - [VidaDeProgramador](https://vidadeprogramador.com.br/)
      - [VidaDeHipster](https://www.vidadehipster.com.br/)
   - Onde Comprar?
      - [FilipeFlop](https://www.filipeflop.com) :muscle:
      - [Robocore](https://www.robocore.net)
      - [VidaDeSilicio](https://www.vidadesilicio.com.br/)
      - [Arducore](https://www.arducore.com.br/)

## Linux

  - Sites
       - [IEEE.org](https://www.ieee.org/)
       - [Guia Foca](http://www.guiafoca.org/?page_id=51)
       - [SS64 - Commands CLI References](https://ss64.com/)
       - [Kernel.org](https://www.kernel.org/)
       - [Linuxize](https://linuxize.com/)
       - [Aurelio.net](https://aurelio.net/)
    - Benchmark
       - [Phoronix Test Suite](https://www.phoronix-test-suite.com/?k=downloads)
    - Comandos engraçados para o terminal :smile:
       - $ fortune 
          - If you are demotivated, maybe this command can be useful
       - $ sl  
          - Sheldon Cooper sure likes this command
       - $ cmatrix
          - man, I'm a hacker, wait, Neo it's you?
       - $ cowsay "I'm Awesome!"
          - Wait, what is a cow doing here?
       - $ xcowsay "I'm More Awesome!"
          - Holy shit, this cow is more awesome.
       - $ espeak "phrase here"
          - I'm making contact with aliens man!
    - Apps for Learn Linux CLI Commands
       - [Linux Command Library](https://play.google.com/store/apps/details?id=com.inspiredandroid.linuxcommandbibliotheca&hl=en&rdid=com.inspiredandroid.linuxcommandbibliotheca)
    - YoTube
       - [Diolinux](https://www.youtube.com/user/Diolinux)
       - [Toca do Tux](https://www.youtube.com/channel/UCkATW9o8m4pnXAAmac2o63Q)
       - [Curso de Linux Básico / Certificação LPIC1 - Bóson Treinamentos](https://www.youtube.com/watch?v=u16ZDPcf8Rc&list=PLucm8g_ezqNp92MmkF9p_cj4yhT-fCTl7)
    - Ferramentas
       - [LinSSID Wifi Inspector](https://www.edivaldobrito.com.br/instale-linssid-um-escaner-de-redes-wireles-para-linux-com-interface-grafica/)
       - [AnyDesk](https://anydesk.com)
       - [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
       - [Etcher - Flash OS images to SD cards & USB drives](https://etcher.io/)
       - [YUMI – Multiboot USB Creator](https://www.pendrivelinux.com/yumi-multiboot-usb-creator/)
       - [WineHQ](https://www.winehq.org/)
       - [Vim Para Noobs](https://woliveiras.com.br/vimparanoobs/)
    - Games
       - [Lutris](https://lutris.net/)
       - [ZNES](http://www.zsnes.com/)
       - [PlayOnLinux](https://www.playonlinux.com/en/)
    - Sistema operacional que utilizo e recomendo
       - [Lubuntu 18.04 LTS (Bionic Beaver)](https://lubuntu.net/)
  - FreeBSD
     - [Documentation PT-BR](https://www.freebsd.org/doc/pt_BR.ISO8859-1/)
    - [FreeBSD: O Poder dos Servidores em Suas Mãos - 2 Edição](https://www.amazon.com.br/FreeBSD-Poder-Servidores-Suas-M%C3%A3os-ebook/dp/B00FFZOE8Y)

## Microsoft Windows

 - Sites
    - [Baboo](https://www.baboo.com.br/)
    - [Baboo Cursos](https://www.baboocursos.com.br/)
 - Tools
    - [Cmder](http://cmder.net/)
    - [Rufus.ie for Windows](https://rufus.ie)
    - [Xorris Wifi Inspector](https://www.riverbed.com/products/xirrus/inspector.html)

## Segurança da Informação

 - Sites
    - [OWASP](https://www.owasp.org/index.php/Main_Page)
    - [EUGDPR.org](https://eugdpr.org/)
    - [LGPD - Lei Geral de Proteção de Dados Pessoais](http://www.planalto.gov.br/ccivil_03/_Ato2015-2018/2018/Lei/L13709.htm)
    - [Haveibeenpwned](https://haveibeenpwned.com/)
    - [Livro - Fundamentos de Engenharia Reversa - Mente Binária](https://mentebinaria.gitbook.io/engenharia-reversa/antes-de-comecar)
    - [Forum CaveiraTech](https://caveiratech.com/forum/)
    - [Oauth2](https://oauth.net/2/)
    - [Practical Cryptography for Developers - Free Book](https://cryptobook.nakov.com/)
 - Videos
    - [Gabriel Pato](https://www.youtube.com/channel/UC70YG2WHVxlOJRng4v-CIFQ)
    - [CaveiraTech](https://www.youtube.com/user/caveiratech2/playlists)
    - [Curso de Engenharia Reversa Online - Papo Binário](https://www.youtube.com/watch?v=IkUfXfnnKH4&list=PLIfZMtpPYFP6zLKlnyAeWY1I85VpyshAA)
 - Cursos 
    - [Fundamentos de Ethical Hacking - Udemy](https://www.udemy.com/fundamentos-de-ethical-hacking/learn/v4/)
    - [Solyd.com.br](https://solyd.com.br)
    - [Técnicas de Invasão](https://tecnicasdeinvasao.com/)
    - [Desenvolimento de Software Seguro - Curso Online Gratuito - ICA Instituto ](https://desenvolvimentoseguro.icainstituto.com.br/)
 - [DAT Protocol](https://www.datprotocol.com/)
    - [DatProject.org](https://datproject.org)
    - [Try Dat](https://try-dat.com/)
 - Banco de dados
    - World's Fastest Password Cracker
       - [HashCat](https://hashcat.net/hashcat/)
       - [HashKiller](https://hashkiller.co.uk/md5-decrypter.aspx)
    - Encriptação Recomendada
       - [Argon2](https://github.com/P-H-C/phc-winner-argon2)
       - [PBKDF2](https://en.wikipedia.org/wiki/PBKDF2)
       - [Scrypt](https://en.wikipedia.org/wiki/Scrypt)
       - [BCrypt](https://en.wikipedia.org/wiki/Bcrypt)
    - Não Recomendado :skull:
       - [MD5](https://pt.wikipedia.org/wiki/MD5)
       - [SHA1](https://www.thesslstore.com/blog/difference-sha-1-sha-2-sha-256-hash-algorithms/)
       - [SHA2](https://www.thesslstore.com/blog/difference-sha-1-sha-2-sha-256-hash-algorithms/)
       - [SHA256](https://www.thesslstore.com/blog/difference-sha-1-sha-2-sha-256-hash-algorithms/)
 - Ferramentas
    - Operation Systems
       - [Kali Linux](https://www.kali.org/)
       - [Tails Linux](https://tails.boum.org/index.pt.html)
    - Virtual Machines for Pentest
       - [PentesterLab](https://www.pentesterlab.com/exercises/)
       - [PentestBox](pentestbox.org)
          - [tools.pentestbox.org](https://tools.pentestbox.org/)
    - Transport Layer Security/Secure Sockets Layer
       - [Let's Encrypt](https://letsencrypt.org/)
    - Softwares
       - [WireShark](https://www.wireshark.org/)
       - [AngryIP Scanner](https://angryip.org/)
       - [metasploit](https://www.metasploit.com/)
	   - DataBases
	      - [Exploit-DB](https://www.exploit-db.com/)
	      - [SQLMap](http://sqlmap.org/)
	   - Useful CLI Commands
	      - [$ nmap site_url](https://nmap.org/)
	      - [$ traceroute site_url](https://www.lifewire.com/traceroute-linux-command-4092586)
        - [$ nmap localhost](https://nmap.org/)
	      - [$ curl site_url](https://curl.haxx.se/)
	      - [$ whafw00f site_url](https://github.com/EnableSecurity/wafw00f)
	      - [$ ping site_url](https://www.wikiwand.com/en/Ping)
	      - [$ host site_url](https://www.computerhope.com/unix/host.htm)
	      - [$ whois site_url](https://who.is/)
	   - Browsers
	      - [DuckDuckGo](https://duckduckgo.com)
	      - [Bernes Lee Solid](https://solid.mit.edu/)
	      - [Beaker Browser](https://beakerbrowser.com)
	      - [TorProject](https://www.torproject.org/)
	         - [TheHiddenWiki](https://thehiddenwiki.org/)
          
## Programação Funcional
  - [Aprender Haskell será um grande bem para você](http://haskell.tailorfontela.com.br/)

## Open Source
  - [OpenSource.org](https://opensource.org/)
  - [OpenSource.guide](https://opensource.guide/)
  - [Creative Commons](https://creativecommons.org/)
  - [Scrum Poker Online](https://scrumpoker.online/)

## Podcasts

 - [GooglePodcast](https://play.google.com/store/apps/details?id=com.google.android.apps.podcasts&hl=pt_BR)
 - Ciência & Tecnologia
    - Português
       - [Dev Na Estrada](https://devnaestrada.com.br/)
       - [HipsterTech](https://hipsters.tech/)
       - [NerdTech](https://www.alura.com.br/podcast-nerdtech)
       - [LoopMatinal](http://www.loopmatinal.com/)
       - [Syntax](https://syntax.fm/)
       - [Sinapse](https://anchor.fm/sinapse)
       - [DataBase Cast](http://databasecast.com.br/wp/)
       - [Podprogramar](https://mundopodcast.com.br/podprogramar/)
       - [SudoCast](https://github.com/sudocast)
       - [OneBitCode](https://onebitcode.com/category/podcast/)
       - [QuebraDev](http://quebradev.com.br/)
       - [Zofe](https://zofe.com.br/)
       - [BoaNoite Internet](https://www.boanoiteinternet.com.br)
       - [Castalio](https://castalio.info/)
       - [ElementCast](https://elemencast.github.io/#/episodios/6)
       - [Egermano](https://anchor.fm/egermano)
       - [Revolution](https://www.youtube.com/channel/UCRmG9ZyWxUenzxfoyatqp3A)
       - [SciCast](http://www.deviante.com.br/podcasts/scicast/)
       - [MeiaLua](http://www.deviante.com.br/podcasts/meialua/)
       - [Miçangas](http://www.deviante.com.br/podcasts/micangas/)
       - [TecnoCast](https://tecnoblog.net/categoria/podcast/)
       - [TricoTech](http://www.trico-tech.com/)
       - [GGDevCast](https://ggdevcast.com.br/)
       - [Por Trás dos Controles](https://www.radio.ufscar.br/shows/por-tras-dos-controles/)
       - [PixelsInk](https://www.cgmagonline.com/media/podcasts/pixels-ink/)
       - [DragoesDeGaragem](http://dragoesdegaragem.com/)
       - [Reloading](http://reloading.com.br/)
       - [RPGGuaxa](http://www.deviante.com.br/podcasts/rpguaxa/)
    - English
       - [CodeNewbie](https://www.codenewbie.org/)
       - [ShopTalk Show](https://shoptalkshow.com/)
       - [Learn To Code With Me](https://learntocodewith.me/podcast/)
       - [DeveloperTea](https://spec.fm/podcasts/developer-tea)
       - [Indie Hackers Podcast](https://www.indiehackers.com/podcast)
       - [FreeCodeCamp](https://freecodecamp.libsyn.com/)
       - [This Developers Life](http://thisdeveloperslife.com)
       - [CodingBlocks](https://www.codingblocks.net/)
       - [Changelog](https://changelog.com/podcast)
       - [FZDPodcast](http://fzdpodcast.com/)
       - [Programming Throwdown](https://www.programmingthrowdown.com/)
       - [Software Engineering Radio](http://www.se-radio.net/)
       - [GeekSpeak](https://geekspeak.org/)
       - [DevChat.TV](https://devchat.tv/)
       - [JavaScript Jabber](https://devchat.tv/js-jabber/)
       - [FullStack Radio](http://www.fullstackradio.com/)
       - [Twit.TV](https://www.twit.tv/)
       - [This Week In Tech](https://www.twit.tv/shows/this-week-in-tech)
       - [Security Now](https://www.twit.tv/shows/security-now)
       - [Floss Weekly](https://www.twit.tv/shows/floss-weekly)
       - [The Knowledge Project](https://fs.blog/the-knowledge-project/)
 - Empreendedorismo & outros
    - Português
       - [GVCast](https://geracaodevalor.com/gvcast/)
       - [Heroes 12 minutos](https://soundcloud.com/heroes-12min-podcast)
       - [Like a Boss](https://www.likeaboss.com.br/)
       - [Decrepitos](https://decrepitos.com/)
       - [CarreiraSemFronteiras](https://www.carreirasemfronteiras.com.br)
       - [GunCast](https://blog.keeplearning.school/guncast)
       - [NerdCast](https://jovemnerd.com.br/nerdcast)
       - [PapriCast](http://paprica.org/categoria/papricast/)
       - [B9 Podcasts](https://www.b9.com.br/podcasts/)
       - [ResumoCast](https://www.resumocast.com.br/)
       - [AntiCast](http://anticast.com.br/)
       - [ChutandoAEscada](https://chutandoaescada.com.br/)
       - [DicasCurtas](https://dicascurtas.com.br/)
       - [EscribaCafe](https://escribacafe.com/tagged/podcast)
    - English
       - [Tim Ferris Podcast](https://tim.blog/podcast/)
       - [Masters Of Scale](https://mastersofscale.com/)
       - [Rework.FM](https://rework.fm/)
       - [MadeYouThinkPodcast](https://madeyouthinkpodcast.com/)
 

## Software Engineering Principles

 - "Bad software that adds value > best software in the world that does not add value"
 - "Learn to say: I DONT KNOW"
 - "Premature Optimization: the Root of All Evil"
 - "Remember that dinosaurs are almost always the best references"
 - "Who thinks little, make more mistakes"
 - "In God we trust. All others must bring data."
 - "Lack of money is the root of all evil"
 - "Doesn't exist silver bullet"
 - "Make it Work > Make it Correct"
 - "Increase Revenue > Lower Costs"
 - "SaaS > PaaS > IaaS > In-House"
 - "You != Unicorn"
 - "Always try to understand what is happening under the hoods"
 - "Write code != programming != software engineering"
 - "Maintainability > Performance"
 - "No Metrics, No Optimization"
 - "Software engineering is 80% thinking ABOUT the problem, and 20% thinking HOW to solve the problem"
 - "The more knowledge you have, the less you know. Ego = 1 / knowledge"
 - "Everyone should care about the quality"
 - "99% of good software code has been thrown away"
 - "2 + 2 is not 5, no matter how many people say it"
 - "Principles > Analogy"
 - "Talk and learn from people smarter than you"
 - "Always try to use Single Source of Truth"
 - "Do not reinvent the wheel"
 - "It is always good to study a tool deeply before using it in production"
 - "Modularization is everything"
 - "Good artists copy. Great artists steal"
 - "Innovation only exists in a world of restraint and not of abundance"
 - "Always will have something to improve. Done is better than perfect"


## YouTube #StopWatchingTV

 - Tecnologia 🤖
    - [Curso em Video](https://www.youtube.com/user/cursosemvideo)
    - [Fabio Akita](https://www.youtube.com/channel/UCib793mnUOhWymCh2VJKplQ)
    - [EstudoNauta](https://www.youtube.com/channel/UCJcWQ9MgPlHIFMx8uDWEYNg)
    - [Fábrica de Noobs](https://www.youtube.com/channel/UCGObNjkNjo1OUPLlm8BTb3A)
    - [Hipsters.Tube](https://hipsters.tech/category/hipsters-ponto-tube/)
    - [COD3R CURSOS](https://www.youtube.com/channel/UCcMcmtNSSQECjKsJA1XH5MQ/featured)
    - [CodigoFonte TV](https://www.youtube.com/user/codigofontetv)
    - [BrasilJS](https://www.youtube.com/user/BrazilJS)
    - [RemoteFirst.com.br](https://www.remotefirst.com.br)
    - [NICbrvideos](https://www.youtube.com/user/NICbrvideos/videos)
    - [FreeCodeCamp](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ)
    - [Papo Binário](https://www.youtube.com/channel/UCuQ8zW9VmVyml7KytSqJDzg)
    - [Baboo](https://www.youtube.com/user/baboo/videos)
    - [CodellabCode](https://www.youtube.com/channel/UCVheRLgrk7bOAByaQ0IVolg)
    - [CanalTech](https://www.youtube.com/user/canaltechbr)
    - [Bruno Germano](https://www.youtube.com/channel/UCBWbWViVqDHckknir8PIIdg/videos)
    - [Brincando com Ideias](https://www.youtube.com/channel/UCcGk83PAQ5aGR7IVlD_cBaw)
    - [O Universo da Programação](https://www.youtube.com/channel/UCWrqsnPLl6aRX0ECUmPaZEw)
    - [UNIVESPTV](https://www.youtube.com/user/univesptv/playlists)
    - [ExplainingComputers](https://www.youtube.com/user/explainingcomputers)
    - [Engenharia Reversa](https://www.youtube.com/channel/UCagV1LuB6C52fFtZwVywZYg)
    - [TheHardwareShow](https://www.youtube.com/channel/UCiXDLhXSFZdnu1OWxwGvPTw)
    - [DevNaEstrada](https://www.youtube.com/channel/UCtIygB7LtILSFWR0kxtZC-A/videos)
    - [RocketSeat](https://www.youtube.com/channel/UCSfwM5u0Kce6Cce8_S72olg/videos)
    - [Bóson Treinamentos](https://www.youtube.com/user/bosontreinamentos)
    - [Leandro Fellipe](https://www.youtube.com/user/LeandroFelipe145/featured)
    - [ProgramadorBR](https://www.youtube.com/channel/UCrdgeUeCll2QKmqmihIgKBQ)
    - [Laboratório da Júlia](https://www.youtube.com/channel/UChfu9xWITOvsXYLKm7hieSQ)
    - [Bonieky Lacerda](https://www.youtube.com/channel/UCw9mYSlqKRXI6l4vH-tAYpQ)
    - [Real Engineering](https://www.youtube.com/channel/UCR1IuLEqb6UEA_zQ81kwXfg)
    - [SoftBlue](https://www.youtube.com/user/softbluecursos)
    - [Computherpile](https://www.youtube.com/user/Computerphile)
    - [A história da Tecnologia - TecMundo](https://www.youtube.com/playlist?list=PL7cCKVGMzqmbyaouQulXxUJLdwW4qBMpp)
    - [Mayuko](https://www.youtube.com/user/hellomayuko/videos)
    - [Computer Science - CrashCourse](https://www.youtube.com/watch?v=tpIctyqH29Q&list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo)
    - [Tecnologias do Futuro - The Enemy](https://www.youtube.com/watch?v=TLeTxzWbak8&list=PLTFO-hPawXIEYU16QavOFJvCFuruFq1Ps)
 - Talks
    - [Alura Cursos Online](https://www.youtube.com/user/aluracursosonline/videos)
    - [Tedx Talks](https://www.youtube.com/channel/UCsT0YIqwnpJCM-mx7-gSA4Q)
    - [iMasters](https://www.youtube.com/user/imasters)
    - [InfoQ Brasil](https://www.youtube.com/channel/UCjiSYWQhLi9a4znW2h5pCrg)
    - [Campus Party](https://www.youtube.com/channel/UCUendDl_o6qhA7GtHxH3PTA)
    - [Futuro Descentralizado](https://www.youtube.com/channel/UCwgs6fw_BSDG5MbEivaw05g/videos)
    - [Locaweb](https://www.youtube.com/channel/UCqHIy-SOkAgNU3b-PRUL8qA)
    - [Pagar.me Talks](https://www.youtube.com/channel/UCNhSCufrcOMeFvzEM7tt9Lw)
    - [Endeavor Brasil](https://www.youtube.com/user/endeavorbrasil/videos)
 - Ciências
    - [Nerdologia](https://www.youtube.com/channel/UClu474HMt895mVxZdlIHXEA)
    - [SpaceToday](https://www.youtube.com/channel/UC_Fk7hHbl7vv_7K8tYqJd5A)
    - [PeixeBabel](https://www.youtube.com/channel/UCqB90BBr6eNRaJl-kl30Xxw)
    - [TED-Ed](https://www.youtube.com/channel/UCsooa4yRKGN_zEE8iknghZA)
    - [Canal do Pirula](https://www.youtube.com/user/Pirulla25)
    - [Kurzgesagt – In a Nutshell](https://www.youtube.com/user/Kurzgesagt)
    - [Vsauce](https://www.youtube.com/user/Vsauce)
    - [Physics Girl](https://www.youtube.com/channel/UC7DdEm33SyaTDtWYGO2CwdA)
    - [Science Vlogs Brasil](https://www.youtube.com/channel/UCqiD87j08pe5NYPZ-ncZw2w)
    - [PBS Space Time ](https://www.youtube.com/channel/UC7_gcs09iThXybpVgjHZ_7g/about)
    - [Ponto em Comum](https://www.youtube.com/channel/UCGo3vjM2Ll3XujL-zYT5SMg)
    - [Alimente o Cérebro](https://www.youtube.com/channel/UC3fBS89aQ7mt5G1TodU4HNg)
    - [Singularidade](https://www.youtube.com/channel/UCA6-1g_4e3iuT1qeXe6xNuA/videos)
    - [Minutos Psíquicos](https://www.youtube.com/channel/UCFiEI1kDHlO9UQtxx0wj-XA)
    - [CrashCourse Kids](https://www.youtube.com/user/crashcoursekids/videos)
    - [BigThink](https://www.youtube.com/user/bigthink)
    - [Guru Da Ciência](https://www.youtube.com/channel/UCHgK6t6Ma6m15UNO2z7YZyw)
    - [AsapSCIENCE](https://www.youtube.com/channel/UCC552Sd-3nyi_tk2BudLUzA)
    - [Ciência Todo Dia](https://www.youtube.com/user/CienciaTodoDia)
    - [Primata Falante](https://www.youtube.com/user/mrprimatafalante)
    - [Manual do Mundo](https://www.youtube.com/user/iberethenorio) 
    - [Thoughty2](https://www.youtube.com/user/Thoughty2/featured)
    - [MathGurl](https://www.youtube.com/channel/UC5RV_s1Jh-jQI4HfexEIb2Q)
    - [A Matemaníaca por Julia Jaccoud](https://www.youtube.com/channel/UCz4Zuqtj9fokXH68gZJmCdA)
    - [OrigensNT](https://www.youtube.com/watch?v=HiNR74zi8qQ&list=PLUBR4s0w2cG1kyI2MDBJV0J3B5HuJoB7g)
 - Outros
    - [NeuroVox](https://www.youtube.com/user/NeuroVoxConsultoria)
    - [Canal Nostalgia](https://www.youtube.com/user/fecastanhari)
    - [Casa do Saber](https://www.youtube.com/channel/UCtvvTFp0XANyllOdmzZr9VQ)
    - [Moporã](https://www.youtube.com/channel/UCZYCNT6OT4_cgt-ldtwGQJw)
    - [Arata Academy](https://www.youtube.com/channel/UCEdgNBcBybRtwv836C8El4g)
    - [MOVA](https://www.youtube.com/channel/UCTw4_Y7XXuorDLN5fdDWeIQ)
    - [Jacob Petry](https://www.youtube.com/channel/UCv79O7v-AHomNC7MB7cx6BA)
    - [Augusto Ollivieri](https://www.youtube.com/channel/UCfkmlovZdEmMzTsGwatkoIw)
    - [IlustradaMente](https://www.youtube.com/channel/UCNmO5NWNLQkOr76WmHEq-DQ)
    - [Quebrando a Caixa](https://www.youtube.com/channel/UC-aLWCrfZTK0_P4KRe9dQZw)
    - [PhilosTV](https://philos.tv/)
    - [Wisecrack](https://www.youtube.com/channel/UC6-ymYjG0SU0jUWnWh9ZzEQ)
    - [The School Of Life](https://www.youtube.com/channel/UC7IcJI8PUf5Z3zKxnZvTBog)
    - [Gilberto de Souza](https://www.youtube.com/channel/UCMMbl7Tt6Zy5Ho3W2bw0BfQ)
    - [Democracia na Teia](https://www.youtube.com/channel/UCvAuRF1LpthT-MNS1qKOzTQ)
    - [The History Channel Brasil](https://www.youtube.com/watch?v=6bvc8TgeGUA)
    - [Canal do Moscoso](https://www.youtube.com/channel/UChVeSyoB200ALDpnTr1TOrg/videos)
    - [Elegante](https://www.youtube.com/channel/UCwqDUiw5ut1d6glseGzH13A)
    - [reVisão](https://www.youtube.com/channel/UCiNq4OzZBFmlmERJrZdOHig/featured)
    - [Roda Viva](https://www.youtube.com/channel/UCNVsZnDXOM4PodYIEgM2e4w)
    - [Antídoto](https://www.youtube.com/channel/UCMlX_MlK7s53AjQdI7uSiyQ)
    - [didatics](https://www.youtube.com/channel/UC6Qp0jm83uxJKJEbkafl35g)
    - [mimimidias](https://www.youtube.com/channel/UCg0CfiR_iKjBOYgeHps17BA)
    - [MuriloGun](https://www.youtube.com/user/murilogun/videos)
    - [Território Conhecimento](https://www.youtube.com/channel/UCLtgh-Q-yHkYjeiY7NSPieA/featured)
    - [Café Filosófico CPFL](https://www.youtube.com/channel/UCEgITwyUyDiMVBpmDibjP3g)
    - [Se Liga Nessa História](https://www.youtube.com/channel/UCKUL3EyuAEaJUYH_kib15dg)
    - [Quem Somos Nós?](https://www.youtube.com/channel/UCIj7UmUVFTFC9yXNiZoRmEg/featured)
    - [Provocações](https://www.youtube.com/channel/UCKdVW7Np-9l3CM5daYcGEAw)
    - [Ler Antes de Morrer](https://www.youtube.com/channel/UCTubbc8ei3JfOBbicSJYPfQ)
    - [Metaforando](https://www.youtube.com/channel/UCh7TUTXojlE8vRtb-EnuDzw)
    - [Canal do Por Quê?](https://www.youtube.com/channel/UCqWMwhpW-rggQZtfNXIqkrw)
    - [Meteoro Brasil](https://www.youtube.com/channel/UCk5BcU1rOy6hepflk7_q_Pw)
    - [Canal do Cortella](https://www.youtube.com/channel/UCyTS929PXJSUiBEFSzdypgg)
    - [Luiz Felipe Pondé](https://www.youtube.com/channel/UCW9jLtlONRp7W-AK9F8M66Q)
    - [NOVA ACRÓPOLE - Escola Internacional de Filosofia](https://www.youtube.com/channel/UCAMO_xP86YB4FSHD1Mi_GpA)
    - [Ivan Maia](https://www.youtube.com/channel/UCV2PX_XxoAr6r8ukV327rtg)
    - [Prazer, Karnal](https://www.youtube.com/channel/UC4O2eKb8vI4VlMeNp90asfg)
    - [Saber Filosófico](https://www.youtube.com/channel/UCWdXgfpEIZIGzah9_yCL-Xw)
    - [Seja Uma Pessoa Melhor](https://www.youtube.com/channel/UCbG7_Agdb99rhG9-rhY8iTg/videos)
    - [Jordan Peterson](https://www.youtube.com/user/JordanPetersonVideos)
       - REGRA 1 – Costas eretas e ombros para trás
       - REGRA 2 – Cuide de si mesmo como cuidaria de alguém sob sua responsabilidade
       - REGRA 3 – Seja amigo de pessoas que queiram o melhor para você
       - REGRA 4 – Compare a si mesmo com quem você foi ontem, não com quem outra pessoa é hoje
       - REGRA 5 – Não deixe que seus filhos façam algo que faça você deixar de gostar deles
       - REGRA 6 – Deixe sua casa em perfeita ordem antes de criticar o mundo
       - REGRA 7 – Busque o que é significativo, não o que é conveniente
       - REGRA 8 – Diga a verdade. Ou pelo menos, não minta. Seja sincero e aprenda a dizer não!
       - REGRA 9 – Presuma que a pessoa com quem está conversando possa saber algo que você não sabe
       - REGRA 10 – Seja preciso no que diz
       - REGRA 11 – Não incomode as crianças quando estão andando de skate
       - REGRA 12 – Acaricie um gato ao encontrar um na rua

## Economia & Negócios
  - [@coachdefracassos](https://www.instagram.com/coachdefracassos/?hl=pt-br)
  - [@startupdareal](https://twitter.com/startupdareal)
  - “Não faz sentido contratar pessoas inteligentes e dizer a elas o que elas devem fazer; nós contratamos pessoas inteligentes para que elas possam nos dizer o que fazer”. - Steve Jobs
  - <strong>"As pessoas não compram o que você faz, elas compram o por que você faz."</strong> – Simon Sinek
  - <img src="circulo-dourado.png" alt="Circulo Dourado">
  - [Me Poupe](https://www.youtube.com/channel/UC8mDF5mWNGE-Kpfcvnn0bUg)
  - [Gustavo Cerbasi](https://www.youtube.com/channel/UC_mSfchV-fgpPy-vuwML8_A)
  - [EconoWeek](https://www.youtube.com/channel/UCZFNY5I0RnErV23CZAd-QuQ)
  - [Canal do Por Quê?](https://www.youtube.com/channel/UCqWMwhpW-rggQZtfNXIqkrw)
  - [José Kobori](https://www.youtube.com/channel/UCOKSOW5uJHdW7Edz37mvAFw)
  - [Ricardo Amorim](https://www.youtube.com/user/RicardoAmorimMC/videos)
  - [Richard Rytenband](https://www.youtube.com/watch?v=ue-jy3-lUTk)
  - [Bruno Perini](https://www.youtube.com/channel/UCCE-jo1GvBJqyj1b287h7jA)
  - [Clube Do Valor](#)
  - <strong>Juros Compostos</strong>
     - “Os juros compostos é a maior invenção da humanidade, porque permite uma confiável e sistemática acumulação de riqueza.” - Einstein
     - M = Montante Final
     - C = Capital Inicial
     - i = Porcentagem do lucro ao mês/ano
     - n = Tempo de Aplicação (meses/anos)
     - J = Lucro líquido dado pelos juros compostos
     - M = C . (1+i)^n
     - J = M - C
     - Ex: Investir 5.000 com 0,5% de rendimento ao mês durante 12 meses
     - M = 5.000 x (1,05)^12
     - M = 5.000 x 1,7958
     - M = 8.979
     - J = 8979 - 5000 = R$ 3979
  - <strong>As Quatro Formas de Ganhar Dinheiro segundo Kiyosaki</strong>
     - Ser empregado == dedica seu conhecimento, habilidades e seu tempo para resolver os problemas de alguma empresa;
     - Ser autônomo == dedica seu conhecimento, habilidades e tempo para alguém que se interessa pelo serviço ou criando produtos próprios (livros, cursos online, etc);
     - Ser um investidor == onde você investe o dinheiro, por exemplo, na Bolsa de Valores ou em um fundo de investimento;
     - Ser dono de um negócio == onde você tem uma micro, média, grande empresa, ecommerce, etc.
     - Ativo == Tudo aquilo que gera dinheiro
     - Passivo == Tudo aquilo que tira dinheiro
     - Sempre se pague primeiro, depois os outros.
  - <strong>Warren Buffet Principles</strong>
     - Warren Buffet diz que procuramos, em geral, três coisas em uma pessoa: a inteligência, a energia e integridade. E se ela não têm essa última coisa, a integridade, não precisamos nos preocupar com as outras duas.
     - Com ou sem integridade, é mais fácil se livrar de uma pessoa que não é inteligente, do que uma pessoa inteligente.
     - Simplificando as coisas (e removendo a integridade dessa equação) teremos 4 combinações possíveis: estúpidos e trabalhadores, estúpidos e preguiçosos, inteligentes e trabalhadoras e inteligentes e preguiçosas.
     - Regra Número 1: Nunca perca dinheiro
     - Regra Número 2: Nunca esqueça a regra número 1
     - O risco vem de não saber o que você está fazendo.
     - Os investidores devem se lembrar que a excitação e os gastos são seus inimigos. E se insistirem em cronometrar a sua participação em ações, eles deveriam tentar ser medrosos quando os outros forem gananciosos e gananciosos quando os outros forem medrosos.
     - Rentabilidade passado NÃO garante rentabilidade futura.
     - Alguém está sentado na sombra hoje porque alguém plantou uma árvore há muito tempo.
     - Procurando pessoas para contratar, você busca três qualidades: integridade, inteligência, e energia. E se elas não têm a primeira, as outras duas matarão você.
     - São necessários 20 anos para construir uma reputação e apenas cinco minutos para destruí-la.
     - Por algum motivo, as pessoas se baseiam nos preços e não nos valores. Preço é o que você paga. Valor é o que você leva.
     - Se você acertou, pare de tentar.
     - Você só precisa fazer algumas poucas coisas certas na vida- desde que não faça muitas erradas.
     - Se a história passada fosse tudo o que importa no jogo, as pessoas mais ricas seriam os bibliotecários.
     - A maioria das pessoas se interessa por ações quando todo mundo está interessado. O momento de interessar-se é quando ninguém mais se interessa. Não se ganha dinheiro comprando o que é popular.
     - Não ponha dinheiro onde não entende, não aplique em empreedimentos endividados, aplique em coisas simples (pé no chão) mas que nunca deixarão de ser usadas (comida, refrigerante, aparelhos de barbear, cerveja).
  - <strong>Os 12 Axiomas de Zurique</strong>
     - 1. Preocupação não é doença, mas sinal de saúde. Se você não está preocupado, não está arriscando o bastante.
     - 2. Realize o lucro sempre cedo demais.
     - 3. Quando o barco começar a afundar, não reze. Abandone-o.
     - 4. O comportamento do ser humano não é previsível. Desconfie de quem afirmar que conhece uma nesga que seja do futuro.
     - 5. Até começar a parecer ordem, o caos não é perigoso.
     - 6. Evite lançar raízes. Elas tolhem seus movimentos.
     - 7. Só se pode confiar num palpite que possa ser explicado.
     - 8. É improvável que entre os desígnios de Deus para o Universo se inclua o de fazer você ficar rico.
     - 9. Otimismo significa esperar o melhor, mas confiança significa saber como se lidará com o pior. Jamais faça uma jogada por otimismo apenas.
     - 10. Fuja da opinião da maioria. Provavelmente está errada.
     - 11. Se não deu certo da primeira vez, esqueça.
     - 12. Planejamentos a longo prazo geram a perigosa crença de que o futuro está sob controle. É importante jamais levar muito a sério os seus planos a longo prazo, nem os de quem quer que seja.

## Outras Referências

 - [TIMELAPSE OF THE FUTURE: A Journey to the End of Time (4K)](https://www.youtube.com/watch?v=uD4izuDMUQA)
 - [Getting Real - the smarter, faster, easy way to build a sucesfull web application - BaseCamp](https://basecamp.com/books/getting-real)
 - [Happiness - Steve Cutts](https://www.youtube.com/watch?v=e9dZQelULDk)
 - [Escravos da Tecnologia - Steve Cutts](https://www.youtube.com/watch?v=Qx8JIoNOz0Y)
 - [The Humble Programmer by Edsger W. Dijkstra](https://www.cs.utexas.edu/~EWD/transcriptions/EWD03xx/EWD340.html)
 - [16 Personalities](https://www.16personalities.com/)
 - [80000hours.org](https://80000hours.org/)
 - [Rob Pike's 5 Rules of Programming](http://users.ece.utexas.edu/~adnan/pike.html)
 - [The Twelve Factor App - Heroku](https://12factor.net/)
    - A aplicação doze-fatores é uma metodologia para construir softwares-como-serviço.
    - I. Base de Código
       - Uma base de código com rastreamento utilizando controle de revisão, muitos deploys
    - II. Dependências
       - Declare e isole as dependências
    - III. Configurações
       - Armazene as configurações no ambiente
    - IV. Serviços de Apoio
       - Trate os serviços de apoio, como recursos ligados
    - V. Build, release, run
       - Separe estritamente os builds e execute em estágios
    - VI. Processos
       - Execute a aplicação como um ou mais processos que não armazenam estado
    - VII. Vínculo de porta
       - Exporte serviços por ligação de porta
    - VIII. Concorrência
       - Dimensione por um modelo de processo
    - IX. Descartabilidade
       - Maximizar a robustez com inicialização e desligamento rápido
    - X. Dev/prod semelhantes
       - Mantenha o desenvolvimento, teste, produção o mais semelhante possível
    - XI. Logs
       - Trate logs como fluxo de eventos
    - XII. Processos de Admin
       - Executar tarefas de administração/gerenciamento como processos pontuais



