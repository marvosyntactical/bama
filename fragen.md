# Gespraech 20.07.

* [DONE] einfache funktionen dicht in W\_H zu zeigen, beweis sollte straightforward sein, kann ich den auslassen? 
* [DONE] warum werden in huangonmfcbo überhaupt in 4.3 hilfsprozesse konstruiert?
* [DONE] muss ich zeigen dass euler maryuama (6.3) ergibt?
* [DONE] begin proof (beweisumgebung) / oder hfill
* [TODO] eindeutigkeitsbeweis von screenshot übernehmen 

# Gespraech 08.07.

* [TODO] funktional: zeige dass Fphi(f) = 0 forall phi => f löst VFP => f löst VFP
* [TODO] funktional name? herkunft der definition? basiert nicht direkt auf lyapunov operator
* [TODO] warum kann ich für Xalpha^4 bound mit schwach konv A -> infty laufen lassen?
* [TODO] ist meine aktuelle version des satzes korrekt? muss ich überhaupt aud kompatibilität mit schwacher top achten?
* [TODO] warum wird "stetigkeit der zeitlichen randmaße" benötigt? für wasserstein auf P(R^D)  zu wasserstein auf P(P(R^D)) überzugehen?

## Custom
* [DONE] "related work" auf deutsch => verwandte forschung scheint OK
* [DONE] formulierung: "wir" vs "ich"? => wir
* [DONE] randmaß oder bildmaß? => scheint okay
* [TODO] warum in folge N>2 immer? prüfe, ob notwendig?
* [DONE]  benoetige ich die aussagen in huang on mf cbo, lemma 2.3? (time marginal) => YES
* [DONE] time marginal proof: fubini: ich behaupte cb teilmenge von l1(f), wie komm ich darauf? => weglassen, fubini benoetigt nur bound
* [DONE] siehe in billingsley wie ich C metrisiere => skorokhod metrik
* [DONE] Noch einmal eine Frage zu Skorokhod: Warum kann das nicht immer verwendet werden, um von konv in dist auf Pfs konv überzugehen? wie die autoren das verwenden, scheint das extrem mächtig? => mächtig, aber benoetigt polnischen raum
* [DONE] funktional: integral von zB v\nabla x\phi sollte bzgl räumlichem maß sein, oder? => no
* [TODO] momentenabschätzungen: skalarprodukt von V mit Diag Matrix? macht keinen sinn -> schreibe als vektor, und füge in späteren umformungen hinzu! (summand wurde vergessen!)
* [DONE] in lipschitzstetigkeitsbeweis kriege ich konstante terme ... wie werde ich die los? brauche abschätzung von |x^\alpha| = c|z| ohne konstanten additiven faktor.
* [TODO] notag fuer keine equation tags
* [TODO] momentenabschätzung usw.: lange umformungen zwischendurch kommentieren

* [TODO] warum brauche ich für die abschätzung (3.21) (3.19)?
* [TODO] warum gilt (3.23) ohne konstante? wie schätze ich integral dfs ab?
* [TODO] zeige isomorphie von C(...R^2D) (mfpso + me) == C(...R^D)^2 (sznitman + mfpso) 
* [TODO] zeige isomorphie von P(C([0,T];R^D)) (mfpso + me) == C([0,T]; P(R^D)) (sznitman + mfpso) 
* [DONE] warum brauche ich polnisch? prohorov? etc




# Gespraech 01.07.

* [TODO] eindeutigkeit der lösung von VFP: Thm 4.3 aus Huang \& Qiu?
* [TODO] straffheitsthm 3.3 con2: abschätzung nicht korrekt, oder? können aber momentenabsch. anwenden (man müsste itoformel anwenden?); vorgehen der autoren funktioniert mit jensen
* [TODO] zweiter teil von stabilitätsbedingung: gronwall anwendbar?
* [TODO] 
* [TODO]
* [TODO]
* [TODO]
* [DONE] mean field limit definition von jabin problematisch/ungenau?
* [DONE] warum sind diese maße mu\_i schwache lösungen der PDEs
* [DONE] ist uniqueness von mckean prozess nicht identisch zu uniq von N < infty prozess bewiesen?


