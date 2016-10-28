Název                   | Symbol              | Definice
---                     | :-:                 | ---
[NOT][]                 | $$\lnot$$           | $$\neg A$$ je **true**, pokud $$A$$ je _**false**_.
[AND][]                 | $$\land$$           | $$A \land B$$ je **true** pouze pokud jsou oba výroky **true**.
[OR][]                  | $$\lor$$            | $$A \lor B$$ je **true** pokud je alespoň jeden z výroků **true**
                        |                     |
[NAND][]                | $$\uparrow$$[^1]        | $$A \uparrow B$$ je **true**, pokud je alespoň jeden z výroků _**false**_.
[NOR][]             | $$\downarrow$$[^2]      | $$A \downarrow B$$ je **true**, pokud jsou oba výroky _**false**_
                        |                     |
[implikace][]           | $$\Rightarrow$$     | $$A \Rightarrow B$$ je _**false**_ pouze tehdy, pokud $$A$$ je **true** a $$B$$ je _**false**_.
[ekvivalence][]         | $$\Leftrightarrow$$ | $$A \Leftrightarrow B$$  je **true**, pokud jsou oba výroky _**false**_, nebo jsou oba výroky **true**.
                        |                     |
tautologie              | $$\top$$            | Formule, která je vždy **true**
kontradikce             | $$\bot$$            | Formule, která je vždy **_false_**
                        |                     |
[logický důsledek][]    | $$\models$$         | Formule $$B$$ je logickým důsledkem formule $$A$$, právě když pro každé ohodnocení $$v$$, pro které $$v(A) = 1$$, je i $$v(B) = 1$$. Píšeme $$A \models B$$. Říkáme též $$B$$ vyplývá z $$A$$.; Nebo jinak: $$A \models B$$, právě když uKNT/uDNT $$A$$ a $$B$$ obsahují stejné klausule/mintermy
[logická ekvivalence][] | $$\equiv$$, $$|=|$$ | Formule $$A$$ a $$B$$ jsou logicky ekvivalentní právě tehdy, když pro každé ohodnocení $$v$$ je $$v(A) = v(B)$$. Píšeme $$A \equiv B$$.; Nebo jinak: $$A \equiv B$$, právě když všechny klausule/mintermy v uKNT/uDNT $$A$$ jsou obsaženy i v uKNT/uDNT $$B$$

[NOT]: https://en.wikipedia.org/wiki/Negation
[AND]: https://en.wikipedia.org/wiki/Logical_conjunction
[OR]: https://en.wikipedia.org/wiki/Logical_disjunction
[^1]: Shefferův symbol
[NAND]: https://en.wikipedia.org/wiki/Sheffer_stroke
[^2]: Piercova šipka
[NOR]: https://en.wikipedia.org/wiki/Logical_NOR
[implikace]: https://en.wikipedia.org/wiki/Material_conditional
[ekvivalence]: https://en.wikipedia.org/wiki/If_and_only_if
[logická ekvivalence]: https://en.wikipedia.org/wiki/Logical_equivalence
[logický důsledek]: https://en.wikipedia.org/wiki/Syllogism