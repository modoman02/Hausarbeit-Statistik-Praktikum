---
title: "Latent-Class-Analyse im German Social Cohesion Panel (SCP):
Netzwerktypologien und Muster sozialer Einbettung"
subtitle:
author: "Nikolas Dippel & Moritz Dallmann"
date: "15.09.2025"
---


# Abstract

Dieser Bericht dokumentiert ein Projekt zur Typisierung persönlicher Netzwerke im **German Social Cohesion Panel (SCP)**. Ziel war es, *Netzwerktypen* anhand von Antworten zu alltäglichen Bekanntenkreisen zu identifizieren und deren soziostrukturelle Einbettung zu beschreiben. Auf Basis der gewichtsbereinigten Umfragedaten (N ≈ 26.195; vollständige Fälle: 9.848) wurden die Variablenblöcke zur Zusammensetzung der persönlichen Netzwerke (u. a. *pgrpknow*) aufbereitet. Nach einer explorativen Faktorenanalyse als heuristische Orientierung erfolgte eine **Latent-Class-Analyse (LCA)**, geschätzt mittels Maximum-Likelihood und EM-Algorithmus. Verglichen wurden u. a. 5‑, 7‑ und 12‑Klassen-Modelle anhand von AIC/BIC. Das **7‑Klassen‑Modell** zeigte den besten statistischen Fit bei zugleich guter Interpretierbarkeit.

Inhaltlich differenzieren sich die Klassen vor allem entlang **geographischer** (Stadt/Land, Ost/West) und **bildungs‑/migrationsbezogener** Dimensionen. Es finden sich keine *homogenen inklusiven politischen Netzwerke*, jedoch Klassen mit hoher Diversität sowie Konstellationen, die demographisch divers, in anderen Merkmalen jedoch homogen erscheinen. Tendenziell gilt: (a) je westdeutscher, desto christlicher; (b) je ländlicher, desto weniger Migrant*innen; (c) je großstädtischer, desto mehr Universitätsabschlüsse – verbunden mit eher linker politischer Orientierung. Wir diskutieren Mess‑, Design‑ und Interpretationsgrenzen (u. a. Definition „Bekannte“, Stichprobengewichte, vollständige Fälle) sowie theoretische und praktische Implikationen für Forschung zum gesellschaftlichen Zusammenhalt.

# Inhaltsverzeichnis

