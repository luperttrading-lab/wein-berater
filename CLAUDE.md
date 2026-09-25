# Wein-Berater – Hinweise für Claude Code

## Kostenanzeige

Unter jede Antwort genau eine Kostenzeile:

1. `python3 tools/kosten.py` ausführen.
2. Die Ausgabe **wörtlich** als letzte Zeile der Antwort setzen – roh, nicht in einem
   Codeblock, nicht umformatieren, nicht schätzen, nichts dahinter.
3. Läuft das Skript nicht (kein Sitzungsprotokoll, andere Umgebung), das offen sagen
   statt eine Zahl zu erfinden.

Optionen: `-v` zeigt Summen je Tag und Modell, `--ttl5` rechnet mit dem
Fünf-Minuten-Cachepreis statt dem Stundencache.
