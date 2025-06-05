# P ≠ NP – Forschungsjournal Version 1.0  
**Lizenz:** MP-Lizenz 1.0 

---

## Elevator-Pitch  
Das **P ≠ NP-Problem** ist das Herzstück der theoretischen Informatik: Die Frage, ob alle Probleme, deren Lösungen sich schnell überprüfen lassen, auch schnell gelöst werden können. Meine Forschung verfolgt neue Wege zur Trennung dieser Klassen, dokumentiert gescheiterte Ansätze und bietet frische Perspektiven auf eines der größten ungelösten Probleme der Mathematik und Informatik.

---

## Willkommen im offiziellen Repository der P ≠ NP Forschung  
Dieses Projekt vereint Theoretische Informatik, Komplexitätstheorie, Mathematik und Logik zu einem interdisziplinären Versuch, das P ≠ NP-Problem besser zu verstehen – nicht nur durch erfolgreiche Beweisversuche, sondern vor allem durch die systematische Analyse von Fehlschlägen und Grenzen aktueller Methoden.

---

## 🔍 Das Problem  

**P vs. NP** fragt:  
Sind alle Probleme, deren Lösungen sich in polynomieller Zeit *prüfen* lassen (NP), auch in polynomieller Zeit *lösbar* (P)?  

Formell:  
\[
P \stackrel{?}{=} NP
\]

- **P:** Menge aller Entscheidungsprobleme, die in polynomieller Zeit deterministisch lösbar sind  
- **NP:** Menge aller Entscheidungsprobleme, deren Lösungen in polynomieller Zeit verifizierbar sind

---

## ⚠️ Gescheiterte Lösungsansätze – Warum sie scheiterten  

### 1. Strukturierte 3-SAT-Reduktionen  
Der Versuch, über eingeschränkte SAT-Fälle (z. B. Planar 3-SAT, Monotone SAT) eine Trennung von P und NP herzuleiten.  
**Grenze:** Keine Verallgemeinerung auf alle NP-Probleme möglich.

### 2. Diagonalargumente à la Turing  
Konstruktion von Turing-Maschinen, die sich selbst analysieren, um eine Trennung zu erzwingen.  
**Grenze:** Lieferten nur bereits bekannte Unentscheidbarkeitsresultate, keine neue Einsicht in P vs. NP.

### 3. Orakelmodelle (Relativierung)  
Verwendung von Orakeln, die in unterschiedlichen Modellen P = NP bzw. P ≠ NP erlauben.  
**Grenze:** Klassische Beweistechniken relativieren; somit ungeeignet für einen universellen Beweis.

### 4. Algebraische Ansätze (Natural Proofs)  
Versuche, Komplexitätsklassen mit algebraischen Methoden zu trennen.  
**Grenze:** Natural Proofs sind laut Razborov & Rudich eingeschränkt durch Annahmen der Kryptographiesicherheit.
