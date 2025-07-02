
<!-- Inline CSS styles -->
<style>
  /* Big headings in primary blue */
  h1, h2 {
    color: #2a6496;
  }
  
  /* Normal text in dark color */
  p, li, summary {
    color: #333;
  }
  
  /* Add spacing between list items */
  li {
    margin-bottom: 8px;
  }
  
  /* Ensure images are responsive */
  img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 1rem auto;
  }
  
  /* Dropdown pointer cursor */
  summary {
    cursor: pointer;
    font-weight: bold;
  }
  
  /* Center content */
  .center {
    text-align: center;
  }
  
  /* System diagram */
  .system-img {
    max-width: 100%;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    border-radius: 8px;
  }
  
  /* Team table styling */
  table {
    width: 100%;
    margin: 2rem auto;
  }
  
  td {
    padding: 1rem;
    text-align: center;
    vertical-align: top;
  }
  
  /* Team logo consistent sizing */
  .team-logo {
    height: 80px;
    width: auto;
    max-width: 150px;
    object-fit: contain;
    margin-bottom: 1rem;
  }
  
  /* Team member photo consistent sizing */
  .team-photo {
    height: 80px;
    width: 80px;
    border-radius: 50%;
    object-fit: cover;
    margin: 0.5rem auto;
    display: block;
  }
  
  /* Institution name consistent height */
  .institution-name {
    min-height: 3rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin-bottom: 1rem;
  }
</style>

<p style="font-size: 1.2em; color: #666; text-align: center; font-style: italic;">
Digitale Soforthilfe bei problematischen Inhalten, Förderung der Selbstwirksamkeit von jungen Nutzer:innen, und institutionelle Vernetzung für eine sichere Online-Schweiz
</p>

---

## 📋 Projekt-Überblick

### Das Problem: Online-Gefahren für Junge Nutzer:innen
Kinder und Jugendliche stossen immer häufiger auf problematische Inhalte wie hate speech, Falschinformationen oder extreme Inhalte in sozialen Medien. Bestehende Schutzmassnahmen zielen oft auf Prävention ab - jedoch fehlt es an direkter Unterstützung für Kinder und Lehrpersonen nach akuter Konfrontation mit solchen Inhalten.

### Unsere Lösungsansatz: Flag&Safe
Wir entwickeln mit "Flag&Safe" eine kindgerechte Plattform, auf der junge Nutzer:innen bedenkliche Online-Inhalte einfach und sicher melden können. Die Plattform führt eine automatische Vorprüfung durch und leitet dringende Fälle an ein Netzwerk von Fachpersonen (z.B. Schulpsycholog:innen, Beratungsstellen) weiter. Dabei bleiben Daten und Metadaten der Inhalte erhalten, was diese Fachpersonen befähigt, schnell und unkompliziert einzugreifen.

<details>
<summary><strong>Mehr zur Vision</strong></summary>

In jüngster Zeit häufen sich Berichte über radikalisierende Inhalte in sozialen Medien – auch in der Schweiz sorgen Schlagzeilen wie „Radikalisierung im Internet: Mit TikTok zum IS-Fanatiker" für Aufmerksamkeit. Gleichzeitig berichten immer mehr junge Nutzer:innen, dass sie in ihren Social-Media-Feeds auf unerwünschte sexuelle, irreführende und hasserfüllte Inhalte stossen.

Mit dem Inkrafttreten des Digital Services Act in der Europäischen Union werden strengere Regeln für soziale Medien eingeführt, insbesondere um Kinder besser zu schützen. Ein zentraler Aspekt solcher Massnahmen sind sogenannte "Trusted Flagger". Diese Akteure identifizieren problematische Inhalte, melden sie und entfernen sie von Social-Media Plattformen. Jedoch existiert in der Schweiz keine entsprechende Meldestelle. Dieses Problem versuchen wir, mit dem Flag&Safe Projekt zu lösen.

</details>

---

## 🔄 So funktioniert Flag&Safe

<img src="data/TrustedFlagger.png" alt="Systemdiagramm der Flag&Safe Plattform" class="system-img">

<details>
<summary><strong>Schritt A: Kinder und Jugendliche melden Inhalte</strong></summary>

Wenn Kinder oder Jugendliche in sozialen Medien auf problematische Inhalte stossen (z.B. extreme, radikale, hasserfüllte oder sexuelle Inhalte), können sie diese über die Flag&Safe Plattform melden. Hierfür schicken sie einen link zum Inhalt oder nutzen einen integrierten Chatbot.

</details>

<details>
<summary><strong>Schritt B: Inhalte werden gesammelt und geprüft</strong></summary>

Sobald ein potenziell problematischer Inhalt gemeldet wird, sammelt unser System diesen automatisch und speichert ihn sicher ab. Spezielle Computerprogramme schauen sich den Inhalt unter Zuhilfenahme von künstlicher Intelligenz an und prüfen, ob er gegen Regeln verstößt oder sogar illegal sein könnte. Dabei werden auch bekannte Listen mit verbotenen Inhalten abgeglichen.

</details>

<details>
<summary><strong>Schritt C: Automatische Meldung an Plattformen und Behörden</strong></summary>

Wenn ein Inhalt gegen die Regeln der sozialen Medien oder gegen Gesetze verstößt, meldet unser System ihn automatisch direkt an die Betreiber der Social-Media-Plattform (z.B. TikTok, Instagram). Wenn der Inhalt klar illegal ist, könnte der Inhalt sogar vollautomatisch an die zuständigen Polizeibehörden gemeldet werden.

