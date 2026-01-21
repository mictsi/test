# FAQ – Multifaktorautentisering (MFA) vid KTH

**Ingress (för CMS):**  
Multifaktorautentisering (MFA) är en central del av hur KTH skyddar identiteter, konton och digitala tjänster. Den här sidan förklarar varför MFA införs, varför Microsoft Authenticator används, hur det stödjer KTH:s Zero Trust-strategi och vad det innebär för säkerhet, tillgänglighet och framtida autentiseringsmetoder.

---

## Vad är MFA och varför använder KTH det?

**MFA (multifaktorautentisering)** är en säkerhetsmetod som kräver mer än bara användarnamn och lösenord vid inloggning. Förutom något du vet (lösenordet) behöver du även bekräfta din identitet med något du har (till exempel en mobiltelefon).

KTH använder MFA för att:
- Skydda konton mot lösenordsstöld och nätfiske
- Minska risken för obehörig åtkomst
- Skydda känslig information, system och tjänster

---

## Hur hänger MFA ihop med KTH:s Zero Trust‑strategi?

MFA och phishing‑resistent autentisering är **grundpelare** i den **Zero Trust (ZT)**‑strategi som KTH implementerar.

### Vad är Zero Trust?

Zero Trust är en säkerhetsmodell som bygger på principen **”lita aldrig, verifiera alltid”**. Det innebär att:
- Ingen användare, enhet eller nätverk litas på som standard
- Varje åtkomstförsök måste verifieras explicit
- Identiteten är den primära säkerhetsgränsen

I stället för att förlita sig på nätverksplats (t.ex. ”på campus”) baseras åtkomstbeslut på:
- Stark autentisering
- Enhets‑ och användarkontext
- Löpande riskbedömning

### Varför är MFA kritiskt i Zero Trust?

I en Zero Trust‑modell:
- Krävs **stark verifiering av identitet** innan åtkomst ges
- Minskar **phishing‑resistent MFA** risken för identitetskompromettering kraftigt
- Räcker inte ett stulet lösenord för angripare

Genom Microsoft MFA och fokus på phishing‑resistenta metoder skapar KTH en stark identitetsgrund som möjliggör säker åtkomst oavsett plats, nätverk eller enhet.

---

## När blir MFA obligatoriskt?

MFA blir **obligatoriskt för alla anställda och anknutna från och med 24 februari 2026** vid åtkomst till KTH:s centrala inloggningstjänst och anslutna system.

---

## Vilka tjänster kräver MFA?

MFA krävs vid inloggning via KTH:s **centrala inloggningstjänst**, som används för många KTH‑system, bland annat (men inte enbart):
- kth.se
- Canvas
- Zoom
- Microsoft 365‑tjänster
- Andra tjänster kopplade till KTH:s centrala autentisering

---

## Hur aktiverar jag MFA?

1. Installera **Microsoft Authenticator** på din mobiltelefon.
2. Öppna en webbläsare (helst privat/inkognito) och gå till **https://aka.ms/mfasetup**.
3. Logga in med ditt KTH‑konto (username@ug.kth.se).
4. Välj att lägga till **Microsoft Authenticator** som autentiseringsmetod.
5. Skanna QR‑koden med appen.
6. Godkänn testinloggningen för att slutföra registreringen.

---

## Varför är det viktigt att installera Microsoft Authenticator från App Store eller Google Play?

Att installera **Microsoft Authenticator** endast från **officiella App Store (iOS)** eller **Google Play Store (Android)** är viktigt för säkerhet och tillförlitlighet:
- **Skydd mot skadliga appar** – Appar från inofficiella källor kan vara manipulerade för att stjäla lösenord, MFA‑godkännanden eller personuppgifter.
- **Verifierad utgivare** – Officiella appbutiker verifierar att appen verkligen publiceras av Microsoft och inte har manipulerats.
- **Automatiska säkerhetsuppdateringar** – Uppdateringar innehåller säkerhetsfixar och kompatibilitetsuppdateringar som kan krävas för KTH‑system.
- **Stöds av KTH** – KTH:s MFA‑lösning är testad och stöds endast med officiella Microsoft Authenticator.
- **Minskad risk för kontokapning** – Inofficiella appar ökar risken för nätfiske och skadeprogram.

Kontrollera att appen är publicerad av **Microsoft Corporation**.

---

## Vilka mobiltelefoner stöds?

Du kan använda både **privat telefon** och **tjänstetelefon**.

Stödda operativsystem:
- **iPhone:** iOS 16 eller senare
- **Android:** Android 8 eller senare

Du kan kontrollera din OS‑version i telefonens inställningar.

---

## Kan jag registrera fler än en telefon för MFA?

Ja. Du kan registrera **flera telefoner** för MFA.

För att lägga till en ny telefon behöver du normalt godkänna tillägget med en redan registrerad MFA‑enhet.

---

## Jag har en ny telefon. Vad ska jag göra?

- **Om du har kvar din gamla telefon:** Lägg till MFA på den nya telefonen innan du tar bort den gamla.
- **Om du inte längre har den gamla telefonen:** Ta bort den gamla enheten med **Mobilt BankID** via ”Hantera ditt KTH‑konto”.
- **Om du inte har Mobilt BankID:** Kontakta **IT‑support** för hjälp.

---

## Hur ofta behöver jag använda MFA?

MFA krävs **per webbläsare och per enhet**.

Du kan behöva autentisera dig igen om:
- Du byter webbläsare eller enhet
- Du rensar webbläsardata
- Du har varit inaktiv under en längre tid