# Gespraech 10.06. 
* [TODO] skorokhod representation erlaubt nicht zu sagen dass f^N -> f Pfs! auch anderer Satz hilft nicht
* [TODO] wie kommt man auf (3.15) ? 
* [TODO] warum darf man in (3.17) den limes in A nehmen? braucht man dafür nicht noch einmal dominierte konvergenz o.Ä.?
* [TODO] woher kommt bound für M\_tN(\\phi)^2? muss noch argumentiert werden?
* [TODO]
* [TODO]
* [TODO]

# Gespraech 03.06.
* [DONE] big picture: background zu MFL: vlasov fokker planck eqn. version: wie allgemein recommended?
* [DONE] konkretheit von PDE: spektrum zwischen: 
* [DONE] FP -> VFP jabin (MFLreview) -> VFP bolley (swarming) -> SDPSO VFP
* [TODO] warum macht das auftauchen der distribution f die PDE nonlinear? passiert zB nicht in (Appendix von Huang on mf cbo)
* [DONE] wie sehen die lösungen des McKean Prozesses (^X, ^V, ^Y) aus? => bedingung law(Xt)=mu
* [TODO] kompaktheit: warum reicht es anderen häufungspunkt anzunehmen; wäre es nicht möglich, dass es keinen anderen häufungspunkt gibt?
* [DONE] ist es richtig, dass (3.19) dominierte konvergenz ist?
* [TODO] pavliotis stochastic processes Zitat - bedingungen an drift und diffusion für lösbarkeit von (V)FP


# Gespraech 20.05.

* [DONE] Warum wird 4tes Moment noch einmal extra abgeschaetzt?
* [TODO] wie teilfolge beheben?
* [TODO] siehe ende von proof: arbitrariness?
* [DONE] note on cbo charakterisierung von weak MF solns; scheint aus MF sde theory zu kommen?
* [DONE] in proof of thm 1 prüfen sie mit testfkt mit kmpkt traeger (wegen pde weak soln theory)

# Gespraech 13.05. 

* [TODO] kopplung unsauber: man kann jetzt nicht fN -> f P-f.s. sagen? brauchen billingsley Thm 6.8
* [TODO] mich verwirren die ausdrücke <phi,f>. sollte es nicht f(phi) sein?
* [TODO] woher kommt das funktional Fphi(f)? hat es einen namen?
* [TODO] wie komme ich mittels kopplung und funktional auf die neue momentenabschaetzung? 

* [TODO] was wird in huang & qiu, lemma 2.3 mit gamma noch bewiesen? => nichts
* [TODO] warum kann man w.l.o.g. sagen, dass teilfolge = folge? (falls folge nicht konvergiert?) => kann man nicht

* [TODO] gehe ich beim nachweis starker konvergenz richtig vor? (2ND? lipschitz? L|Z|²?) => ja

# Gespraech 29.04.

* [TODO] SDPSO Momentenabschaetzung kommentar Integral Fehler; neue überlegung
* [TODO] aldous kriterium 2 richtig aus billingsley uebernommen? (diskrete stoppzeiten?, fdds?)
* [TODO] ansatz doob mart ineq statt markov? andere ansaetze?
* [TODO] zu zeigen: Mdelta submart oder supermart, verwende Zt supermart!
* [TODO] diskret-zeit martingal? filtration? übertraegt sich markov prozess aus stab. thm. 3.5?
* [TODO] starke lösung: lipschitz auf zylindern pruefen: Zt vektor lokal abschaetzen
* [TODO] starke lösung: einordnen in rest des papers? nebenbemerkung?
* [TODO] proof thm.1: dominierte konvergenz womit?
* [TODO]
* [TODO]
* [TODO]


# Gespraech 22.04.
* [DONE] Anwendung von Gronwall laesst alpha(t) von N abhaengen, anders als geclaimt?
* [DONE] vorgehen mom.abschaetz. fuer SDPSO: betrachte [X\_t,V\_t] (2D) oder nur X\_t (D) ?