</details>

<details>
<summary><strong>Schritt D: Schnelle Hilfe für Betroffene</strong></summary>

Gleichzeitig informiert das System auch lokale Hilfsstellen, wie Schulpsychologen oder Medienpädagogen. Diese Fachleute erhalten dann die wichtigsten Informationen über den gemeldeten Inhalt und können dem betroffenen Kind schnell helfen, zum Beispiel durch ein Beratungsgespräch.

</details>

<details>
<summary><strong>Schritt E: System lernt dazu und wird besser</strong></summary>

Alle gemeldeten Inhalte werden gesammelt und helfen dabei, unser System immer weiter zu verbessern. Die künstliche Intelligenz lernt aus neuen Fällen unter Wahrung der Anonymität der beteiligten Personen und kann so problematische Inhalte in Zukunft noch schneller und genauer erkennen. Wir können ausserdem so auch besser verstehen, welche potenziell gefährlichen Trends sich gerade online entwickeln.

</details>

<details>
<summary><strong>Schritt F: Infos für die Politik</strong></summary>

Unsere gesammelten Erkenntnisse geben wir auch an die Politik weiter. So können Politikerinnen und Politiker besser verstehen, welchen Gefahren Kinder und Jugendliche online ausgesetzt sind und neue Gesetze entwickeln, um sie besser zu schützen.

</details>

---

## 🎯 Was wir bieten

### Unsere Outputs
- ✅ **Trusted Flagger Plattform:** Eine Open-Source Softwarelösung, mit der Kinder und Jugendliche problematische Inhalte einfach melden können.
- ✅ **Workshops:** Workshops für Schulen und Beratungsstellen, um Bedürfnisse zu verstehen und den Umgang mit der Plattform zu schulen.
- ✅ **Usability-Studie:** Tests mit Kindern und Jugendlichen zur Evaluierung und Verbesserung der Plattform.
- ✅ **Wissenschaftliche Veröffentlichungen:** Publikationen zu technischen Entwicklungen und Ergebnissen.

### Zielgruppen
Unser Angebot richtet sich speziell an **Kinder und Jugendliche in der Schweiz**, die auf Social-Media-Plattformen aktiv sind.

---

## 👥 Das Projektteam

Ein interdisziplinäres Team aus Informatik, Rechtswissenschaft und Medienpädagogik:

<table>
  <tr>
    <td>
      <img src="data/HSG_Logo_EN_RGB.svg.png" alt="HSG Logo" class="team-logo"><br>
      <div class="institution-name">
        <strong>Universität St.Gallen</strong><br>
        Institut für Informatik
      </div>
      <img src="data/Luka.jpg" alt="Luka Bekavac" class="team-photo">
      <strong>Doktorand Luka Bekavac</strong><br><br>
      <img src="https://storage.inrupt.com/f531f8ef-cd9d-474a-9fa6-70026b37c847/public/publicPortrait-square.jpg" alt="Simon Mayer" class="team-photo">
      <strong>Prof. Simon Mayer</strong>
    </td>
    <td>
      <img src="data/Logo_Université_de_Lausanne.png" alt="Lausanne Logo" class="team-logo"><br>
      <div class="institution-name">
        <strong>Universität Lausanne</strong><br>
        Rechtswissenschaftliche Abteilung
      </div>
      <img src="data/Alice.jpeg" alt="Alice Palmieri" class="team-photo">
      <strong>Doktorand Alice Palmieri</strong><br><br>
      <img src="data/aurelia.jpg" alt="Aurelia Tamò-Larrieux" class="team-photo">
      <strong>Prof. Aurelia Tamò-Larrieux</strong>
    </td>
    <td>
      <img src="data/logo_stadt_st.gallen.jpg" alt="St.Gallen Logo" class="team-logo"><br>
      <div class="institution-name">
        <strong>Primarschule Halden</strong><br>
        St.Gallen
      </div>
      <img src="data/Benjamin-Lizinger.jpg" alt="Benjamin Lizinger" class="team-photo">
      <strong>Benjamin Lizinger</strong><br>
      Medienpädagoge
    </td>
    <td>
      <img src="data/Maastricht_University_logo.svg.png" alt="Maastricht Logo" class="team-logo"><br>
      <div class="institution-name">
        <strong>Universität Maastricht</strong><br>
        Law&Tech Lab
      </div>
      <img src="data/Konrad.jpeg" alt="Konrad Kollnig" class="team-photo">
      <strong>Prof. Konrad Kollnig</strong><br>
      (Unterstützende Funktion)
    </td>
  </tr>
</table>

---

## 📅 Zeitplan

**Projektstart:** 01.04.2025  
**Projektende:** 30.04.2026

### Nachhaltigkeit
Die Universität St.Gallen sichert den Betrieb der Plattform für 5 Jahre nach Projektende zu. Die Open-Source-Lösung ermöglicht zudem die Weiterentwicklung und den Betrieb der Plattform durch Dritte.

---

## 📄 Lizenz

Dieses Projekt wird als Open-Source-Lösung entwickelt und bereitgestellt.

---

<div class="center">

<strong>© 2025 Flag&Safe Projekt</strong>

<p style="font-style: italic;">Ein Projekt mit Unterstützung der</p>

<img src="data/Palatin.png" alt="Palatin Stiftung" style="max-width: 200px; height: auto;">

</div>
