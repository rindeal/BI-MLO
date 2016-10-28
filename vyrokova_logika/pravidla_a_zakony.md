# Pravidla a zákony

### Identita (eliminace)
- $$A \land \top \equiv A$$
- $$A \land \bot \equiv \bot$$
- $$A \lor \top \equiv \top$$
- $$A \lor \bot \equiv A$$

### Zákon vyloučeného třetího (vyloučení sporu)
- $$A \lor \lnot A \equiv \top$$ - vždy je něco z leva nebo z prava **true**

### Zákon dvojí negace
- $$A \equiv \lnot (\lnot A)$$

### Asociativní zákony (závorky)
- $$A \land (B \land C) \equiv (A \land B) \land C$$
- $$A \lor (B \lor C) \equiv (A \lor B) \lor C$$
- $$A \Leftrightarrow (B \Leftrightarrow C) \equiv (A \Leftrightarrow B) \Leftrightarrow C$$
    
### Komutativní zákony (změna stran)
- $$A \land B \equiv B \land A$$
- $$A \lor B \equiv B \lor A$$
- $$A \Leftrightarrow B \equiv B \Leftrightarrow A$$

### Distributivní zákony
- $$A \lor (B\land C) \equiv (A \lor B) \land (A\lor C)$$
- $$A \land (B\lor C) \equiv (A \land B) \lor (A\land C)$$
- používají se hlavně při hledání DNT/KNT, pokud formule není celá znegovaná

### Zákony absorpce
- $$A \land (A \lor B) \equiv A$$
- $$A \lor (A \land B) \equiv A$$

### De Morganovy zákony
- $$\lnot (A \lor B) \equiv \lnot A \land \lnot B$$
- $$\lnot (A \land B) \equiv \lnot A \lor \lnot B$$
- používají se hlavně při hledání DNT/KNT, pokud je celá formule znegovaná

### [Modus ponens](https://en.wikipedia.org/wiki/Modus_ponens)
- $$(A \Rightarrow B) \land A \models B$$
- $$((A \Rightarrow B ) \land A ) \Rightarrow B$$
- opakem je [Modus tollens](https://en.wikipedia.org/wiki/Modus_tollens)

### [Kontrapozice](https://en.wikipedia.org/wiki/Contraposition)
- invert and flip
- $$A \Rightarrow B \equiv \lnot B \Rightarrow \lnot A$$