1. [Einleitung](#einleitung)  
2. [Datengrundlage](#datengrundlage)  
3. [Methodik](#methodik)  
4. [Ergebnisse](#ergebnisse)  
5. [Diskussion & Fazit](#diskussion--fazit)  
6. [Literaturverzeichnis](#literaturverzeichnis)  
7. [Anhang](#anhang)  

---

# Einleitung

## Problemstellung und Zielsetzung

Der gesellschaftliche Zusammenhalt wird wesentlich durch die Struktur und Qualität sozialer Beziehungen getragen. Persönliche Netzwerke – verstanden als die Gesamtheit der Menschen, denen Individuen im Alltag regelmäßig begegnen – bilden die „soziale Umwelt“, in der Normen, Informationen und Unterstützung zirkulieren. **Wie** diese Netzwerke zusammengesetzt sind (z. B. hinsichtlich Bildung, Migration, Religion, politischer Orientierung) und **wie homogen oder heterogen** sie ausfallen, ist für Integrations‑ und Segregationsprozesse zentral. Unser Projekt adressiert deshalb die Frage: **Wie lassen sich die persönlichen Netzwerke der Befragten im SCP typisieren, und durch welche Merkmale zeichnen sich die resultierenden Netzwerktypen aus?**

## Relevanz und theoretischer Hintergrund

Forschung zu Netzwerktypen und sozialem Zusammenhalt hebt hervor, dass **Homogenität** einerseits Vertrauensbildung, Stabilität und effiziente Koordination begünstigen kann, andererseits aber **Kontaktchancen über soziale Grenzen** (z. B. Bildung, Migration, Politik) reduziert und so Segregation verfestigt. Umgekehrt fördert **Heterogenität** die Exposition gegenüber alternativen Perspektiven, kann jedoch höhere Aushandlungskosten implizieren. In der Lebenslauf‑ und Altersforschung wurden LCA‑basierte **Netzwerktypologien** vielfach genutzt, um Muster sozialer Einbettung herauszuarbeiten und mit Wohlbefinden, Gesundheit oder Partizipation zu verbinden (z. B. Fiori et al., 2006; Miche et al., 2013). In der Kohäsionsforschung erlauben Netzwerktypen zudem Rückschlüsse auf **Brücken‑** (bridging) versus **Bindungskapital** (bonding) und die **Reichweite** individueller Informations‑ und Unterstützungsflüsse.

## Forschungsfragen

1. **Typisierung:** Welche latenten Klassen (Netzwerktypen) lassen sich im SCP identifizieren?  
2. **Charakterisierung:** Entlang welcher Merkmale (z. B. Stadt/Land, Ost/West, Bildung, Migration, Religion, Politik) differenzieren sich diese Klassen?  
3. **Bewertung:** Welche Klassenlösung bietet das beste Verhältnis aus **statistischem Fit** und **interpretativer Plausibilität**?  
4. **Implikationen:** Welche Konsequenzen ergeben sich für das Verständnis von **Homogenität**, **Heterogenität** und **Segregation** persönlicher Netzwerke im Kontext gesellschaftlichen Zusammenhalts?

## Aufbau des Berichts

Kapitel 2 beschreibt Datensatz, Erhebung und Variablen sowie die Datenaufbereitung. Kapitel 3 erklärt das methodische Vorgehen (EFA, LCA, Schätz‑ und Auswahlkriterien). Kapitel 4 berichtet die Ergebnisse inklusive Modellvergleich und inhaltlicher Interpretation. Kapitel 5 diskutiert theoretische und praktische Implikationen, Limitationen und Forschungsbedarf. Literatur und ergänzende Materialien schließen den Bericht ab.

# Datengrundlage

## Herkunft und Erhebungsdesign

Die Analysen basieren auf dem **German Social Cohesion Panel (SCP)** des Forschungsinstituts Gesellschaftlicher Zusammenhalt (FGZ). Erhoben werden repräsentative Befragungsdaten zur sozialen Einbettung, zu Werthaltungen und zur gesellschaftlichen Partizipation in Deutschland. Für unsere Fragestellung sind die Items zu **alltäglichen Kontakten („Bekannte“) und deren Merkmalsverteilung** zentral. Das Paneldesign erlaubt wiederholte Messungen; für die vorliegende Typisierung nutzen wir die Querschnittsinformation der betrachteten Welle.

## Stichprobe und Gewichtung

Die verfügbare **Bruttostichprobe** umfasst **N = 26.195** Beobachtungen. Zur Sicherung der Repräsentativität wurden **Design‑ und Poststratifizierungsgewichte** einbezogen (sofern verfügbar), welche zentrale **sozialstrukturelle Merkmale** (Alter, Geschlecht, Bildung, Region etc.) ausgleichen. Infolge strenger **Vollständigkeitskriterien** (listwise deletion) arbeiten die LCA‑Schätzungen mit **n = 9.848** vollständigen Fällen. Dieser Kompromiss gewährleistet konsistente Likelihood‑Berechnungen, geht aber mit Informationsverlust einher (siehe Limitationen).

## Variablen und Messung

Im Fokus stehen Variablen zur **Zusammensetzung des Bekanntenkreises**, u. a. der Block **„pgrpknow“**. Die Items erheben auf einer **6‑stufigen Likert‑Skala** (z. B. „keine“ bis „alle“) oder dichotom, **wie groß der Anteil** der Bekannten ist, der bestimmten Merkmalen entspricht (z. B. **Bildung**, **Migrationshintergrund/Staatsangehörigkeit**, **Religion**, **politische Orientierung**, **Stadt/Land**, **Ost/West**). Diese Operationalisierung approximiert **Anteile** im persönlichen Netzwerk und ermöglicht einen **relativen** Blick auf Diversität und Homogenität.

## Datenaufbereitung

Nicht‑Antwort‑Kodierungen (z. B. 7, −1, −2 … −9) wurden **gemäß Codebuch** in **fehlende Werte (NA)** überführt. Die anschließende **Explorative Datenanalyse (EDA)** prüfte Verteilungen und Plausibilitäten der Netzwerkmix‑Items und diente der **Heuristik** für die spätere Klassenzahl (u. a. Scree‑Plot, Parallelanalyse im Variablenraum). Für die LCA wurden die relevanten Items skaliert/kategorisiert und – falls erforderlich – **konsistent invertiert**, sodass höhere Werte inhaltlich größere Anteile des jeweiligen Merkmals widerspiegeln. **Gewichte** wurden in deskriptiven Auswertungen berücksichtigt; die LCA‑Schätzung erfolgte ungewichtet bzw. in Sensitivitätsläufen mit Gewichten (falls implementierbar), da LCA‑Software dies unterschiedlich unterstützt.

## Messlogik und Validität

Die gewählte **Definition von „Bekannten“** (kurze Gespräche bei zufälliger Begegnung) ist weitreichend und bildet **Alltagskontakte** ab. Dadurch werden Netzwerke nicht auf enge Freundschaften reduziert, sondern **breitere Interaktionssphären** erfasst. Zugleich besteht das Risiko, dass Befragte **Anteile schwer einschätzen** (z. B. politische Orientierung), was **klassische Messfehler** (Unschärfe/Antworttendenzen) bedingt. Diese Einschränkung wird in der Diskussion aufgegriffen.

# Methodik

## Analytischer Rahmen

Ziel der **Latent‑Class‑Analyse (LCA)** ist die Identifikation einer endlichen Anzahl **latenter, kategorialer Klassen** (C ∈ {1,…,K}), welche die **gemeinsame Verteilung** der beobachteten Indikatoren Y = (Y₁,…,Yₚ) erklären. Formal setzen wir *lokale Unabhängigkeit* voraus: Bedingt auf die Klasse C sind die Indikatoren unabhängig. Für polytome Items modellieren wir **Klassen‑spezifische Antwortwahrscheinlichkeiten** π_{jk}(r) = P(Y_j = r | C = k). Die **Klassenanteile** τ_k = P(C = k) gewichten die Mischverteilung. Die Parameter Θ = (τ_k, π_{jk}(r)) werden **per Maximum‑Likelihood** geschätzt, üblicherweise via **EM‑Algorithmus**.

## Heuristik der Klassenzahl (EFA)

Vor der LCA führten wir eine **explorative Faktorenanalyse (EFA)** durch, um die **dimensionalen Strukturen** der Itemmenge zu sondieren (Scree‑Plot nach Kaiser‑Kriterium, Parallelanalyse). Die EFA dient **nicht** der Klassifikation, liefert aber **Hinweise** auf Komplexität und potenzielle **Heterogenität** – beides relevante Informationen für die plausible Größenordnung von K.

## Schätzung und Modellwahl

Die LCA wurde für mehrere Kandidaten K ∈ {5, 7, 12} geschätzt. Als **Auswahlkriterien** nutzten wir **AIC** und **BIC** sowie inhaltliche **Interpretierbarkeit**. Die Gütemaße für zwei zentrale Kandidaten und eine „Überfitting“-Variante lauten (gerundet):

| Modell | BIC | AIC | G² | χ² |
|---|---:|---:|---:|---:|
| 5‑Klassen | 657 862.1 | 654 355.8 | 244 424.8 | 3.41 × 10²² |
| 7‑Klassen | **650 294.7** | **645 382.5** | 237 828.4 | 7.30 × 10²⁰ |
| 12‑Klassen | 668 004.9 | 659 578.2 | 239 683.4 | 5.16 × 10¹⁴ |

Das **7‑Klassen‑Modell** weist die **niedrigsten Informationskriterien** auf und erwies sich zugleich als **inhaltlich differenziert und noch gut kommunizierbar**. Das 12‑Klassen‑Modell erzielte keinen klaren inhaltlichen Mehrwert, litt jedoch unter sehr kleinen Klassen und erschwerter Interpretierbarkeit.

## Annahmen, Robustheit, Grenzen
- **Lokale Unabhängigkeit** kann bei nahe verwandten Items verletzt sein. Residualanalysen/Posterior‑Korrelationen können entsprechende Abweichungen anzeigen.  
- **Skaleninvarianz**: Unterschiedliche Antwortstile könnten Klassenartefakte erzeugen. Sensitivitätsanalysen (z. B. Rekodierungen, Bündelungen) mildern dieses Risiko.  
- **Gewichtete LCA** ist software‑ und implementierungsabhängig. Wir dokumentieren beide Pfade (deskriptiv gewichtet; LCA primär ungewichtet).  
- **Stabilität**: Startwert‑Diversifikation und Mehrfachläufe wurden genutzt, um Lokallösungen zu vermeiden.  
- **Validierung**: Die inhaltliche Validität stützt sich auf **Profilvergleiche** der Klassen sowie auf **Übergangsmatrizen** zwischen 5‑ und 7‑Klassen‑Lösungen (siehe Anhang).

# Ergebnisse

## Deskriptive Muster

Die EDA zeigt deutliche **Streubreiten** in den Anteilen bestimmter Merkmale innerhalb der Bekanntenkreise. Bereits deskriptiv treten **geographische Achsen** (Stadt/Land, Ost/West) sowie **bildungs‑/migrationsbezogene Unterschiede** hervor. Variablen wie **Bildung** und **Stadtgröße** korrelieren erwartungsgemäß: In Großstädten ist der Anteil an Universitätsabsolvent*innen im Bekanntenkreis höher; ländliche Räume weisen niedrigere Migrationsanteile auf. Diese Muster legen nahe, dass **mehr als vier Klassen** erforderlich sind, um die beobachtete Heterogenität angemessen zu erfassen.

## LCA‑Profilierung der 5‑, 7‑ und 12‑Klassen‑Modelle

**5‑Klassen‑Modell.** Diese Lösung bildet **grobe Großgruppen** ab (z. B. eher städtisch‑akademisch vs. eher ländlich‑traditionell), verwischt jedoch **nuancierte Mischtypen**. Für kommunikative Zwecke ist sie **übersichtlich**, unterschätzt aber **geographische und demographische Querstrukturen**.

**7‑Klassen‑Modell.** Diese Lösung bringt **zusätzliche Differenzierung**, insbesondere innerhalb **westdeutscher Netzwerke** (Stadt vs. Land) und entlang **Bildung/Migration/Religion**. Sie enthält (i) **eine Klasse mit hoher Diversität** über viele Merkmale hinweg, (ii) **eine Klasse**, die **demographisch divers** ist, in anderen Merkmalen jedoch **homogener**, sowie (iii) **keine** Klasse, die **politisch vollständig inklusiv** wäre – politische Zusammensetzungen bleiben tendenziell **schief**.

**12‑Klassen‑Modell.** Trotz weiter fallender G²‑Werte entstehen **kleine Splitterklassen** ohne konzeptionellen Zusatznutzen. Die **Kommunizierbarkeit** leidet, und Unsicherheit der Klassenzuordnung nimmt zu; wir betrachten diese Lösung deshalb als **überparametrisiert**.

## Tendenzen und Typenskizzen (7‑Klassen‑Modell)

Die folgenden **tentativen Etiketten** dienen der **kommunikativen Verdichtung**; sie ersetzen **nicht** die vollständigen Itemprofile im Anhang.

1. **Großstadt‑akademisch (links‑liberal geprägt):** Hoher Anteil Universitätsabschlüsse; überdurchschnittlich linke politische Orientierung; religiös weniger gebunden.  
2. **Ländlich‑traditionell (christlich geprägt):** Niedriger Migrationsanteil; höhere Kirchenbindung; politisch moderat bis konservativ.  
3. **Westdeutsch‑urban gemischt:** Heterogene Zusammensetzung, moderate Diversität; mittlere Bildungsanteile.  
4. **Ostdeutsch‑ländlich:** Geringere Migrationsanteile; niedrigere Hochschulanteile; traditionellere Muster.  
5. **Urban‑migrationsgeprägt:** Hoher Anteil Migrant*innen; höhere muslimische Anteile; politisch heterogen.  
6. **Breit diversifiziert:** Hohe Diversität über viele Merkmale; keine klare Dominanz eines Merkmals.  
7. **Demographisch divers, sonst homogen:** Alters‑/Bildungsmix, jedoch Homogenität in z. B. Religion/Region.

Diese Skizzen spiegeln die im Datensatz beobachteten **Tendenzen** wider: **Je westdeutscher, desto christlicher**; **je ländlicher, desto weniger Migrant*innen**; **je großstädtischer, desto mehr Universitätsabschlüsse**, was wiederum mit **linker politischer Orientierung** korrespondiert. Mit Blick auf **politische Inklusivität** fällt auf, dass keine Klasse **gleichmäßig politisch divers** ist – Hinweise auf **Clustering** und **Selektionsprozesse** in Alltagskontakten.

## Modellvergleich und Entscheidung

Die Informationskriterien (AIC/BIC) favorisieren eindeutig die **7‑Klassen‑Lösung**. Inhaltlich liefert sie **feinere Unterscheidungen**, ohne in schwer kommunizierbare Splitter zu verfallen. Die **5‑Klassen‑Lösung** bleibt als **kompakter Überblick** nützlich (z. B. für öffentliches Reporting), verfehlt jedoch mehrere Substrukturen. Das **12‑Klassen‑Modell** wird aus inhaltlichen Gründen verworfen.

## Übergänge zwischen 5‑ und 7‑Klassen

Eine **Übergangsanalyse** (Projekt‑intern erstellte Alluvial‑/Sankey‑Darstellung) zeigt, **welche 5‑Klassen‑Typen** sich im 7‑Klassen‑Modell **aufspalten** (z. B. westdeutsch‑urban → großstadt‑akademisch vs. urban‑gemischt). Dies stützt die **Interpretierbarkeit** des 7‑Klassen‑Modells als **Verfeinerung** anstelle eines Strukturbruchs.

# Diskussion & Fazit

## Interpretation im Lichte von Homogenität, Heterogenität, Segregation

Die Befunde legen nahe, dass **Alltagsnetzwerke** in Deutschland **geographisch und bildungsbezogen strukturiert** sind. **Brückenbeziehungen** über Stadt/Land und Bildungskluften sind vorhanden, aber **ungleich verteilt**. Die **Abwesenheit politisch vollständig inklusiver** Klassen spricht für **Echokammer‑Tendenzen** bereits in **schwachen Bindungen** – ein relevanter Befund für Debatten zu Polarisierung und „Filterblasen“. Zugleich existieren **hochdiverse** Klassen, die als **Ressourcenräume** für Perspektivwechsel fungieren könnten.

## Theoretische und praktische Implikationen

Theoretisch unterstreichen die Ergebnisse die **Koexistenz** von *bonding*‑ und *bridging*‑Strukturen in Alltagsnetzwerken. Praktisch implizieren sie, dass **Kontaktgelegenheiten** (z. B. in Vereinen, Bildungs‑, Kultur‑ und Quartiersprojekten) **gezielt** dort gestärkt werden sollten, wo **Diversitätsschnittstellen** fehlen (ländliche Räume; ostdeutsche Regionen mit niedrigen Migrationsanteilen; homogene religiöse Milieus). Kommunale Akteure könnten **niedrigschwellige Treffpunkte** fördern, die über **Bildungs‑ und Herkunftsgrenzen** hinweg wirken.

## Limitationen

1. **Vollständige Fälle (n = 9.848):** Mögliche **Selektionsartefakte**; Multiple Imputation könnte künftig geprüft werden.  
2. **Messunsicherheit:** Anteile im Bekanntenkreis sind **subjektive Schätzungen**; „Politik“ ist besonders **intransparent**.  
3. **Lokale Unabhängigkeit:** Potenzielle Verletzungen durch inhaltlich verwandte Items.  
4. **Gewichte/Schätzung:** Gewichtete LCA nicht in allen Pipelines verfügbar; Sensitivitätsläufe wünschenswert.  
5. **Querschnittlichkeit:** Aussagen zu **Kausalität** oder **Dynamik** sind eingeschränkt; Panel‑Analysen bieten Perspektiven.

## Ausblick

Künftige Arbeiten sollten (a) **gewichtete LCA** systematisch evaluieren, (b) **Validierungsanalysen** (z. B. externe Kriterien wie Vertrauen, Partizipation, Wohlbefinden) durchführen, (c) **Longitudinal‑LCA** und **Übergangswahrscheinlichkeiten** über Panelwellen schätzen und (d) **räumliche Kontexte** (z. B. Kreisebene) integrieren, um **Kontext‑Netzwerk‑Kopplungen** zu identifizieren.

## Schlussfolgerung

Das **7‑Klassen‑Modell** bietet den **besten Kompromiss** aus statistischer Güte und soziologischer Nuance. Es zeigt **erkennbare Strukturachsen** persönlicher Netzwerke in Deutschland und liefert **handlungsrelevante Hinweise** für Maßnahmen zur **Stärkung gesellschaftlichen Zusammenhalts** – insbesondere durch Förderung **diversitätsschaffender Kontaktgelegenheiten**.

# Literaturverzeichnis

- Bacher, J., & Vermunt, J. K. (2010). *Analyse latenter Klassen*. In C. Wolf & H. Best (Hrsg.), **Handbuch der sozialwissenschaftlichen Datenanalyse** (S. 553–574). VS Verlag für Sozialwissenschaften. https://doi.org/10.1007/978-3-531-92038-2_22  
- Bacher, J., & Wolff, H. G. (2010). *Hauptkomponentenanalyse und explorative Faktorenanalyse*. In C. Wolf & H. Best (Hrsg.), **Handbuch der sozialwissenschaftlichen Datenanalyse** (S. 333–365). VS Verlag für Sozialwissenschaften. https://doi.org/10.1007/978-3-531-92038-2_22  
- Ferguson, S. L., Moore, E. W. G., & Hull, D. M. (2020). Finding latent groups in observed data: A primer on latent profile analysis in Mplus for applied researchers. **International Journal of Behavioral Development, 44**(5), 458–468. https://doi.org/10.1177/0165025419881721  
- Fiori, K. L., Antonucci, T. C., & Cortina, K. S. (2006). Social Network Typologies and Mental Health Among Older Adults. **The Journals of Gerontology Series B, 61**(1), P25–P32. https://doi.org/10.1093/geronb/61.1.P25  
- Geiser, C. (2011). *Latent-Class-Analyse*. In C. Geiser (Hrsg.), **Datenanalyse mit Mplus: Eine anwendungsorientierte Einführung** (S. 235–271). VS Verlag für Sozialwissenschaften. https://doi.org/10.1007/978-3-531-93192-0_6  
- Lee, H., Kim, M. K., Park, H. Y., & Park, K. (2024). Social network typologies of Korean older adults and digital literacy differences: A latent class analysis. **Annals of Geriatric Medicine and Research, 28**(2), 134–143. https://doi.org/10.4235/agmr.23.0174  
- Teichler, N., Gerlitz, J.-Y., Cornesse, C., Dilger, C., Groh-Samberg, O., Lengfeld, H., Nissen, E., Reinecke, J., Skolarski, S., Traunmüller, R., & Verneuer-Emre, L. M. (2023). *Entkoppelte Lebenswelten? Soziale Beziehungen und gesellschaftlicher Zusammenhalt in Deutschland. Erster Zusammenhaltsbericht des FGZ*. Universität Bremen. https://doi.org/10.26092/elib/2517  

# Anhang

- A1. Scree‑Plot (EFA) und Parallelanalyse (EFA) – Projektabbildungen  
- A2. Itemverteilungen (Netzwerk‑Zugehörigkeiten, Teil 1 & 2) – Projektabbildungen  
- A3. LCA‑Profilplots für 5‑, 7‑ und 12‑Klassen – Projektabbildungen  
- A4. Übergangsdarstellung 5→7 Klassen (Alluvial/Sankey) – Projektabbildungen  
- A5. Tabellen: Informationskriterien, Klassenanteile, Posterior‑Wahrscheinlichkeiten  
