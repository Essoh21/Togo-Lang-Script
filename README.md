# Togo-Lang-Script
Togolang Script (TGS) est un système d'écriture translinguistique conçu pour offrir une orthographe simple, cohérente et adaptable à toutes les langues parlées au Togo. Ce projet vise à harmoniser la diversité linguistique en proposant une écriture standardisée mais flexible pour écrire dans n'importe laquelle des langues du Togo.
**Un système d'écriture unifié pour les langues togolaises**  

![Bannière ou logo du projet](https://via.placeholder.com/800x200?text=Togolang+Script)  
*Exemple : Illustration des caractères TGS appliqués à l'éwé et au kabyè*

---

## 📜 Projet  
**Togolang Script (TGS)** est une orthographe simplifiée et standardisée conçue pour :  
✔️ **Écrire toutes les langues du Togo** avec un seul système  
✔️ **Combler les lacunes** des alphabets latins traditionnels et faciliter l'écriture dans nos langues sur internet et dans les groupes sociaux 
✔️ **Faciliter l'apprentissage** grâce à une approche phonémique  

## 🌍 Contexte  
Le Togo compte **30+ langues** dont beaucoup n'ont pas d'écriture standardisée. Ce projet vise à :  
- Unifier les transcriptions  
- Préserver le patrimoine linguistique  
- Permettre l'édition numérique  

## 📜 Règles d'écriture TGS

### **Alphabet & Prononciation**  
- Utilise **25 lettres** (A-Z sauf **Q**)  
- **Prononciations spéciales** :  
  | Lettre | Sons possibles | Exemple |  
  |--------|----------------|---------|  
  | **e**  | é / è / e      |wezon, blewou (bonne arrivé, doucement en éwé|
  | **m**  | m / hm         ||  
  | **n**  | n / hn         | "nana" (enfant) |  
  | **o**  | o / oh         | "toro" (nuit) |  
  | **r**  | r / rh         | "raru" (soleil) |  
- **Pas d'accents** : Les sons "ou" s'écrivent `ou`
- **Les lettres h et n forment un nouveau son**: hn
   exemple: mila hnlon nou la seme la (nous allons écrire et nous comprendre (éwé))
- **K ↔ C interchangeables** : Ex: "koto" = "coto"  

### **Syntaxe d'entrée**  
Pour commencer à écrire dans une langue :  
1. **Première ligne** : `..` + **3-4 premières lettres de la langue**  
   - Exemples :  
     ```text  
     ..kab  (pour Kabyè)  
     ..ewe  (pour Éwé)  
     ..tem  (pour Tem)
     ..ife (pour ifè)
     ..adj (pour Adja)
     ..bas (pour bassar)
     ..mob (pour moba) 
     ```  
2. **Ligne suivante** : Texte dans la langue choisie  

### **Exemple Complet**  
```text  
..ewe  
Miawoe zon ! (Soyez les bien venu ou bonne arrivée!)  

## ✨ Fonctionnalités  
| Caractéristique | Description |  
|----------------|-------------|  
| 🔤 **Alphabet modulaire** | 24 caractères de base + extensions |  
| 🔉 **Notation phonétique** | 1 symbole = 1 son (API simplifié) |  
| 💻 **Clavier virtuel** | Pack d'installation pour Windows/Android |  

## 📚 Langues supportées  
```mermaid  
pie  
    title Répartition des langues  
    "Gbe (éwé, mina)" : 45  
    "Gur (kabyè, tem)" : 35  
    "Autres (akposso, ifè)" : 20  
