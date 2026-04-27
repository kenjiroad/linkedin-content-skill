# LinkedIn Algorithm Reference

## How the Algorithm Works

### Phase 1 — Initial Distribution Test (0-90 min)
1. Le post est montré à **8-15% de vos followers** comme test
2. L'algorithme mesure la vélocité de l'engagement (vitesse, pas juste volume)
3. Score calculé basé sur : saves (5x), comments >15 mots (4x), shares (3-4x), likes (1x)
4. Le dwell time (temps de lecture) est mesuré même sans interaction

### Phase 2 — Decision (90 min - 4h)
- Score élevé → Distribution élargie aux followers-of-followers
- Score faible → Distribution limitée, post "enterré"

### Phase 3 — Viral Loop (4h - 7 jours)
- Posts avec engagement continu reçoivent des boosts additionnels
- Les commentaires de personnes avec grande audience = multiplicateur supplémentaire
- Les reshares avec commentaire = signal de qualité fort

---

## Engagement Weights (Confirmed)

| Signal | Poids | Notes |
|--------|-------|-------|
| Save/Bookmark | **5x** | Le plus fort — montre une intention de réutilisation |
| Commentaire >15 mots | **4x** | Engagement qualitatif |
| Share avec commentaire | **3-4x** | Extension de réseau |
| Share sans commentaire | **2-3x** | Plus faible que share avec commentaire |
| Commentaire <15 mots | **2x** | "Super post !" ne vaut pas grand chose |
| Clic "voir plus" | **0.5-1x** | Signal d'intérêt, mais faible |
| Like | **1x** | Baseline |

---

## Format Performance

| Format | Reach Multiplier | Pourquoi |
|--------|-----------------|----------|
| Carousel PDF | 2.5-3.5x | Dwell time élevé, slides multiples |
| Native Video | 1.2-2x | Autoplay = dwell time forcé |
| Image + texte | 1-1.5x | Meilleur que texte seul pour stop-the-scroll |
| Texte seul | 1x | Baseline |
| Poll | 0.8-1.2x | Clic facile mais faible dwell time |
| Lien externe | 0.3-0.6x | LinkedIn pénalise le traffic sortant |

---

## Creator Topic Graph

L'algorithme construit un profil de "topics" pour chaque créateur :
- Postez sur les mêmes 2-3 sujets → l'algorithme vous associe à ces topics
- Distribution préférentielle vers les audiences intéressées par ces topics
- Pivot soudain de sujet = reset partiel de la distribution
- Régularité sur 3-4 semaines = "autorité de niche" dans l'algorithme

---

## Comment Quality Filter

LinkedIn filtre les commentaires par qualité depuis 2024 :
- Commentaires <5 mots : peu ou pas de valeur algorithmique
- Commentaires 5-15 mots : valeur modérée
- Commentaires >15 mots avec question = valeur maximale
- **Emoji seul = 0 valeur**

---

## External Links Penalty

- Liens dans le corps du post : **-40 à -60% de portée**
- **Workaround :** postez le texte sans lien, ajoutez le lien en premier commentaire
- Mentionnez "lien en commentaire" dans le post
- LinkedIn scanne le contenu pour détecter les URLs même partielles

---

## Posting Time Algorithm Factor

L'algorithme considère :
1. **Heure de publication** vs heure de connexion habituelle de votre audience
2. **Cohérence** — poster à la même heure régulièrement améliore la distribution
3. **Concurrence** — moins de posts au même moment = plus de visibilité
4. **Timezone** — l'algorithme adapte selon le fuseau de chaque utilisateur

Meilleure fenêtre globale B2B : **Mardi-Jeudi, 7h30-8h30 CET**

---

## What LinkedIn's Algorithm Does NOT Care About

- Le nombre de followers (la portée est proportionnelle, pas absolue)
- Les hashtags seuls (signal très faible depuis 2023)
- La longueur du post (la qualité prime)
- La fréquence de publication seule (sans Golden Hour routine)
