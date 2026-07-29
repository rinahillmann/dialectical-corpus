# The Topics corpus: what's in here and how it fits together

This repository collects thirteen texts tracing how Aristotle's *Topics* (his treatise on dialectical reasoning, i.e. how to argue persuasively from generally accepted premises rather than strict logical proof) was translated and commented on across Greek, Latin, Arabic, and Hebrew over roughly 1,500 years.

A quick note on vocabulary, since the folder names use it constantly:
- **Translation**: rendering the same text into a new language.
- **Commentary**: a separate text written to explain or gloss an existing one, in the same or a different language. A **super-commentary** comments on a commentary, rather than on the original.
- Several folders are both, or something in between — that's flagged where it applies.

## Two branches

**1. The core line (Greek → Latin, Greek → Arabic)**
Aristotle's Greek original sits at the root. From there the tradition splits three ways: a Greek commentary, an Arabic translation, and a Latin line via Boethius. Cicero's *Topica* is a related but independently written work (not a translation of Aristotle, but a Roman rhetorical handbook drawing on the same logical material) with its own Latin commentary tradition.

**2. The Hebrew branch (skips Latin entirely)**
Two further works reach Hebrew readers directly from Arabic, without ever passing through Latin: al-Farabi's own treatise on dialectic (*Kitab al-Jadal*), and Averroes' *Middle and Short Commentaries* on the *Topics*. Al-Farabi's Arabic original is in the corpus. Averroes' *Short Commentary* is present in Arabic; the *Middle Commentary* for now only through its Hebrew translation (and a Hebrew super-commentary on that translation).

## Folder by folder

| # | Text | Language | Relation |
|---|------|----------|----------|
| 01 | Aristotle, *Topics* | Greek | Original text |
| 02 | Alexander of Aphrodisias, commentary | Greek | Comments on 01 |
| 03 | Al-Dimashqi, translation | Arabic | Translates 01 |
| 04 | Boethius, *De topicis differentiis* | Latin | Between translation and commentary on 01 |
| 05 | Abaelard, commentary | Latin | Comments on 04 |
| 06 | Cicero, *Topica* | Latin | Independent work, related to 01 |
| 07 | Boethius, commentary on Cicero | Latin | Comments on 06 |
| 08 | Al-Farabi, *Kitab al-Jadal* | Arabic | Original text |
| 09 | Anonymous translation of 08 | Hebrew | Translates 08 |
| 10 | Qalonymos ben Qalonymos, translation of Averroes' Middle Commentary | Hebrew | Translates Averroes' Middle Commentary (Arabic original not in corpus) |
| 11 | Todros Todrosi, super-commentary | Hebrew | Comments on 10 |
| 12 | Averroes, Short Commentary on the Topics | Arabic | Comments on 01 (via the Arabic tradition) |
| 13 | ibn Tibbon, translation of 12 | Hebrew | Translates 12 |

Folders 09, 10, and 13 each contain multiple manuscript witnesses (separate .txt files) rather than a single edited text, since no standard critical edition exists for those.

## Open items

- **04 (Boethius)** doesn't fit cleanly into "translation" or "commentary" — it's closer to a Latin reworking of Aristotle's material. Worth a one-line caveat wherever this corpus is described publicly.
- **Averroes' Middle Commentary** still has no Arabic original in the corpus — only its Hebrew translation (10) and the Hebrew super-commentary on that translation (11) are present.

## Why this matters as a set

The point of grouping these thirteen together isn't just that they all touch Aristotle's *Topics* — it's that they let you watch a single argumentative tradition move across religious and linguistic communities that didn't otherwise read each other's languages: Byzantine Greek commentators, Latin scholastics, Arabic Aristotelians, and Hebrew-reading Jewish philosophers in Provence and Spain, each adapting the same material for their own intellectual context.
