# speedview-privacy
# Integritetspolicy / Privacy Policy – SpeedView

**Senast uppdaterad / Last updated:** 2026-11-24  
**Utvecklare / Developer:** Croftersoft

---

## Svenska

### 1. Allmänt
SpeedView ("appen") är en färddator- och körjournalsapplikation utvecklad av Croftersoft. Din integritet är viktig för oss. Appen samlar inte in, lagrar inte och delar inte någon personlig information på externa servrar.

### 2. Platsdata (GPS)
Appen begär åtkomst till enhetens exakta platsdata (`ACCESS_FINE_LOCATION` och `ACCESS_COARSE_LOCATION`) uteslutande i realtid när appen är aktiv på skärmen för att:
* Beräkna aktuell hastighet, maxhastighet, snitthastighet, körd sträcka, kompassriktning och höjd över havet.
* Hämta start- och slutgatuadress vid sparande av en resa i den valfria körjournalen.
* Hämta gällande hastighetsgräns för aktuell väg via OpenStreetMap (Overpass API) när automatisk fartgräns är aktiverad.

Platsdata bearbetas endast lokalt på din enhet (samt via Androids inbyggda Geocoder-tjänst för adressuppslagning) och skickas aldrig till Croftersoft eller någon tredje part för spårning eller marknadsföring.

### 3. Lokal lagring & Användardata
Alla inställningar, färgval, fordonsuppgifter (såsom förarnamn och registreringsnummer), körhistorik och tankningsloggar sparas uteslutande lokalt i enhetens interna minne (`SharedPreferences`). Du kan när som helst radera enskilda poster i appen eller rensa all data via telefonens systeminställningar.

### 4. Delning & Export
När du aktivt väljer att dela (`.csv`) eller skriva ut (`.pdf`) din körjournal skapas filen lokalt på din enhet och skickas endast vidare till den app eller skrivare du själv väljer i Androids delningsmeny.

### 5. Kontakt
Vid frågor om denna integritetspolicy, kontakta Croftersoft via vår kontaktsida eller e-post i Google Play Butik.

---

## English

### 1. Overview
SpeedView ("the App") is a speedometer and trip log application developed by Croftersoft. We respect your privacy. The App does not collect, store, or transmit any personal data to external servers.

### 2. Location Data (GPS)
The App accesses precise device location (`ACCESS_FINE_LOCATION` and `ACCESS_COARSE_LOCATION`) strictly while the App is in use in the foreground to:
* Calculate current speed, maximum speed, average speed, trip distance, compass bearing, and altitude.
* Retrieve start and end street addresses when saving a trip in the optional trip log.
* Retrieve applicable speed limits for the current road via OpenStreetMap (Overpass API) when automatic speed limit detection is enabled.

Location data is processed locally on your device (and via Android's built-in Geocoder service for street address lookup) and is never sent to Croftersoft or third parties for tracking or advertising.

### 3. Local Storage
All preferences, color themes, vehicle details, trip history, and fuel logs are stored exclusively on your local device (`SharedPreferences`). You may delete individual entries inside the App or clear all app data via your device settings at any time.

### 4. Data Export
When you manually choose to share (`.csv`) or print (`.pdf`) your trip log, the file is generated locally and passed solely to the target application or printer selected by you.
