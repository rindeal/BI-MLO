# Slovník

Výraz                                       | Význam                                                                            | Příklad
---                                         | ---                                                                               | ---
**Výrok**                                   | Výrokem je každá oznamovací věta, u které se lze ptát, zda je či není pravdivá.   | "Číslo 2 je sudé a zároveň je liché."
**Prvotní výrok** (atomický)                | Dále nedělitelný výrok. Jedná se v jistém smyslu o to nejjednodušší konstatování. | "Je rok 2014.", "2 + 2 = 5"
                                            |                                                                                   |
**Prvotní formule**                         | Prvotní výroky označené velkými tiskacími písmeny.                                | $$A$$, $$B$$, $$C$$
**Formule**                                 | Prvotní formule a formule poskládáné pomocí logických spojek a závorek.           | $$A$$, $$B$$, $$A \land B$$, $$\lnot A \Rightarrow B$$, $$(A \Rightarrow B) \lor \lnot ((A \land B) \lor B)$$
**Podformule**                              | Každá část formule, která je sama formulí.                                        | Formule: $$\lnot (A \land B) \Leftrightarrow (C \Rightarrow A)$$, podformule: $$A$$, $$B$$, $$C$$, $$A \land B$$, $$\lnot (A \land B)$$, $$C \Rightarrow A$$
**Splnitelná formule**                      | Formule, která je pravda alespoň pro jedno ohodnocení, tedy všechny formule kromě kontradikcí. | $$A$$, $$A \land B$$ a nesplnitelné $$A \land \lnot A$$
**Instance formule**                        | Formule, která vznikne nahrazením **prvotních formulí** jinými formulemi a to tak, že všechny výskyty jedné prvotní formule jsou nahrazeny jinou, jednou a tou samou formulí. | Instance $$\lnot A \lor (B \Rightarrow A)$$: $$\lnot C \lor (D \Rightarrow C)$$ nebo $$\lnot (A \land B) \lor (C \Rightarrow (A \land B))$$
                                            |                                                                                   |
**Pravdivostní ohodnocení**                 | Funkce $$v$$ z množiny prvotních formulí do množiny $$\{0,1\}$$.                  | Pokud pro formuli $$A$$ platí $$v(A) = 1$$, řekneme, že $$A$$ je **pravdivá** při ohodnocení $$v$$. Pokud platí $$v(A) = 0$$, řekneme, že $$A$$ je **_nepravdivá_** při ohodnocení $$v$$.
**Teorie**                                  | Množina formulí | $$T = \{A, B, \lnot A \lor \lnot B\}$$
**Axiom**                                   | Formule obsažená v teorii                                                         |
**Splnitelná teorie**                       | Teorie $$T$$ je splnitelná, právě když existuje ohodnocení $$v$$ prvotních formulí, pro které jsou **všechny** formule teorie **pravdivé**. Řekneme, že $$v$$ splňuje $$T$$. | $$T = \{A, B, A \land B, C \lor B\}$$ splnitelná pro $$(1,1,1)$$, $$(1,1,0)$$
                                            |                                                                                   |
**Literál**                                 | Prvotní formule nebo její negace.                                                 | $$A$$, $$B$$, $$\lnot C$$
**Minterm**                                 | Literál nebo **konjunkce** několika literálů                                      | $$A \land B$$, $$B \land \lnot C$$
**Klausule**                                | Literál nebo **disjunkce** několika literálů                                      | $$A \lor B$$, $$B \lor \lnot C$$
                                            |                                                                                   |
**KNT** (Konjunktivní normální tvar)        | Formule je v _KNT_, jestliže je klausulí nebo konjunkcí několika klausulí.        | $$(A \lor \lnot B) \land C$$, $$A \land \lnot B$$, $$A \lor B$$
**uKNT** (Úplný konjunktivní normální tvar) | Formule je v _uKNT_, jestliže je v _KNT_ a ve všech klausulích se vyskytují stejné prvotní formule. | $$(A \lor \lnot B \lor C) \land (\lnot A \lor \lnot B \lor C)$$
**DNT** (Disjunktivní normální tvar)        | Formule je v _DNT_, jestliže je mintermem nebo disjunkcí několika mintermů.       | $$(A \land \lnot B) \lor C$$, $$A \land \lnot B$$, $$A \lor B$$
**uDNT** (Úplný disjunktivní normální tvar) | Formule je v _uDNT_, jestliže je v _DNT_ a ve všech mintermech se vyskytují stejné prvotní formule. | $$(A \land \lnot B \land C) \lor (\lnot A \land \lnot B \land C)$$