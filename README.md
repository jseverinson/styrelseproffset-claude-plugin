# Styrelseproffset för Claude

[Styrelseproffset](https://www.styrelseproffset.se) är plattformen där svenska bostadsrättsföreningar sköter
sitt styrelsearbete. Med pluginet kan du be Claude om hjälp med föreningens arbete i stället för att leta
själv: vad styrelsen beslutade på förra mötet, vilka ärenden som är öppna, vad som händer i kalendern nästa
månad, vilka avtal som löper ut, eller allt som rör ett visst ämne. Claude kan också förbereda saker åt dig —
ett svar i ett e-postärende, ett nyhetsutkast till hemsidan, ett sms — som du sedan granskar och skickar i
Styrelseproffset.

## Vad pluginet innehåller

- **En anslutning till Styrelseproffsets MCP-server** på `https://www.styrelseproffset.se/mcp`. Det är den
  enda adress pluginet kontaktar. Pluginet kör ingen kod på din dator och läser inga filer eller
  inställningar där.
- **En skill** (`skills/styrelseproffset/SKILL.md`) som lär Claude hur verktygen hänger ihop: vilket verktyg
  som svarar på vilken fråga, hur ett möte eller ett ärende läses i sin helhet, och att det som når andra
  alltid förbereds som utkast och aldrig skickas.

## Så ansluter du

1. Installera pluginet och välj att ansluta Styrelseproffset.
2. Du skickas till Styrelseproffset och loggar in som vanligt, med BankID eller lösenord och tvåfaktor.
3. Välj förening, vad anslutningen får göra (**Enbart läsa** är förvalt) och vilka komponenter den når.

Anslutningen agerar i ditt namn och kan aldrig göra mer än du själv får. Hela guiden finns i hjälpcentret:
[Ansluta Claude eller ChatGPT](https://www.styrelseproffset.se/hjalp/ansluta-claude-eller-chatgpt).

## Vad Claude kan göra

**Läsa:** söka i föreningen, lista och öppna möten, ärenden, aktiviteter, projekt, medlemmar, lägenheter,
avtal och leverantörer, läsa ett mötes dagordning och protokoll, inläggen i ett ärende och kalendern för en
period. Av dokumenten ser Claude namn, beskrivning och storlek, men inte innehållet.

**Skapa och ändra**, om du gett anslutningen den rätten: projekt, aktiviteter, möten och mötespunkter,
kalenderhändelser, leverantörer, anteckningar och beslut.

**Förbereda**, som du granskar och skickar själv: svar i e-postärenden, nya e-postärenden, e-postutskick,
sms, nyheter och sidor till hemsidan.

En anslutning kan aldrig skicka utskick, sms eller notiser, signera, rösta eller publicera något på
hemsidan, oavsett vad du väljer.

## Dataskydd

Det Claude läser lämnar Styrelseproffset och behandlas enligt Anthropics villkor. Under **Anslutna
AI-tjänster** i dina inställningar i Styrelseproffset ser du varje anrop anslutningen gjort och kan koppla
bort den när som helst. Styrelsen kan stänga av AI-anslutningar för hela föreningen.

- Integritetspolicy: https://www.styrelseproffset.se/privacy
- Användarvillkor: https://www.styrelseproffset.se/villkor
- Support: https://www.styrelseproffset.se/kontakt

## Licens

MIT. Se [LICENSE](LICENSE).
