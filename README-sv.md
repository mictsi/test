# FAQ – Multifaktorautentisering (MFA) vid KTH

**Ingress:**  
Multifaktorautentisering (MFA) är en central del av hur KTH skyddar identiteter, konton och digitala tjänster. Dokumentet beskriver varför MFA används, varför Microsoft Authenticator är vald lösning, hur detta stödjer KTH:s Zero Trust‑strategi samt vad det innebär för säkerhet, tillgänglighet och framtida autentisering.

---

## Vad är MFA och varför använder KTH det?

**MFA (multifaktorautentisering)** kräver mer än användarnamn och lösenord. Du verifierar även din identitet med något du har, till exempel en mobiltelefon.

KTH använder MFA för att:
- Skydda konton mot nätfiske och lösenordsstöld
- Minska risken för obehörig åtkomst
- Skydda känsliga system och tjänster

---

## Hur hänger MFA ihop med KTH:s Zero Trust‑strategi?

MFA och phishing‑resistent autentisering är **grundpelare** i KTH:s **Zero Trust‑strategi**.

### Vad är Zero Trust?

Zero Trust bygger på principen **”lita aldrig, verifiera alltid”**:
- Ingen användare eller enhet litas på som standard
- Varje åtkomst verifieras explicit
- Identiteten är den primära säkerhetsgränsen

### Varför är MFA kritiskt i Zero Trust?

- Stark verifiering av identitet krävs
- Phishing‑resistent MFA minskar risken för kontokapning
- Ett stulet lösenord räcker inte för angripare

---

## När blir MFA obligatoriskt?

MFA blir **obligatoriskt för alla anställda och anknutna från och med 24 februari 2026**.

---

## Vilka tjänster kräver MFA?

- kth.se
- Canvas
- Zoom
- Microsoft 365
- Andra centralt autentiserade tjänster

---

## Hur aktiverar jag MFA?

1. Installera **Microsoft Authenticator**
2. Gå till https://aka.ms/mfasetup
3. Logga in med username@ug.kth.se
4. Lägg till Authenticator
5. Skanna QR‑koden
6. Godkänn testinloggningen

---

## Varför måste Microsoft Authenticator installeras från officiella appbutiker?

För att säkerställa:
- Skydd mot skadliga appar
- Verifierad utgivare
- Säkerhetsuppdateringar
- Fullt stöd från KTH

---

## TOTP och tredjepartsappar

KTH stödjer **inte** TOTP eller tredjepartsappar för MFA.

---

## Varför phishing‑resistent autentisering?

Metoderna skyddar mot återanvändning av stulna uppgifter och realtids‑phishing.

---

## Varför använder KTH Microsoft MFA?

Lösningen är:
- Integrerad i KTH:s identitetsplattform
- Phishing‑resistent och hårdvaruskyddad
- Kostnadseffektiv
- Framtidssäker

---

## Passkeys, FIDO2 och lösenordslös inloggning

KTH utvärderar dessa metoder för framtida bruk.

---

## Kan jag använda min egen YubiKey eller FIDO2‑nyckel när detta införs?

Nej. FIDO2‑enheter måste **tillhandahållas och hanteras av KTH**.  
Privata säkerhetsnycklar stöds inte av säkerhets‑ och förvaltningsskäl.

---

## Tillgänglighet

Användare med tillgänglighetsbehov ska kontakta **KTH IT‑support** för individuell bedömning.
