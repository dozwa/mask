# Funktionale Anforderungen

1. **Wissensbasis**
   - Das System muss auf eine Wissensbasis basierend auf für die Kopfschmerzdiagnostik relevanten medizinischen Leitlinien zugreifen können.

2. **Symptomerfassung**
   - Das System muss einen Eingabedialog bereitstellen, um Symptome zu erfassen.

3. **Patientendatenerfassung**
   - Das System muss einen Eingabedialog bereitstellen, um anonymisierte Informationen über die Patient_Innen zu erfassen.

4. **Symptomanalyse**
   - Das System muss in der Lage sein, Symptome und Fallbeschreibungen von Patienten zu zu analysieren.
   
5. **Diagnosestellung**
   - Basierend auf den eingegebenen Informationen muss das System eine oder mehrere wahrscheinliche Diagnosen stellen können.
   - Das System muss dabei die relevanten Kriterien für die Entscheidungsfindung darlegen.
   - Wenn mehrere Diagnosen wahrscheinlich sind, soll das System mögliche Differenzierungsansätze vorschlagen, die eine präzisere Diagnose ermöglichen können.
   
6. **Interaktive Anfragen**
   - Bei unvollständigen Informationen soll das System in der Lage sein, gezielte Nachfragen zu stellen, um die Diagnose zu präzisieren.

7. **Klassifizierung von Kopfschmerzarten**
   - Das System muss eine Unterscheidung zwischen verschiedenen Kopfschmerzarten wie Migräne, Spannungskopfschmerzen und Cluster-Kopfschmerzen vornehmen.
     
8. **Behandlungsempfehlungen**
   - Das System soll Behandlungsempfehlungen basierend auf der gestellten Diagnose und aktuellen medizinischen Leitlinien geben können.

9. **Verständlichkeit**
   - Die Systemausgaben müssen so gestaltet sein, dass eine fachkundige Person die Systementscheidungen nachvollziehen kann.
   - Die Systemausgaben müssen in deutscher Sprache ausgegeben werden.

# Nicht-funktionale Anforderungen

1. **Benutzerfreundlichkeit**
   - Das System muss noch nicht über eine grafische Nutzeroberfläche verfügen.
   
2. **Performance**
   - Die Verarbeitung der eingegebenen Daten und Generierung von Diagnosen und Behandlungsempfehlungen sollte innerhalb von höchstens zwei Minuten durchgeführt werden.
   
3. **Datenschutz und Sicherheit**
   - Schutz der Patientendaten gemäß den geltenden Datenschutzrichtlinien, auch wenn in der Anfangsphase mit anonymisierten oder fiktiven Daten gearbeitet wird.
   
4. **Skalierbarkeit**
   - Das System muss nicht skalierbar sein.

5. **Reproduzierbarkeit**
   - Das System muss so gestaltet sein, dass die Systemausgaben reproduzierbar sind.

6. **Zuverlässigkeit**
   - Hohe Genauigkeit bei der Diagnosestellung und den Behandlungsempfehlungen, basierend auf aktuellen medizinischen Standards und Leitlinien.
