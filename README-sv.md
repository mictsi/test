# FAQ – Multifaktorautentisering (MFA) vid KTH

**Ingress (för CMS):**  
Multifaktorautentisering (MFA) är en central del av hur KTH skyddar identiteter, konton och digitala tjänster. Den här sidan förklarar varför MFA införs, varför Microsoft Authenticator används, hur det stödjer KTH:s Zero Trust‑strategi och vad det innebär för säkerhet, tillgänglighet och framtida autentiseringsmetoder.

---

## Vad är MFA och varför använder KTH det?

**MFA (multifaktorautentisering)** är en säkerhetsmetod som kräver mer än bara användarnamn och lösenord vid inloggning. Förutom något du vet (lösenordet) behöver du även bekräfta din identitet med något du har (till exempel en mobiltelefon).

KTH använder MFA för att:
- Skydda konton mot lösenordsstöld och nätfiske
- Minska risken för obehörig åtkomst
- Skydda känslig information, system och tjänster

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

Detta ligger i linje med aktuella bästa praxis och rekommendationer från större säkerhetsaktörer.

---

## Varför använder KTH Microsoft MFA som lösning?

KTH använder **Microsoft MFA (Microsoft Authenticator)** som standardlösning av flera strategiska och säkerhetsmässiga skäl:
- **Integrerat i KTH:s identitetsmiljö** – Tätt integrerat med KTH:s centrala identitets‑ och åtkomstplattform
- **Starkare skydd av identiteten** – Möjliggör villkorsstyrd åtkomst, riskbaserad autentisering och kontoskydd i stor skala
- **Phishing‑resistent autentisering** – Stöd för moderna phishing‑resistenta metoder (t.ex. nummermatchning och enhetsbunden godkänning)
- **Hårdvarubaserad säkerhet** – Utnyttjar säkra hårdvarufunktioner i moderna telefoner för att skydda kryptografiska nycklar
- **Framtidssäkert** – Möjliggör starkare metoder framöver utan plattformsbyte
- **Kostnadseffektivt** – Ingår i befintliga licenser och minskar behovet av separata token‑ och infrastrukturlösningar
- **Enkelt att förvalta** – Central administration, övervakning och återställning via befintliga verktyg

Detta ger bättre säkerhet samtidigt som lösningen är hanterbar, skalbar och användarvänlig.

---

## Varför använder vi specifikt en Microsoft‑lösning?

Microsoft MFA är en del av samma plattform som redan hanterar identiteter, åtkomst och säkerhet för stora delar av KTH:s IT‑miljö.

Genom att använda en sammanhållen plattform kan KTH:
- Skydda **själva identiteten**, inte bara enskilda inloggningar
- Tillämpa konsekventa säkerhetspolicyer för alla tjänster
- Korrelera signaler, risk och autentiseringshändelser
- Minska arkitekturkomplexitet och operativ risk

Denna integration är ett viktigt krav för att implementera Zero Trust i stor skala.

---

## Vad gäller för passkeys, FIDO2‑nycklar och lösenordslös inloggning?

KTH **utvärderar** passkeys, FIDO2‑nycklar och lösenordslösa autentiseringsmetoder för framtida användning.

Metoderna är intressanta eftersom de:
- Är **phishing‑resistenta** i grunden
- Minskar eller eliminerar beroendet av lösenord
- Binder autentiseringen kryptografiskt till användare, enhet och tjänst
- Kan ge en enklare och säkrare användarupplevelse

Microsoft MFA och KTH:s identitetsplattform möjliggör införande av dessa metoder när de är mogna, väl testade och lämpliga för KTH:s miljö.

I nuläget är dessa metoder **inte generellt tillgängliga vid KTH**, men ingår i KTH:s långsiktiga autentiseringsstrategi.

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

## Varför tillåts inte tredjepartsappar för MFA?

KTH **tillåter inte** tredjepartsappar för MFA för KTH‑konton.

Beslutet baseras på säkerhet, hanterbarhet och efterlevnad:
- **Bristande phishing‑skydd** – Många tredjepartsappar bygger på TOTP eller enkla push‑lösningar som inte uppfyller KTH:s krav.
- **Ingen djup integration** – Tredjepartslösningar kan inte integreras fullt ut med KTH:s identitetsplattform, riskbedömning och villkorsstyrning.
- **Otydliga säkerhetsgarantier** – KTH kan inte verifiera hur hemligheter lagras, nycklar skyddas eller hårdvaruskydd nyttjas.
- **Svårare incidenthantering** – Återställning, enhetsförlust och övervakning blir betydligt svårare.
- **Ökad driftkomplexitet** – Flera MFA‑lösningar ökar administration, supportbehov och användarförvirring.
- **Efterlevnads‑ och dataskyddsrisker** – KTH måste säkerställa att autentisering uppfyller krav från regelverk och avtal.

