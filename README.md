# analyse_oai-pmh
Analysis of OAI_PMH  endpoints


Kjente endepunkter


## NB OAI-PMH sluttpunkt
Liste av datasett: https://bibsys.alma.exlibrisgroup.com/view/oai/47BIBSYS_NB/request?verb=ListSets

## SIKT OAI-PMH sluttpunkt
Liste av datasett: https://bibsys.alma.exlibrisgroup.com/view/oai/47BIBSYS_NETWORK/request?verb=ListSets

## NB OAI-PMH repository
Startside: https://www.nb.no/oai/

### Beskrivelse
Nasjonalbiblioteket tilbyr utlevering av allment tilgjengelige metadata fra søketjenesten http://www.nb.no/nbsok/ basert på OAI-PMH v2.0 (Open Archives Initiative Protocol for Metadata Harvesting, version 2).

Velg [Identify](https://www.nb.no/oai/repository?verb=Identify) for å se en kort beskrivelse av Nasjonalbiblioteket OAI-R.

#### Metadata
Nasjonalbiblioteket OAI-R støtter utlevering av 2 metadataformater: oai_dc og mods, se: [ListMetadataFormats](https://www.nb.no/oai/repository?verb=ListMetadataFormats)

#### Bruk av tjenesten
Ved høsting av store intervall (f.eks. årsspenn) så kan det ta opptil flere minutter før første respons kommer (skyldes intern generering av idliste ved første forespørsel). Noen ganger må man ned på spenn-intervallet, typisk ukesintervall hvis man treffer et intervall der mange poster er oppdatert. Det kan være praktisk med korte høste-intervall hvis noe feiler for da slipper man å høste så langt tilbake i tid.