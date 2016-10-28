# Konverze

### Do universálního systému spojek $$\{\lnot, \land, \lor\}$$
| Původní výraz                 | Jak?                                                           | Výsledek                                                                              |
| ---                           | ---                                                            | ---                                                                                   |
| $$A \land B$$; $$A \lor B$$       | Přidáním double negatives a aplikací prvního z nich na závorku | $$\lnot (\lnot A \lor \lnot B)$$; $$\lnot (\lnot A \land \lnot B)$$                       |
|                               |                                                                |                                                                                       |
| $$A \Rightarrow B$$             |                                                                | $$\lnot A \lor B$$                                                                      |
| $$A \Leftrightarrow B$$         |                                                                | $$(A \land B) \lor (\lnot A \land \lnot B)$$; $$(\lnot A \lor B) \land (A \lor \lnot B)$$ |
| $$\lnot (A \Leftrightarrow B)$$ | Aplikací negativu na závorku a eliminací                       | $$(A \land \lnot B) \lor (\lnot A \land B)$$                                            |

### Do universálního systému spojek $$\{\lnot, \Rightarrow\}$$
| Původní výraz          | Výsledek                                    |
| ---                    | ---                                         |
| $$A \land B$$            | $$\lnot (A \Rightarrow \lnot B)$$             |
| $$A \lor B$$             | $$\lnot A \Rightarrow B$$                     |
| $$A \Leftrightarrow  B$$ | $$(A \Rightarrow B) \land (B \Rightarrow A)$$ |