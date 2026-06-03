***POUR LE MJ***

## La Cote de Danger (CD)

La CD permet d'évaluer la menace d'une créature rapidement, en croisant ses deux attributs les plus importants : combien de temps elle résiste, et à quel point elle frappe fort.

### Formule

**CD = arrondi(PV ÷ 4) + (dégâts fixes × 2)**

| Créature              | PV  | Dégâts fixes | Moral | CD base | Modif       | CD final |
| --------------------- | --- | ------------ | ----- | ------- | ----------- | -------- |
| Bandit                | 4   | 1 PV         | 6     | 3       | —           | **3**    |
| Naga                  | 4   | 1 PV         | 7     | 3       | —           | **3**    |
| Garde du port         | 4   | 1 PV         | 8     | 3       | DEF 16 +1   | **4**    |
| Chien-loup            | 4   | 2 PV         | 6     | 5       | —           | **5**    |
| Soldat d'élite        | 8   | 2 PV         | 8     | 6       | —           | **6**    |
| Champion, vétéran     | 14  | 2 PV         | 9     | 8       | —           | **8**    |
| Shakir (capitaine)    | 22  | 2 PV         | 9     | 10      | DEF 15 +1   | **11**   |
| Ankheg                | 13  | 2 PV         | 7     | 7       | —           | **7**    |
| Troll des marais      | 22  | 3 PV         | 10    | 12      | Moral +1    | **13**   |

> **Modificateurs optionnels :**
> - +1 CD si DEF ≥ 15 (créature difficile à toucher)
> - +1 CD si la créature effectue 3 attaques ou plus par round
> - −1 CD si Moral ≤ 5 (fuira probablement avant la fin du combat)
> - +1 CD si Moral ≥ 10 (se bat jusqu'au bout — la menace est totale)

---

## Budget de Difficulté

Additionne la CD de tous les ennemis, et compare au budget de ton groupe.

> **Note de recalibrage :** comme les PJ n'ajoutent pas leur modificateur aux dégâts, les rencontres en haut de fourchette durent plus longtemps qu'avant. Un Équilibré à la limite haute peut jouer comme un Difficile bas si les ennemis ont beaucoup de PV ou une DEF élevée.

| Difficulté        | CD total pour N PJs |
| ----------------- | ------------------- |
| ☀️ **Facile**    | ≤ N × 4             |
| ⚔️ **Équilibré** | N × 5 à N × 8       |
| 🔥 **Difficile** | N × 8 à N × 12      |
| 💀 **Mortel**    | ≥ N × 12            |

> **Note :** le Moral réduit la difficulté effective — des ennemis à Moral 4–6 qui fuient à mi-combat transforment un Équilibré en Facile. Calibre la rencontre selon la ténacité des ennemis.

### Exemples pour un groupe de 3 PJs

| Budget    | Facile | Équilibré | Difficile | Mortel |
| --------- | ------ | --------- | --------- | ------ |
| **3 PJs** | ≤ 12   | 15 à 24   | 24 à 36   | ≥ 36   |

### Vérification sur des scénarios réels (3 PJs niveau 1)

| Rencontre                        | CD total | Verdict                                          |
| -------------------------------- | -------- | ------------------------------------------------ |
| 3 bandits                        | 9        | ☀️ Facile                                       |
| 2 brigands + 2 chiens-loups      | 16       | ⚔️ Équilibré (bas)                              |
| 6 bandits                        | 18       | ⚔️ Équilibré (bas)                              |
| 3 gardes du port                 | 12       | ☀️ Facile                                       |
| Shakir seul                      | 11       | ☀️ Facile (dangereux sur un PJ ciblé)           |
| Shakir + 3 bandits               | 20       | ⚔️ Équilibré                                    |
| 1 Ankheg                         | 7        | ☀️ Facile (attention à l'acide persistant)      |
| 2 Ankhegs                        | 14       | ⚔️ Équilibré (bas)                              |
| Shakir + 4 gardes du port        | 27       | 🔥 Difficile                                    |

---

## Ce Que les Chiffres Révèlent

**Les hordes de mooks sont dangereuses par accumulation.** 6 bandits font chacun 1 PV par touche — mais 6 attaques par round sur le groupe = jusqu'à 6 PV perdus en un round. Un PJ fragile peut tomber en 2 rounds si plusieurs bandits le ciblent.

**Un seul mook ne menace pas vraiment un aventurier.** 1 bandit fait 1 PV par touche. Un PJ à 8 PV peut encaisser 7 touches avant de tomber. Dans un face-à-face, un bandit seul n'est jamais réellement dangereux.

**Les élites sont dangereuses par leurs attaques multiples.** Shakir (2 attaques × 2 PV) peut infliger jusqu'à 4 PV en un round. Un Vestige à 6 PV peut tomber en 2 rounds si Shakir le cible exclusivement. Priorité tactique : neutraliser les élites en premier.

**Les effets persistants changent tout.** L'acide de l'Ankheg (1 PV/tour) s'accumule silencieusement. Un PJ qui ne se soigne pas perd des PV sans même être attaqué ce round.

---

## Le Facteur Moral

**Le Moral peut réduire un combat de moitié — littéralement.** Dès que la moitié du groupe ennemi tombe, chaque survivant teste son Moral individuellement (1d12, résultat > Moral = fuite). Certains tiennent, d'autres décrochent. C'est ça qui rend les mooks humains — et c'est aussi pour ça que les seuils de budget sont généreux.

- **Moral 4–6** : test fréquent, une fuite sur deux — un Équilibré joue souvent comme un Facile
- **Moral 7–9** : tiennent dans l'ensemble, quelques défections possibles
- **Moral 10–12** : se battent jusqu'au bout — la CD s'applique pleinement, sans réduction

---

## Règle des 3 Questions (Vérification Rapide)

Si tu n'as pas envie de calculer des CD, ces 3 questions suffisent :

**1. Combien de PV par round le groupe peut-il perdre ?**
Compte le nombre total d'attaques ennemies × leurs dégâts fixes. Si le résultat dépasse les PV du PJ le plus fragile en 2 rounds, un PJ risque de tomber.

**2. Combien de rounds dure le combat ?**
PV total ennemis ÷ dégâts estimés du groupe (environ 5–7 dégâts par round pour 3 PJ niveau 1 actifs, selon DEF ennemie, armes, sorts et capacités)
- ≤ 2 rounds → Facile
- 3–4 rounds → Équilibré, 1–2 PJs blessés sérieusement
- 5+ rounds → Difficile à Mortel

**3. Les ennemis sont-ils en surnombre ?**
Si le nombre d'ennemis ≥ nombre de PJs × 2, le groupe absorbe un volume de dégâts qui dépasse sa capacité de réponse, même si chaque ennemi est un simple mook.
