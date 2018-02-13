# RChain Nomenclature

    Ang tumong alang niini nga dokumento: paghimo og listahan sa mga pulong sa RChain, ang ilang kahulugan
    ug nalambigit nga sulod sa markdown isip pahina sa github.
    Kasamtangan nga kahimtang: gikinahanglan ang pag-uswag pinaagi sa mga tigtabang nga teknikal.

    Sintaks alang sa mga editor:
    - Ang mga seksyon makakuha sa usa ka lebel 2 nga ulohan (##) ug mga subseksyon (kung gikinahanglan) ang lebel 3.
    - Ang mga kondisyon nga gihubit makakuha og level 4 nga ulohan (####). Kini sa batakan naghimo sa
      text bold apan usab URL-linkable ingon man usab nga parsable alang sa umaabot nga bot.
    - Ang kahulugan nga nagasunod sa usa ka pulong usa ka normal nga parapo.

**Pagdugtong sa mga Kahulugan**
Pag-link sa usa ka termino pinaagi sa paggamit sa termino sa usa ka angkla, e.g. alang sa Rholang, sumpay ngadto sa:https://github.com/rchain/Members/blob/master/projects/dictionary.md#rholang. 
O kopyaha gikan sa icon nga link nga gipakita sa Github sa dihang nag-hover ka sa usa ka ulohan.



##  RChain General

#### RChain
Ang RChain usa ka desentralisado, ekonomikanhon nga malungtarong publiko nga compute nga imprastraktura. Ang modelo sa pagpatay niini gikuha gikan sa syntax ug semantics sa rho-calculus, diin ang "Rho" nagpasabot sa reflective, higher-order. Ang rho-calculus usa ka balangkas alang sa pag-analisar sa dungan nga mga proseso nga nagsulti sama sa biolohikal nga mga selula o lainlaing mga ngalan sa usa ka blockchain. Ang FMI makita ang FAQ ug ang website.(https://github.com/rchain/reference/blob/master/faq.md) and the [website](http://rchain.coop/).

#### RChain Platform
Ang plataporma mao ang kinatibuk-ang imprastraktura sa software, nga gipagawas sa katapusan sa 2018. Ang kasingkasing sa usa ka RChain mao ang Rho Virtual Machine (RhoVM) Execution Environment, nga nagpadagan sa daghang RhoVMs nga ang matag usa nagpatuman sa usa ka smart nga kontrata. Kini nga mga pag-execute sa dungan nga panahon ug mga multi-threaded.

#### RChain Blockchain
Ang RChain blockchain usa ka graph sa mga bloke. Ang matag bloke adunay usa ka header nga nagpunting sa usa o labaw pa nga nangaging mga bloke, lista sa mga transaksyon, ug uban pang metadata. Source: Architecture Overview sa RChain Architecture

## Pormal nga mga Pamaagi

#### Pormal nga mga Pamaagi
Sa siyensiya sa kompyuter, partikular nga software engineering ug hardware engineering, pormal nga mga pamaagi ang usa ka partikular nga matang sa mga pamaagi sa matematika nga pamaagi alang sa paghingalan, pagpalambo ug pagsusi sa software ug hardware nga mga sistema. Source: Formal Methods sa Wikipedia.

#### Process Algebra
Ang usa ka algebra usa ka matematika nga istruktura nga adunay usa ka hugpong sa mga bili ug usa ka hugpong sa mga operasyon sa mga bili. Kini nga mga operasyon nakatagamtam sa algebraic properties sama sa commutativity, associativity, idempotency, ug distributivity. Sa usa ka tipikal nga proseso nga algebra, ang mga proseso mao ang mga bili ug ang parallel nga komposisyon gihubit nga usa ka commutative ug associative operation sa proseso. Source:[Process Algebra](https://en.wikipedia.org/wiki/Process_calculus)sa Wikipedia.

#### Pagproseso Algebra
Sa siyensiya sa kompyuter, ang proseso nga calculi (o proseso nga mga algebras) usa ka lainlaing pamilya nga may kalabutan nga mga pamaagi alang sa pormal nga pagmugna og dungan nga mga sistema. Ang proseso nga calculi naghatag og usa ka himan alang sa hataas nga lebel nga paghulagway sa mga interaksyon, komunikasyon, ug mga pag-synchronize tali sa usa ka koleksyon sa mga independenteng ahente o proseso. Naghatag usab sila og mga algebraic nga mga balaod nga nagtugot sa mga paghulagway sa proseso sa pagmaniobra ug pag-analisar, ug pagtugot sa pormal nga pangatarungan mahitungod sa pagkaparis sa mga proseso. Source: [Process Calculus](https://en.wikipedia.org/wiki/Process_calculus) sa Wikipedia.

#### Lambda Calculus
Ang Lambda calculus (gisulat usab nga λ-calculus) usa ka pormal nga sistema sa matematika nga lohika alang sa pagpahayag sa pag-ihap pinasukad sa function abstraction ug aplikasyon gamit ang variable binding ug substitution. Source: [Lambda Calculus](https://en.wikipedia.org/wiki/Lambda_calculus) sa Wikipedia.

#### Pi Calculus
Sa teoretikal nga siyensiya sa computer, ang π-calculus (o pi-calculus) usa ka proseso nga calculus. Ang π-calculus nagtugot sa mga ngalan sa channel nga ipaambit sa mga channel mismo, ug niining paagiha kini makahulagway sa dungan nga pag-compute nga ang pag-usab sa network mahimo nga mausab sa panahon sa pag-compute. Ang π-calculus elegante ka simple, kini adunay pipila lamang ka mga pulong ug mao ang usa ka gamay kaayo nga pinulongan, apan kini makapahayag kaayo. Ang mga programa nga pang-obra mahimong ma-encode sa π-calculus, ug ang pag-encode nagpasiugda sa pag-dialogo nga kinaiya sa pag-compute, pagdrowing og koneksyon sa mga semantics sa game.

#### Rho Calculus

Ang rho-calculus usa ka pormalismo nga gitumong aron mahiusa ang mas taas nga pagkasunod nga mga kahimanan sa lambda calculus uban ang sumbanan sa pagsulat sa termino nga pagsulat pag-usab. Source: [Rho Calculus](https://en.wikipedia.org/wiki/Rho_calculus) sa Wikipedia.

#### LADL

LADL Ang LADL mao ang Logic nga usa ka Distributive Law. Sa tinuud, kini mahitungod sa usa ka matang sa pagbag-o gikan sa usa ka panglantaw sa kolektibo ngadto sa lain. Ang LADL algorithm nag-ingon nga ang mga pormula nahisama sa usa ka larawan sa Rayna sa England nga gihimo gikan sa daghang gagmay nga mga larawan sa Queen. Ang kamatuoran, bisan pa nga posible nga buhaton kini nga sistematiko alang sa matag pormula naghatag kanato sa katungod sa pagtratar sa mga pormula sa ilang mga kaugalingon ingon nga paghatag sa mga pamaagi aron sa pagtukod sa mga kolektibo nga sa matag usa adunay katilingban. Source: "E Pluribus Unum 2.0" RChain posisyon nga papel (wala pa gipatik).

## Rholang

#### Rholang

Ang Rholang usa ka kompleto nga bahin, kinatibuk-an nga katuyoan, Turing-kompleto nga programming language nga gitukod gikan sa rho-calculus. Kini usa ka kinaiya nga gi-type, r-eflective, h-igher o-rder nga proseso nga pinulongan ug ang opisyal nga pinulongan nga pinulongan sa RChain. Ang katuyoan niini mao ang pag-concretize sa maayong pagkahan-ay, ang pag-concurrency sa programa. Source: [Contract Design](http://rchain-architecture.readthedocs.io/en/latest/contracts/contract-design.html#rholang-a-concurrent-language) sa RChain Architecture.

#### RhoVM

Ang matag usa nga institusyon sa Rho Virtual Machine (RhoVM) nagmintinar sa usa ka palibot nga kanunayng nagamit sa ubos nga lebel sa rho-calculus reduction rule, nga gipahayag sa taas nga level Rholang nga pinulongan nga pinulongan, ngadto sa mga elemento sa usa ka nagapadayon nga key-value data store. Ang "kahimtang" sa RhoVM susama sa estado sa blockchain. Source:[Execution MOdel](http://rchain-architecture.readthedocs.io/en/latest/execution_model/rhovm.html) sa RChain Architecture.

#### Rosette
Ang matag usa nga institusyon sa Rho Virtual Machine (RhoVM) nagmintinar sa usa ka palibot nga kanunayng nagamit sa ubos nga lebel sa rho-calculus reduction rule, nga gipahayag sa taas nga level Rholang nga pinulongan nga pinulongan, ngadto sa mga elemento sa usa ka nagapadayon nga key-value data store. Ang "kahimtang" sa RhoVM susama sa estado sa blockchain. Source: [Execution MOdel](http://rchain-architecture.readthedocs.io/en/latest/execution_model/rhovm.html) sa RChain Architecture.
##  Rho API

##  Rho API

#### Binding ng Wika
Sa computing, ang isang umiiral na mula sa isang programming language sa isang library o operating system service ay isang application programming interface (API) na nagbibigay ng glue code upang magamit ang library o serbisyo sa isang wika ng programming. Source: Wika Binding sa Wikipedia.
Source: [Language Binding](https://en.wikipedia.org/wiki/Language_binding) at Wikipedia.

#### Rho Language Bindings
Ang Rho API ay may bindings para sa Java, Scala, at ilang iba pa ngunit hindi Phyton ....

## Mga Tuntunin sa Science sa Computer

#### Mga Aktor, Tuple, at Pi

    Not sure what this is meant to be.... please fill in.

#### Behavioral Types
<!-- Substitutability is a principle in object-oriented programming stating that, in a computer program, if S is a subtype of T, then objects of type T may be replaced with objects of type S (i.e. an object of type T may be substituted with any object of a subtype S) without altering any of the desirable properties of T (correctness, task performed, etc.). More formally, the Liskov substitution principle (LSP) is a particular definition of a subtyping relation, called (strong) behavioral subtyping. It is a semantic rather than merely syntactic relation because it intends to guarantee semantic interoperability of types in a hierarchy, object types in particular.
Source: [Liskov substitution principle](https://en.wikipedia.org/wiki/Liskov_substitution_principle) at Wikipedia. -->
Ang uri ng pag-uugali ay isang ari-arian ng isang bagay na nagbubuklod sa isang discrete range ng mga pattern ng pagkilos. Ang mga uri ng pag-uugali ay hindi lamang ang istruktura ng input at output, kundi ang pinahihintulutang pagkakasunud-sunod ng mga input at output sa pakikipag-usap at (posibleng) mga sabay na proseso sa ilalim ng iba't ibang mga kondisyon. 
Source: [Contract Design](http://rchain-architecture.readthedocs.io/en/latest/contracts/contract-design.html) in RChain Architecture.

#### Concurrency
Sa agham ng kompyuter, ang concurrency ay ang pag-aari ng pag-decomposability ng isang programa, algorithm, o problema sa mga bahagi o yunit ng order-independiyenteng o bahagi na iniutos. [1] Nangangahulugan ito na kahit na ang mga kasabay na yunit ng programa, algorithm, o problema ay pinaandar ng out-of-order o sa bahagyang order, ang huling resulta ay mananatiling pareho. Ito ay nagbibigay-daan para sa parallel pagpapatupad ng mga kasabay na mga yunit, na maaaring makabuluhang mapabuti ang pangkalahatang bilis ng pagpapatupad sa multi-processor at multi-core system.:: [Concurrency (computer science)](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) at Wikipedia.

#### Concurrency vs Parallelism
Mahalagang maunawaan ang mga implikasyon ng kasabay na pagpapatupad. Kapag sinasabi namin, "concurrency", hindi namin tinutukoy ang sabay na pagpapatupad ng maraming proseso. Iyon ay parallelism. Concurrency ay isang estruktural ari-arian na nagbibigay-daan sa mga independiyenteng proseso upang bumuo sa kumplikadong proseso. Ang mga proseso ay itinuturing na malaya kung hindi sila makipagkumpetensya para sa mga mapagkukunan.
Pinagmulan: [Architecture Overview](http://rchain-architecture.readthedocs.io/en/latest/introduction/architecture-overview.html?highlight=Concurrency) in RChain Architecture.

#### Extensional
Ang isang extensional na kahulugan ng isang konsepto o termino ay bumubuo ng kahulugan nito sa pamamagitan ng pagtukoy ng extension nito, samakatuwid nga, ang bawat bagay na nasa ilalim ng kahulugan ng konsepto o termino na pinag-uusapan. Ang mga malawak na kahulugan ay ginagamit kapag ang mga halimbawa ng paglilista ay magbibigay ng higit na naaangkop na impormasyon kaysa sa iba pang mga uri ng kahulugan, at kung saan ang listahan ng mga miyembro ng isang set ay nagsasabi ng sapat na tanong tungkol sa likas na katangian ng set na iyon.
Pnagmulan: [Extensional and intensional definitions](https://en.wikipedia.org/wiki/Extensional_and_intensional_definitions) at Wikipedia.

#### Intensiyon
Sa lohika at matematika, ang isang kahulugan ng intensyon ay nagbibigay ng kahulugan ng isang termino sa pamamagitan ng pagtukoy ng mga kinakailangan at sapat na kondisyon para sa kung kailan dapat gamitin ang term. Sa kaso ng mga pangngalan, ito ay katumbas ng pagtukoy sa mga ari-arian na kailangan ng isang bagay upang maibilang bilang isang reperensya ng termino. Ang mga intensiyon na kahulugan ay pinakamahusay na ginagamit kapag ang isang bagay ay may isang malinaw na tinukoy na hanay ng mga katangian, at gumagana ang mga ito nang maayos para sa mga tuntunin na may masyadong maraming mga referent sa listahan sa isang extensional kahulugan.
Pinagmulan: [Extensional and intensional definitions](https://en.wikipedia.org/wiki/Extensional_and_intensional_definitions) at Wikipedia.

#### Recursion
Ang pag-recursion sa agham ng computer ay isang paraan kung saan ang solusyon sa isang problema ay nakasalalay sa mga solusyon sa mga mas maliit na pagkakataon ng parehong problema (kumpara sa pag-ulit). Ang diskarte ay maaaring mailapat sa maraming uri ng mga problema. Karamihan sa mga programming language computer ay sumusuporta sa recursion sa pamamagitan ng pagpapahintulot ng isang function na tumawag sa sarili sa loob ng teksto ng programa. Ang ilang mga functional programming languages ay hindi tumutukoy sa anumang mga looping constructs ngunit umaasa lamang sa recursion sa paulit-ulit na tawag code. Pinatutunayan ng teorya ng computability na ang mga recursive-only na wika na ito ay kumpleto na; ang mga ito ay tulad ng malakas na computationally bilang Turing kumpletong mga makapangyarihang wika, ibig sabihin maaari nilang malutas ang parehong uri ng mga problema bilang mga makapangyarihang wika kahit na walang iterative control structures tulad ng "habang" at "para sa". 
Pinagmulan: [Recursion (computer science)](https://en.wikipedia.org/wiki/Recursion_(computer_science)) at Wikipedia.

#### Reflection
In mathematics, a reflection formula or reflection relation for a function f is a relationship between f(a − x) and f(x). It is a special case of a functional equation, and it is very common in the literature to use the term "functional equation" when "reflection formula" is meant.
Source: [Contract Design](http://rchain-architecture.readthedocs.io/en/latest/contracts/contract-design.html) in RChain Architecture.

#### Tuple Space
Sa matematika, ang isang reflection formula o pagmumuni-muni para sa isang function f ay isang relasyon sa pagitan ng f (a - x) at f (x). Ito ay isang espesyal na kaso ng isang functional equation, at ito ay napaka-pangkaraniwan sa panitikan upang gamitin ang terminong "functional equation" kapag ang "formula ng pagmuni-muni" ay nilalayong. Pinagmulan: Disenyo ng Kontrata sa RChain Architecture.
Tuple Space
Ang puwang ng tuple ay isang pagpapatupad ng paradaym ng pag-uugnay ng memory para sa parallel / ipinamamahagi computing. Nagbibigay ito ng isang repository ng mga tuple na maaaring ma-access nang sabay-sabay. Bilang isang nakapagpapaliwanag halimbawa, isaalang-alang na mayroong isang pangkat ng mga processor na gumagawa ng mga piraso ng data at isang pangkat ng mga processor na gumagamit ng data. Ang mga producer ay nag-post ng kanilang data bilang mga tuple sa espasyo, at pagkatapos ay kunin ng mga mamimili ang data mula sa puwang na tumutugma sa isang tiyak na pattern. Ito ay kilala rin bilang ang metapora ng pisara. Ang puwang ng Tuple ay maaaring iisip bilang isang paraan ng ibinahagi na shared memory. 
Pinagmulan: [Tuple Space](https://en.wikipedia.org/wiki/Tuple_space) at Wikipedia.

## Mga Token

#### Katunayan ng Stake
PoS ay isang uri ng algorithm kung saan ang isang cryptocurrency blockchain network ay naglalayong makamit ang ipinagkaloob na pinagkasunduan. Hindi tulad ng cryptocurrency na batay sa katibayan ng trabaho (PoW) (tulad ng bitcoin), kung saan ang algorithm ay nagbibigay ng gantimpala sa mga kalahok na lutasin ang mga komplikadong mga cryptographical puzzle upang mapatunayan ang mga transaksyon at lumikha ng mga bagong bloke (ibig sabihin, pagmimina), sa PoS-based cryptocurrencies ang lumikha ng Ang susunod na bloke ay pinili sa pamamagitan ng iba't ibang mga kumbinasyon ng random na pagpili at kayamanan o edad (ie ang taya). 
Pinagmulan: [Proof-of-stake](https://en.wikipedia.org/wiki/Proof-of-stake) at Wikipedia.

#### Casper Proof of Stake
CAng Casper ay isang kasunduan sa pinagkaisahan na pang-ekonomiya batay sa seguridad. Nangangahulugan ito na ang mga node, na tinatawag na validators na may bonded, ay kailangang maglagay ng isang security deposit, isang pagkilos na tinatawag na bonding, upang maihatid ang pinagkasunduan sa pamamagitan ng paggawa ng mga bloke. Sa Casper estilo ng katibayan ng taya kahit sino ay maaaring lumahok sa block produksyon sa pamamagitan ng pag-post ng isang bono. Pagkatapos ng pag-post ng isang bono mayroon kang isang pagkakataon upang pumusta kung saan ang bloke ay isasama sa susunod. Ang mga insentibo ay tulad na gumawa ka ng pera sa pamamagitan ng pagtaya sa sa wakas na pinagkasunduan at mawalan ng pera sa pamamagitan ng pagtaya laban sa pinagkasunduan. Ang anumang crypto-graphically provable misbehavior ay nagreresulta sa pagkawala ng bono.
Pinagmulan: [How does the Casper proof of stake algorithm work?](https://ethereum.stackexchange.com/questions/102/how-does-the-casper-proof-of-stake-algorithm-work) on StackExchange.

#### Staking Tokens
Ang mga token ay ang mga kinakailangang magpatakbo ng pinagkasunduan, kabilang ang token ng RChain Rev. Kinakailangan ang isang staking token para magbayad para sa mga mapagkukunang node.
Pinagmulan: [Architecture Overview](http://rchain-architecture.readthedocs.io/en/latest/introduction/architecture-overview.html) in RChain Architecture.

#### Application Tokens
Ang mga token ng application ay opsyonal at maaaring kinakailangan upang magpatakbo ng ilang mga dApps. Maaaring ipakilala ang mga bagong token ng application sa anumang oras sa pamamagitan ng isang developer ng dApp, at katulad sa mga token ng ERC20 ng Ethereum.

#### Pinag-uusapan
Ang pinagkasunduan (Casper Proof-of-Stake validation / consensus Protocol) assures node consensus sa estado ng bawat blockchain. 
Pinagmulan: [Architecture Overview](http://rchain-architecture.readthedocs.io/en/latest/introduction/architecture-overview.html) in RChain Architecture.

#### Phlogiston
Ang Phlogiston ay ang panukalang-batas ng RChain ng halaga ng mga mapagkukunan (katulad ng gas sa Ethereum), at ito ay multi-dimensional at depende sa paggamit ng compute (depende sa pagtuturo), imbakan (depende sa laki at tagal), at bandwidth (kalidad-ng -service at throughput) mga mapagkukunan.
Pinagmulan: [Architecture Overview](http://rchain-architecture.readthedocs.io/en/latest/introduction/architecture-overview.html) in RChain Architecture.


## Namespace Logic

#### Namespace
Ang isang namespace ay isang koleksyon lamang ng mga pangalan. Ang lahat ng mga address ng blockchain ay mga pangalan. Ang isang koleksyon ay maaaring inilarawan sa ilang mga paraan. Ang isa sa kanila ay extensionally sa pamamagitan ng malinaw na spelling ang bawat item sa koleksyon. Ang isa pang paraan ay intensionally sa pamamagitan ng pagbibigay ng isang panuntunan o programa na alinman ay bumubuo ng koleksyon o kinikilala kapag ang isang item ay sa koleksyon o sa labas ng koleksyon. Ang mas kawili-wiling namespaces ay ang intensionally tinukoy na mga. Ang susunod na hakbang ay upang maugnay ang mga iyon sa mga gumagamit, mga kontrata, at mga node. Ang parehong mga gumagamit at kontrata ay nakikipag-ugnayan sa bawat isa sa pamamagitan ng mga pangalan. 
Pinagmulan: Forum discussion with @leithaus in [Discord #proof-of-stake](https://discordapp.com/).

#### Node
Ang mga node ay nagpapatunay ng mga transaksyon sa mga ibinigay na mga namespace, at ang mga transaksyon ay mga kaganapan sa buong pangalan (na ginagamit bilang mga channel). Ang anumang transaksyon na nagsasangkot ng dalawang magkahiwalay na mga namespaces ay dapat na paglingkuran ng isang koleksyon ng mga node na humahawak sa mga namespaces na iyon. Kung walang mga node na may hawak na mga transaksyon na pagsamahin ang mga namespaces, hindi maaaring mangyari ang transaksyon. Kung may mga node na pagsamahin ang mga namespaces, pagkatapos ay ang garantiya na algorithm ay tinitiyak na ang lahat ng mga node ay sumasang-ayon sa mga transaksyon. Mas partikular, sumasang-ayon sila sa mga nanalo sa bawat lahi. Kaya, hindi na maaaring maging double gastusin. Ang pinakamalaking banta ay upang makahanap ng mga composite namespaces na nagsilbi sa pamamagitan ng ilang mga validator. Sa kabutihang palad, maaari mong makita ang lakas ng validator sa likod ng isang namespace at magpasiya kung magtiwala ka sa namespace na iyon. 
Pinagmulan: Forum discussion with @leithaus in [Discord #proof-of-stake](https://discordapp.com/).

#### Composable Namespaces
Ang isang namespace ay maaaring maisip bilang isang URI (Uniform Resource Identifier), habang ang address ng isang mapagkukunan ay maaaring maisip bilang isang URL (Uniform Resource Locator). Ang path component ng URL, scheme: // a / b / c, halimbawa, ay maaaring matingnan na katumbas sa isang RChain address. Iyon ay, isang serye ng mga nested na channel na kumuha ng bawat mensahe, na may pinangalanang channel, a, bilang "top" na channel. Subalit, gayunpaman, ang mga landas ng URL ay hindi laging sumulat. Kumuha ng pamamaraan: // a / b / c at pamamaraan: // a / b / d. Sa isang tradisyonal na pamamaraan ng URL, ang dalawa ay hindi sumulat upang magbigay ng landas. Gayunpaman, ang bawat patag na landas ay awtomatikong isang landas ng puno, at, tulad ng mga puno, ang mga ito ay gumagawa upang magbigay ng bagong scheme ng puno: // a / b / c + d. Samakatuwid, ang mga puno ay makakapagbigay ng isang modelo ng komposable para sa pagtugon sa mapagkukunan. 
Pinagmulan: [Namespace Logic](http://rchain-architecture.readthedocs.io/en/latest/contracts/namespaces.html#composable-namespaces-resource-addressing) in RChain Architecture.


## Mga Ahente at Bot

#### Ahente
Sa agham ng computer, ang isang ahente ng software ay isang programa sa kompyuter na kumikilos para sa isang user o ibang programa sa isang relasyon ng ahensiya, na kinukuha mula sa Latin - agere (gawin): isang kasunduan na kumilos sa ngalan ng isa. Ang ganitong "pagkilos sa ngalan ng" ay nagpapahiwatig ng awtoridad na magdesisyon kung alin, kung mayroon man, ang aksyon ay angkop
Pinagmulan: [Agent](https://en.wikipedia.org/wiki/Agent) at Wikipedia.

#### Agent-based model
Isang modelo ng computational para sa pagtulad sa mga aksyon at pakikipag-ugnayan ng mga indibidwal. 
Pinagmulan: [Agent-based model](https://en.wikipedia.org/wiki/Agent-based_model) at Wikipedia.

#### Bisimilarity
Sa teoretikal na agham ng kompyuter, ang bisimulation ay isang binary na ugnayan sa pagitan ng mga sistema ng paglipat ng estado, na nag-uugnay sa mga sistema na kumikilos sa parehong paraan sa kamalayan na ang isang sistema ay simulates ang isa at kabaligtaran. Intuitively dalawang sistema ay bisimilar kung sila ay tumutugma sa bawat isa ay gumagalaw. Sa ganitong diwa, ang bawat isa sa mga sistema ay hindi maaaring makilala mula sa isa sa pamamagitan ng isang tagamasid. 
Pinagmulan: [Bisimilarity](https://en.wikipedia.org/wiki/Bisimulation) at Wikipedia.

#### Bot
Ang Internet bot, kilala rin bilang web robot, WWW robot o simpleng bot, ay isang software application na nagpapatakbo ng mga awtomatikong gawain (script) sa Internet. Kadalasan, ang mga bot ay nagsasagawa ng mga gawain na parehong simple at structurally paulit-ulit, sa isang mas mataas na rate kaysa sa magiging posible para sa isang tao lamang.
Pinagmulan: [Bot](https://en.wikipedia.org/wiki/Internet_bot) at Wikipedia.

#### Chatbot
(Kilala rin bilang isang talkbot, chatterbot, bot, IM bot, interactive agent, o Artificial Conversational Entity) ay isang programa sa computer na nagsasagawa ng isang pag-uusap sa pamamagitan ng pandinig o tekstuwal na pamamaraan. 
Pinagmulan: [Chatbot](https://en.wikipedia.org/wiki/Chatbot) at Wikipedia.

#### Cyborg
(Maikling para sa "cybernetic organismo") ay isang pagiging may parehong organo at biomechatronic bahagi ng katawan. Cyborg mula sa "cybernetic organsim". Cybernetic mula sa grey kybernetes na nangangahulugan ng steersman, governor, pilot, o timon. 
Pinagmulan:[Cyborg](https://en.wikipedia.org/wiki/Cyborg) at Wikipedia.

#### Intelligent agent
Isang autonomous, layunin-direktang entity na kung saan observes at kumikilos sa isang kapaligiran. 
Pinagmulan: [Intelligent agent](https://en.wikipedia.org/wiki/Intelligent_agent) at Wikipedia.

## RChain Development Milestones

#### Kumpletuhin ang tagatala
Ang foundational code ng RChain blockchain ay matagumpay na na-compile.

#### Kumpletong Node
Ang RChain blockchain ay sumasama sa mga kliyenteng node na tumatakbo sa mga remote machine.

#### Kumpletong Mercury
The full functionality of the Mercury milestone is ready to release.


### Project Double Linking
[This document is being referenced and curated by the VPG](https://chat.divvydao.net/video-team/channels/web-production-group). Your help and suggestions are most appreciated.
[Join us at Mattermost for the Social Ledger experment](https://chat.divvydao.net/signup_user_complete/?id=au57xr9fxbb65bmssnpz9xsy7h).