Genom att standardisera på Microsoft MFA kan KTH tillämpa konsekventa säkerhetskontroller och erbjuda en förutsägbar och supportbar lösning.

---

## Varför använder KTH inte MFA‑lösningar med öppen källkod?

MFA‑lösningar med öppen källkod används inte för KTH‑konton eftersom de inte uppfyller den kombination av krav på **säkerhet, skalbarhet, integration och driftstöd** som behövs i KTH:s miljö.

Skäl inkluderar:
- **Brist på djup identitetsintegration** – Ofta saknas tät koppling till identitetsplattform, villkorsstyrd åtkomst och riskbaserade kontroller.
- **Driftansvar** – KTH behöver själv stå för drift, härdning, patchning, övervakning och incidenthantering.
- **Begränsat stöd för phishing‑resistens** – Många lösningar fokuserar på TOTP snarare än moderna phishing‑resistenta metoder.
- **Skalbarhet och tillgänglighet** – Att nå KTH:s krav på tillgänglighet och prestanda kräver betydande infrastruktur.
- **Kostnad och risk över tid** – ”Gratis” mjukvara kan ge högre långsiktig driftkostnad och större säkerhetsrisk.

För identitet och autentisering prioriterar KTH plattformar med tydliga säkerhetsgarantier, ansvar och långsiktigt stöd.

---

## Hur ser KTH på öppen källkod jämfört med kommersiella lösningar?

KTH har en stark och etablerad inriktning att **prioritera öppen källkod** där det är lämpligt och uppfyller KTH:s krav. Öppen källkod kan ge transparens, flexibilitet, minskat leverantörsberoende och samverkan.

Samtidigt är valet mellan öppen källkod och kommersiella lösningar alltid **kontextberoende** och baseras på vilken typ av tjänst som ska levereras.

För varje tjänst utvärderar KTH bland annat:
- **Säkerhetskrav** – inkl. skydd mot moderna angrepp och förmåga att skydda identiteter och känslig data
- **Integrationsbehov** – hur väl lösningen passar med KTH:s plattformar och tjänster
- **Driftsmognad** – övervakning, incidenthantering, återställning och livscykelhantering
- **Skalbarhet och tillgänglighet** – stöd för hela organisationen med hög tillgänglighet
- **Total ägandekostnad** – långsiktig driftkostnad, inte bara licens
- **Risk och ansvar** – tydligt ansvar för sårbarheter, uppdateringar och support

För **identitet och autentisering** är kraven särskilt höga. Dessa tjänster är en kritisk grund för alla andra system. I detta område har KTH bedömt att en **kommersiell, tätt integrerad plattform** i dagsläget ger lägre risk och starkare säkerhetsgarantier än tillgängliga open source‑alternativ.

Det innebär inte att open source är uteslutet, utan att KTH väljer det som bäst matchar tjänstens kritikalitet och riskprofil, samtidigt som open source‑alternativ fortsätter att utvärderas över tid.

---

## Vad gäller för användare med funktionsnedsättning eller tillgänglighetsbehov?

KTH är medvetet om att **alla användare inte kan använda MFA på samma sätt**, och tillgänglighet är viktigt.

Microsoft Authenticator stödjer flera tillgänglighetsfunktioner via operativsystemet, till exempel:
- Skärmläsare
- Röststyrning
- Högkontrast och tillgänglighetsinställningar

Samtidigt kan MFA fortfarande vara svårt för vissa användare på grund av fysiska, kognitiva eller andra funktionsnedsättningar.

Om du har tillgänglighetsbehov som gör det svårt eller omöjligt att använda Microsoft Authenticator:
- **Kontakta KTH IT‑support** för att diskutera din situation
- En individuell bedömning kan göras för att hitta **rimliga och säkra alternativ eller anpassningar**

Eventuella alternativ måste fortfarande uppfylla KTH:s säkerhetskrav och vara förenliga med phishing‑resistens och Zero Trust‑principer.
