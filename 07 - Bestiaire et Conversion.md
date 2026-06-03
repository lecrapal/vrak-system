***POUR LE MJ***

## Construire une Créature

Chaque créature a besoin des éléments suivants pour fonctionner dans le système :

| Élément                   | Description                                      |
| ------------------------- | ------------------------------------------------ |
| **PV**                    | Points de Vie — résistance physique              |
| **DEF**                   | Défense = 10 + mod AGI + bonus d'armure          |
| **FOR / AGI / ESP / PRÉ** | Modificateurs de −1 à +4                         |
| **Attaque(s)**            | Dégâts fixes en PV + stat utilisée (FOR ou AGI) |
| **Moral**                 | Score 1–12 (élevé = ne fuit pas)                 |
| **Capacités**             | Tout ce qui sort de l'ordinaire (facultatif)     |

### Format standard d'un bloc de stats

```
### Nom de la créature
*Une ligne de flavour text*

PV : X  |  DEF : X  |  Moral : X/12
FOR +X  |  AGI +X  |  ESP +X  |  PRÉ +X

Attaque : [Nom] — X PV (FOR / AGI)
Capacités : ...
```

### Exemples de créatures

**Soldat ordinaire**
> PV : 8 | DEF : 13 | Moral : 7/12
> FOR +1 | AGI +0 | ESP +0 | PRÉ +0
> Attaque : Épée — 2 PV (FOR)

**Brigand lâche**
> PV : 5 | DEF : 11 | Moral : 3/12
> FOR +0 | AGI +1 | ESP −1 | PRÉ −1
> Attaque : Dague — 1 PV (AGI)

**Troll des marais**
> PV : 22 | DEF : 12 | Moral : 10/12
> FOR +3 | AGI −1 | ESP −1 | PRÉ −1
> Attaque : Griffes — 3 PV (FOR) | Morsure — 2 PV (FOR)
> Capacités : *Régénération* — récupère 3 PV au début de son tour (stoppé par le feu ou l'acide)

---

## Conversion D&D 5e → Ce Système

La 5e est le système le plus documenté. Presque toutes les créatures imaginables y existent.

**Où le trouver :** https://www.aidedd.org/dnd-filters/monstres.php

### Étape 1 — Stats de base

| D&D 5e                | Ce système | Formule                                       |
| --------------------- | ---------- | --------------------------------------------- |
| Points de vie         | PV         | Voir table par CR ci-dessous                  |
| CA                    | DEF        | Direct, même valeur                           |
| Mod FOR               | Mod FOR    | Direct, plafonner à +4                        |
| Mod DEX               | Mod AGI    | Direct, plafonner à +4                        |
| max(Mod INT, Mod SAG) | Mod ESP    | Garder le plus élevé des deux, plafonner à +4 |
| Mod CHA               | Mod PRÉ    | Direct, plafonner à +4                        |
| —                     | Moral      | Estimer selon la créature (voir table)        |

### Étape 2 — Conversion des PV

| CR      | Conversion PV   |
| ------- | --------------- |
| 0 – 1/4 | HP ÷ 4, min 4   |
| 1/2+    | HP ÷ 3, arrondi |

### Étape 3 — Dégâts fixes

**Les ennemis n'ont pas de dés de dégâts.** Chaque attaque inflige un nombre fixe de PV, calculé à partir des dégâts moyens de l'attaque en 5e :

> **Dégâts moyens 5e = dé moyen + modificateur**
> *(ex : d6+3 → 3,5 + 3 = 6,5)*

| Dégâts moyens par attaque (5e) | PV fixes infligés |
| ------------------------------ | ----------------- |
| 1 – 5                          | **1 PV**          |
| 6 – 10                         | **2 PV**          |
| 11 – 15                        | **3 PV**          |
| 16+                            | **4 PV**          |

Pour les effets persistants (acide, poison, feu) : appliquer la même table sur les dégâts du tick, et noter comme **Condition : X PV/tour**.

> **Important :** les PJ ne rajoutent pas leur modificateur aux dégâts. Leur modificateur sert uniquement à savoir si l'attaque touche. En cas de touche, ils lancent seulement les dégâts de l'arme ou du sort.

### Estimation du Moral

| Type de créature                   | Moral estimé        |
| ---------------------------------- | ------------------- |
| Mort-vivant, Artificiel, Fanatique | 12 (ne fuit jamais) |
| Fiélon, Géant, Monstre sauvage     | 9–11                |
| Bête ordinaire                     | 5–7                 |
| Humanoïde mercenaire               | 6–8                 |
| Gobelin, créature opportuniste     | 3–5                 |
| Lâche ou proie                     | 1–3                 |

---

## Règles de Moral en Jeu

Quand la situation dérape (moitié des alliés hors combat, chef tué, situation désespérée), le MJ lance **1d12** :
- **Résultat > Moral** : la créature fuit, se rend ou cherche un compromis
- **Résultat ≤ Moral** : elle tient bon

Les créatures avec Moral 12 ne font jamais ce jet. Celles à Moral 1–2 le font dès la première difficulté.

---

## Conseils pour Créer ses Propres Créatures

- **PV bas** (3–8) : créature fragile — bandits, animaux, mooks
- **PV moyen** (9–18) : créature robuste — élites, vétérans, monstres courants
- **PV élevé** (19–30+) : boss, monstres légendaires, créatures épiques

- **DEF 10–11** : créature non blindée, facile à toucher
- **DEF 12–14** : armure légère à intermédiaire ou agilité naturelle
- **DEF 15–17** : armure lourde ou créature très difficile à toucher

- **Un seul modificateur à +3 ou +4** suffit pour définir l'identité d'une créature.
- **Capacités spéciales** : une ou deux max. Une capacité forte vaut souvent mieux que beaucoup de stats élevées.