---

## Kan jag hantera mina MFA‑inställningar själv?

Ja, om du har **Mobilt BankID**.

Via tjänsten **Hantera ditt KTH‑konto** kan du:
- Lägga till en telefon för MFA
- Ta bort en telefon från MFA
- Se registrerade MFA‑enheter

Om du inte har Mobilt BankID kontaktar du **IT‑support**.

---

## Hur tar jag bort en telefon från MFA?

1. Logga in i **Hantera ditt KTH‑konto** med Mobilt BankID.
2. Gå till **Mina MFA‑enheter**.
3. Välj den enhet du vill ta bort.
4. Bekräfta borttagningen med Mobilt BankID.

---

## Vad gör jag om jag inte kan logga in på grund av MFA?

- Har du **Mobilt BankID**, använd det för att hantera eller återställa dina MFA‑enheter.
- Har du **inte Mobilt BankID**, kontakta **KTH IT‑support** för hjälp.

---

## Stödjer KTH mjukvaru‑ eller hårdvarubaserade TOTP‑lösningar (engångskoder)?

Nej. KTH stödjer **inte** mjukvaru‑ eller hårdvarubaserade TOTP‑lösningar (till exempel sexsiffriga roterande koder).

KTH prioriterar **phishing‑resistenta autentiseringsmetoder**, och traditionell TOTP ger inte tillräckligt skydd mot moderna nätfiskeattacker.

---

## Varför prioriterar KTH phishing‑resistenta autentiseringsmetoder?

Phishing‑resistenta metoder är utformade så att autentisering inte kan återanvändas av en angripare, även om användaren luras att godkänna en inloggning.

KTH prioriterar dessa metoder eftersom de:
- Förhindrar att angripare kan fånga och återanvända inloggningsuppgifter eller MFA‑koder
- Skyddar mot realtids‑phishing och ”MFA‑trötthet”‑attacker
- Binder autentiseringen till rätt tjänst och identitet
- Minskar risken för kontokapning avsevärt

---

## Varför använder KTH Microsoft MFA som lösning?

KTH använder **Microsoft MFA (Microsoft Authenticator)** som standardlösning av flera strategiska och säkerhetsmässiga skäl:
- **Integrerat i KTH:s identitetsmiljö** – Tätt integrerat med KTH:s centrala identitets‑ och åtkomstplattform
- **Starkare skydd av identiteten** – Möjliggör villkorsstyrd åtkomst, riskbaserad autentisering och kontoskydd i stor skala
- **Phishing‑resistent autentisering** – Stöd för moderna phishing‑resistenta metoder
- **Hårdvarubaserad säkerhet** – Utnyttjar säkra hårdvarufunktioner i moderna telefoner för att skydda kryptografiska nycklar
- **Framtidssäkert** – Möjliggör starkare metoder framöver utan plattformsbyte
- **Kostnadseffektivt** – Ingår i befintliga licenser och minskar behovet av separata token‑ och infrastrukturlösningar
- **Enkelt att förvalta** – Central administration, övervakning och återställning via befintliga verktyg

---

## Varför använder vi specifikt en Microsoft‑lösning?

Microsoft MFA är en del av samma plattform som redan hanterar identiteter, åtkomst och säkerhet för stora delar av KTH:s IT‑miljö.

Genom att använda en sammanhållen plattform kan KTH:
- Skydda **själva identiteten**, inte bara enskilda inloggningar
- Tillämpa konsekventa säkerhetspolicyer för alla tjänster
- Korrelera signaler, risk och autentiseringshändelser
- Minska arkitekturkomplexitet och operativ risk

---

## Vad gäller för passkeys, FIDO2‑nycklar och lösenordslös inloggning?

KTH **utvärderar** passkeys, FIDO2‑nycklar och lösenordslösa autentiseringsmetoder för framtida användning.

---

## Kan jag använda min egen YubiKey när FIDO2‑nycklar blir tillgängliga?

Nej. En FIDO2‑enhet behöver **provisioneras av KTH**.

---

## Varför tillåts inte tredjepartsappar för MFA?

KTH **tillåter inte** tredjepartsappar för MFA för KTH‑konton.

Skälen är bland annat:
- Bristande phishing‑skydd
- Ingen djup integration med identitetsplattformen
- Svårare incidenthantering och återställning
- Ökad driftkomplexitet och efterlevnadsrisk

---

## Varför använder KTH inte MFA‑lösningar med öppen källkod?

MFA‑lösningar med öppen källkod används inte för KTH‑konton eftersom de inte uppfyller den kombination av krav på **säkerhet, skalbarhet, integration och driftstöd** som behövs i KTH:s miljö.

---

## Hur ser KTH på öppen källkod jämfört med kommersiella lösningar?

KTH prioriterar öppen källkod där det är lämpligt. Samtidigt är valet kontextberoende. För identitet och autentisering – tjänster med mycket höga krav på säkerhet och tillgänglighet – ger i dagsläget en kommersiell, tätt integrerad plattform lägre risk och starkare säkerhetsgarantier.

---

## Vad gäller för användare med funktionsnedsättning eller tillgänglighetsbehov?

Om du har tillgänglighetsbehov som gör det svårt eller omöjligt att använda Microsoft Authenticator:
- Kontakta **KTH IT‑support** för individuell bedömning och säkra alternativ

Eventuella alternativ måste fortfarande uppfylla KTH:s säkerhetskrav och vara förenliga med phishing‑resistens och Zero Trust‑principer.
