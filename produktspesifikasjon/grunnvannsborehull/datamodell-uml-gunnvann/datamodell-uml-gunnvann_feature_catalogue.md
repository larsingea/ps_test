#### LGNBrønn

brønn som benyttes eller har vært benyttet under monitorering av upåvirkede grunnvannsakviferer ("Landsomfattende grunnvannsnett - LGN" -<a href="http://www.grunnvann.no/overvaking_eks.php">http://www.grunnvann.no/overvaking_eks.php</a>)

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>målePunktNr</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Merking av observasjonspunkter (brønner og oppkommer) som forekommer i et LGNområde (LGN overvåkingsstasjon).<br /><br />En slags merkelapp/nummerering, men som også kan inneholde bokstaver. Tallverdier over 50 representerer oppkommer.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>måleFrekvens</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvor hyppig det blir utført målinger/ kjemiske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kjemiskeAnalyser</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>link til kjemiske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Link</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>driftStartMåling</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>startmåned/år for innsamling av kjemiske data</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>driftStoppMåling</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sluttmåned/år for innsamling av kjemiske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>lgnNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir NGUs stasjonsnummer i overvåkningsprogrammet "Landsomfattende grunnvannsnett" (LGN)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
GrunnvannBorehull

**Assosiasjoner**
LGNOmrådeRefPkt – rolle: referansepunkt – kardinalitet: 1

#### GrunnvannBorehull (abstrakt)

ett enkelt fysisk punkt der det er foretatt en boring i forbindelse med bruk eller undersøkelse av grunnvannet eller dets egenskaper, herunder alle energiboringer (til uttak av grunnvarme), boringer etter grunnvann, overvåkningsbrønner og sonderboringer som er motivert i undersøkelse av grunnvann eller potensiale for grunnvannsuttak. Geotekniske boringer inngår ikke.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektet har punktgeometri</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnNr</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>brønnummer i NGUs database</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolMedium</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>definerer om et borehull er boret slik at den blir permanent åpen; et stykke ned i fjellgrunnen (fjell) eller kun i løsmasser (løsmasse).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GeolMediumType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Løsmasse<br />- Fjell</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>stedfestelseMetodeInfo</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>stedfestelsesmetode, for eksempel GPS, kart med flere. Fram til ca 2000 finnes en del registreringer som avviker betydelig fra brønnhullets reelle koordinater.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppdragstaker</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på borefirma som har utført boringen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnBrukOmfang</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvor omfattende vannforsyningen er (til enkelthusholdning, gårdsbruk osv.)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BrønnBrukOmfangType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Enkelthusholdning<br />- Gårdsbruk<br />- Turistnæring<br />- Hytte/fritidsbolig<br />- Næringsmiddelproduksjon<br />- Annen industri<br />- Vannverk<br />- Vanningsanlegg<br />- Vannforsyning<br />- Miljøundersøkelser/overvåkning<br />- Større anlegg<br />- Undersøkelse for energibrønn/anlegg<br />- Undersøkelse for vannforsyning<br />- Forskning<br />- Ukjent</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boreDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for boringen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>konsulentFirma</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>konsulentfirma, som for eksempel har valgt ut borelokalitet, eller som har utredet aspekter ved bruk av brønnen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>rapport</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referanse til NGU-rapporter, samt VRL46-rapporter (innrapportert til NGU ifm oppgaveplikt jf Vannressurslovens §46 4. ledd).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>total lengde av borehullets forløp, tilsvarer dyp ved vertikal boring</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengdeTilBerg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dybde til berg som ikke er målt men basert på tolkning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>vannstandBorehull</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>stabil vannstand etter boring målt fra overflaten i meter.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>datoVannstandBorehull</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for når vannstand etter boring er målt  (før eventuell kapasitetsøkning).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnHelningType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type helning borehullet kan ha (grovinndeling)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BrønnHelningType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Loddrett<br />- Skrå<br />- Horisontal</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>diameterBorehull</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>borehullets diameter målt i millimeter. For fjellbrønner oppgis dominerende diameter på borhullet nedenfor foringsrørets avslutning.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretHelningsgrad</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>borehullets hellning målt som avvik i grader fra loddlinje</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretAzimuth</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>helning hvor  90 grader er vertikalt , 0 grader er horisontalt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialForingsrør</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>foringsrørets materialtype</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>ForingsrørMaterialType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Plast<br />- Rustfritt stål<br />- Stål<br />- PVC<br />- Damprør<br />- PE</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>lengdeForingsrør</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>foringsrørets lengde i meter</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretKapasitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>brønnens kapasitet ("vannføring") i liter/time før eventuell kapsitetsøkende trykking eller sprengning. Vanligvis målt nokså usikkert av boreren i forbindelse med selve boringen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kapasMålemet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver målemetode brukt for å måle brønnens kapasitet (vanngiverevne). Hvis brønnen senere er trykket eller sprengt for å øke kapasiteten,  oppgis her den målemetoden som er brukt FØR denne kapasitetsøkningen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>KapasitetMålemetode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Blåsing<br />- Prøvepumping<br />- Stigningstest</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kapasØkningType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver om brønnen er sprengt eller trykket for å øke kapasiteten</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>KapasitetØkningType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Trykking<br />- Sprengning<br />- Ukjent</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>øktKapasitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>brønnens kapasitet ("vannføring") i liter/time målt etter eventuell kapsitetsøkende trykking eller sprengning.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>beskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forklaring til objektet og undersøkelser utført på lokaliteten.<br />Brønnborers generelle kommentarer til boringen, gitt på brønnskjema</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnFiler</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>filer i alle formater (billedformater, pdf, excel, word m.fl.) som brønnborere og andre rapportører har lagt inn og knyttet til borehullet (brønnen).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FellesegenskaperGrunnvannBorehull

#### EnergiBrønn

Grunnvannborehull som helt eller delvis er dedikert for uttak eller deponering av grunnvarme, enten gjennom kollektorslanger eller pumping av grunnvann hvis temperatur benyttes til oppvarming eller avkjøling.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnParkNr</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>brønnparknummer  i NGUs databaser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
GrunnvannBorehull

**Assosiasjoner**
BrønnPark – rolle: brønnpark – kardinalitet: 0..1

#### GrunnvannOppkomme

forekomst av oppkomme/kilde/ naturlig utstrømmende grunnvann

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektet har punktgeometri</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppkomNr</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>oppkommets nummer i Nasjonal Grunnvannsdatabase</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolMedium</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>definerer om et borehull er boret slik at den blir permanent åpen; et stykke ned i fjellgrunnen (fjell) eller kun i løsmasser (løsmasse).<br /><br />I dette tilfellet definerer den om et oppkommet forekommer i løsmasse eller i fjell</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GeolMediumType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Løsmasse<br />- Fjell</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppkomVannføring</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>oppkommets vanngiverevne målt i liter/time målt ved registrering. (vil variere)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppkomBruk</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>overordnet bruksområde for naturlig oppkomme (kilde)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>OppkomBruk</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Vannforsyning<br />- Undersøkelse<br />- Ukjent</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppkomBrukOmfang</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>underordnet bruksområde (til enkelthusholdning, gårdsbruk osv.)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BrønnBrukOmfangType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Enkelthusholdning<br />- Gårdsbruk<br />- Turistnæring<br />- Hytte/fritidsbolig<br />- Næringsmiddelproduksjon<br />- Annen industri<br />- Vannverk<br />- Vanningsanlegg<br />- Vannforsyning<br />- Miljøundersøkelser/overvåkning<br />- Større anlegg<br />- Undersøkelse for energibrønn/anlegg<br />- Undersøkelse for vannforsyning<br />- Forskning<br />- Ukjent</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppkomUtforming</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver om oppkomme er naturlig uten inngrep, eller lagt i rør/kum</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>OppkomUtforming</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Rør<br />- Naturlig<br />- Kum</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppkomBeskyttelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver hvordan oppkommet evnt er besyttet (drenering, gjerde, overbygg)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>OppkomBeskyttelse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Drensledning/-grøft<br />- Gjerde<br />- Overbygg</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppkomFareForurensing</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>inndeler forurensningsfaren for oppkommet til liten/middels/stor</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>OppkomFareForurensing</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Liten<br />- Middels<br />- Stor</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppkomTypeForurensing</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>definerer om eventuell forurensningsfare stammer fra bebyggelse, industri, jordbruk etc</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>OppkomTypeForurensing</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Bebyggelse<br />- Beitemark<br />- Industri<br />- Jordbruk<br />- Annen</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppkomFiler</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>link til eventuelle filer som er knyttet til oppkommet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Link</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>konsulentFirma</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på konsulentfirma som evnt har utredet kilden/oppkommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>rapport</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referanse til NGU-rapporter, samt VRL46-rapporter (innrapportert til NGU ifm oppgaveplikt jf Vannressurslovens §46 4. ledd).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppkomRegDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato når oppkomme ble registrert</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppkomKommentar</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver formål, historikk, referanser og kontakt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>stedfestelseMetodeInfo</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metoden brukt for å stedfeste lokaliteten</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FellesegenskaperGrunnvannBorehull

#### Sonderboring

undersøkelsesboring benyttet til å karakterisere løsmassenes egenskaper, vanligvis for å estimere om massene er grove og velsorterte nok til å kunne levere grunnvann til vannforsyning. Før ca år 2000   var håndholdt borutstyr vanligst, etter hvert mer vanlig med utstyr tilsvarende det som benyttes under geotekniske boringer.

Egenskaper

(ingen)

Relasjoner

**Arv**
GrunnvannBorehull

#### FellesegenskaperGrunnvannBorehull (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er fagområde-uavhengige og kan benyttes for alle objekttyper<br /><br />Merknad:<br />Spesielt i produktspesifikasjonsarbeid vil en velge egenskaper og av grensningslinjer fra denne klassen.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>datauttaksdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for uttak fra en database<br /><br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

#### LGNGrunnvannOppkomme

forekomst av oppkomme/ naturlig utstrømmende grunnvann som benyttes eller har vært benyttet under monitorering av upåvirkede grunnvannsakviferer ("Landsomfattende grunnvannsnett - LGN" -<a href="http://www.grunnvann.no/overvaking_eks.php">http://www.grunnvann.no/overvaking_eks.php</a>)

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>målePunktNr</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Merking av observasjonspunkter (brønner og oppkommer) som forekommer i et LGNområde (LGN overvåkingsstasjon).<br /><br />En slags merkelapp/nummerering, men som også kan inneholde bokstaver. Tallverdier over 50 representerer oppkommer.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>måleFrekvens</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvor hyppig det utføres målinger/kjemiske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kjemiskeAnalyser</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>link til kjemiske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Link</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>driftStartMåling</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>startmåned/år for innsamling av kjemiske data</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>driftStoppMåling</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sluttmåned/år for innsamling av kjemiske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>lgnNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir NGUs stasjonsnummer i overvåkningsprogrammet "Landsomfattende grunnvannsnett" (LGN)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
GrunnvannOppkomme

**Assosiasjoner**
LGNOmrådeRefPkt – rolle: referansepunkt – kardinalitet: 1

#### BrønnPark

anlegg for uttak og/eller deponering av grunnvarme. Anlegg må ha tilsluttet minst fem energibrønner for å falle inn under NGUs definisjon av "Brønnpark".

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektet har punktgeometri</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnParkNr</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>brønnparknummer  i NGUs database</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnpOmrNavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokalt stedsnavn der brønnparken ligger.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolMedium</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>definerer om et borehull er boret slik at den blir permanent åpen; et stykke ned i fjellgrunnen (fjell) eller kun i løsmasser (løsmasse).<br /><br />I dette tilfellet definerer den om brønnpark er basert på boringer kun i løsmasse (vanligvis for oppumping av varmt grunnvann) eller også er  boret videre ned i berggrunn (vanligvis varmeuttak via kollektorslanger).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GeolMediumType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Løsmasse<br />- Fjell</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>antallEnergiBrønner</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver antall energibrønner i brønnparken (minimum 5 for å defineres som brønnpark)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnpKommentar</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>brønnboreres kommentarer om brønnparken</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnpVEffekt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>brønnparkens maksimale varmeeffekt i kW</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnpVEnergi</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>brønnparkens maksimale varmeenergi i kWh/år</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnpKEffekt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>brønnparkens maksimale kjøleeffekt i kW</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnpKEnergi</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>brønnparkens maksimale kjøleeffekt i kWh/år</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnpFrikjøling</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver om brønnparken benyttes til frikjøling (ja/nei)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnpKollVæske</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver type kollektorvæske (Metanol osv)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BrønnparkKollVæske</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Etylenglykol<br />- Kaliumformiat – hycool<br />- Kaliumklorid<br />- Metanol<br />- Propylenglykol<br />- Vann<br />- Etanol – denaturert sprit</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>brønnpFiler</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>link til eventuelle filer som er knyttet til brønnparken</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Link</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FellesegenskaperGrunnvannBorehull

**Assosiasjoner**
EnergiBrønn – rolle: energibrønn – kardinalitet: 5..*

#### LGNOmrådeRefPkt

cirka plassert senterpunkt i lokalt "LGN-område" bestående av en eller flere brønner/oppkommer som benyttes eller har vært benyttet under monitorering av upåvirkede grunnvannsakviferer ("Landsomfattende grunnvannsnett - LGN" -<a href="http://www.grunnvann.no/overvaking_eks.php">http://www.grunnvann.no/overvaking_eks.php</a>)

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektet har punktgeometri</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>antallBrønnerKilder</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>antall brønner og kilder i LGNområdet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolMedium</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>definerer om et borehull er boret slik at den blir permanent åpen; et stykke ned i fjellgrunnen (fjell) eller kun i løsmasser (løsmasse).<br /><br />I dette tilfellet definerer den om LGN-området består av løsmassebrønner eller fjellbrønner</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GeolMediumType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Løsmasse<br />- Fjell</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjonHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>LGN områdets høyde over havet målt i meter</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>lgnNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir NGUs stasjonsnummer i overvåkningsprogrammet "Landsomfattende grunnvannsnett" (LGN)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>nveNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir NVEs stasjonsnummer i overvåkningsprogrammet "Landsomfattende grunnvannsnett" (LGN)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>lgnOmrNavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>stasjonsnavn i overvåkningsprogrammet "Landsomfattende grunnvannsnett" (LGN)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>akviferType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver akvifertype i LGN-området.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>AkviferType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Åpen – grunnvannsoverflaten står i direkte kontakt med atmosfæren, og dermed har akvifærisk trykk<br />- Lukket – grunnvann under hydrostatisk trykk av overliggende tette masser<br />- Artesisk – lukket akvifer der den piezometriske overflaten er jordoverflaten</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>omrEtableringDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver når LGN-området ble etablert</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>lgnOmrFiler</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>link til eventuelle filer som er knyttet til LGNområdet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Link</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>nedbørÅrMin</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir LGN-områdets minste årlige nedbør i perioden 1960 til 1990</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>nedbørÅrMid</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir LGN-områdets gjennomsnittlig årlig nedbør i perioden 1960 til 1990</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>nedbørÅrMaks</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir LGN-områdets høyeste årlige nedbør i perioden 1960 til 1990</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>tempÅrMiddel</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir LGN-områdets gjennomsnittlig årlig temperatur 1960 til 1990</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navnPåVassdrag</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>vassdragsnavn jf NVEs databaser (ved eventuelle endringer ikke oppdatert, se NVEs nettsider)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>vassdragsnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon på nedbørsfelt som et hierarkisk system i henhold til NVEs REGINE (REGIster over NEdbørsfelt (T15).<br />Vassdragsnummer jf NVEs databaser (ved eventuelle endringer ikke oppdatert, se NVEs nettsider)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kommentar</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver formål, historikk, referanser og kontakt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FellesegenskaperGrunnvannBorehull

**Assosiasjoner**
LGNBrønn – rolle: lgnbrønn – kardinalitet: 1..*
LGNGrunnvannOppkomme – rolle: lgngrunnvannoppkomme – kardinalitet: 0..*

#### GrunnvannBrønn

Boret brønn for uttak av grunnvann til vannforsyning

Egenskaper

(ingen)

Relasjoner

**Arv**
GrunnvannBorehull

### Kodelister

#### «Enumeration» GeolMediumType

**Definisjon:** definerer om et borehull er boret slik at den blir permanent åpen; et stykke ned i fjellgrunnen (fjell) eller kun i løsmasser (løsmasse).

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Løsmasse</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fjell</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» BrønnBrukOmfangType

**Definisjon:** underordnet bruksområde (til enkelthusholdning, gårdsbruk osv.)

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Enkelthusholdning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gårdsbruk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Turistnæring</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hytte/fritidsbolig</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Næringsmiddelproduksjon</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Annen industri</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vannverk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vanningsanlegg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vannforsyning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Miljøundersøkelser/overvåkning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Større anlegg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Undersøkelse for energibrønn/anlegg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Undersøkelse for vannforsyning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Forskning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» BrønnHelningType

**Definisjon:** hvilken type helning borehullet kan ha (grovinndeling)

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Loddrett</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skrå</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Horisontal</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» ForingsrørMaterialType

**Definisjon:** foringsrørets materialtype

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Plast</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Rustfritt stål</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stål</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>PVC</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Damprør</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>PE</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» KapasitetMålemetode

**Definisjon:** beskriver målemetode brukt for å måle brønnens kapasitet (vanngiverevne). Hvis brønnen senere er trykket eller sprengt for å øke kapasiteten,  oppgis her den målemetoden som er brukt FØR denne kapasitetsøkningen.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Blåsing</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Prøvepumping</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stigningstest</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» KapasitetØkningType

**Definisjon:** beskriver om brønnen er sprengt eller trykket for å øke kapasiteten

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Trykking</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sprengning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» OppkomBruk

**Definisjon:** overordnet bruksområde for naturlig oppkomme (kilde)

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Vannforsyning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Undersøkelse</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» OppkomUtforming

**Definisjon:** beskriver om oppkomme er naturlig uten inngrep, eller lagt i rør/kum

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Rør</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Naturlig</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kum</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» OppkomBeskyttelse

**Definisjon:** beskriver hvordan oppkommet evt er beskyttet (drenering, gjerde, overbygg)

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Drensledning/-grøft</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gjerde</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Overbygg</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» OppkomFareForurensing

**Definisjon:** inndeler forurensningsfaren for oppkommet til liten/middels/stor

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Liten</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Middels</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stor</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» OppkomTypeForurensing

**Definisjon:** definerer om eventuell forurensningsfare stammer fra bebyggelse, industri, jordbruk etc

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Bebyggelse</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Beitemark</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Industri</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Jordbruk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» BrønnparkKollVæske

**Definisjon:** beskriver type kollektorvæske (Metanol osv)

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Etylenglykol</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kaliumformiat</td>
      <td>hycool</td>
      <td></td>
    </tr>
    <tr>
      <td>Kaliumklorid</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Metanol</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Propylenglykol</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vann</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Etanol</td>
      <td>denaturert sprit</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» AkviferType

**Definisjon:** beskriver akvifertype i LGN-området.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Åpen</td>
      <td>grunnvannsoverflaten står i direkte kontakt med atmosfæren, og dermed har akvifærisk trykk</td>
      <td></td>
    </tr>
    <tr>
      <td>Lukket</td>
      <td>grunnvann under hydrostatisk trykk av overliggende tette masser</td>
      <td></td>
    </tr>
    <tr>
      <td>Artesisk</td>
      <td>lukket akvifer der den piezometriske overflaten er jordoverflaten</td>
      <td></td>
    </tr>
  </tbody>
</table>
