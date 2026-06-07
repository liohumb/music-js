# 🎹 music-js

> Un mini-instrument de musique qui tient dans un seul fichier HTML. Tu glisses la souris (ou ton doigt sur mobile), ça joue. Aucune dépendance, aucune installation.

---

## ✨ En bref

- **Position horizontale = la note**, calée sur une gamme pentatonique majeure → ça sonne toujours juste.
- **Position verticale = le volume** (silence en haut, fort en bas).
- **Multi-touch** : chaque doigt joue indépendamment, pour plaquer des accords.
- **5 instruments** synthétisés de zéro.
- **Effets** : réverbération générée en code, écho et filtre réglables en direct.
- **Visuel réactif** : chaque geste laisse une traînée lumineuse dont la couleur suit la fréquence jouée.

Le tout avec **Web Audio API native**, dans **un seul `index.html`**

## 🎮 Comment jouer

1. Ouvre la démo et **touche/clique** n'importe où.
2. **Glisse horizontalement** pour changer de note, **verticalement** pour le volume.
3. Sur mobile, **pose plusieurs doigts** pour jouer des accords.
4. En bas de l'écran, un panneau discret permet de choisir l'**instrument** et de régler **Cutoff**, **Écho** et **Réverb**.

## 🎻 Instruments

| Instrument  | Synthèse                                            | Caractère                    |
|-------------|-----------------------------------------------------|------------------------------|
| **Piano**   | Onde additive + deux « cordes » désaccordées        | Frappé, chaud, qui résonne   |
| **Guitare** | Triade majeure nylon, 3 cordes avec strum           | Accord gratté, doux et boisé |
| **Flûte**   | Sinus quasi pur + vibrato                           | Aérien, attaque douce        |
| **Basse**   | Dent de scie filtrée, transposée 2 octaves plus bas | Grave et rond                |
| **Lead**    | Deux dents de scie désaccordées + filtre résonant   | Synthwave qui chante         |

## 🧱 Stack

- **Vanilla JavaScript** (aucun framework)
- **Web Audio API**. Synthèse, filtres, réverb par convolution, le tout généré à la volée (pas un seul fichier audio).
- **Pointer Events**. Une seule API pour la souris et le tactile.

## 🚀 Lancer en local

Le plus simple : **double-clique sur `index.html`**

## 📄 Licence

Fais-en ce que tu veux :)

---

Codé par [&lt;humb/&gt;](https://github.com/liohumb) 🤘