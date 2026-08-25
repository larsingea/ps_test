#### MarinGassoppkommePkt

Datasettet viser eller indikerer gassoppkommer fra havbunnen. Detaljnivået på datasettet tilsier bruk innenfor kartmålestokken: 1:5 000 - 1:500 000.

Geometri:<br />Elementtype: feature<br />Type: geometry-point<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/4258">http://www.opengis.net/def/crs/EPSG/0/4258</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geometry</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Elementtype: feature</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>geometry-point</td>
    </tr>
    <tr>
      <th scope="row">OGC-rolle:</th>
      <td>primary-geometry</td>
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
      <td><strong>lokalid</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokalid</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
    </tr>
    <tr>
      <th scope="row">OGC-rolle:</th>
      <td>id</td>
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
      <td><strong>identifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
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
      <td><strong>identifikasjon.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
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
      <td><strong>identifikasjon.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
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
      <td><strong>identifikasjon.versjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
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
      <td><strong>datafangstdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Dato når objektet siste gang ble registrert/observert/målt i terrenget<br />Merknad: I mange tilfeller er denne forskjellig fra oppdateringsdato, da registrerte endringer kan bufres i en kortere eller lengre periode før disse legges inn i databasen.<br />Ved førstegangsregistrering settes Datafangstdato lik førsteDatafangstdato.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>date-time (string)</td>
    </tr>
    <tr>
      <th scope="row">OGC-rolle:</th>
      <td>primary-instant</td>
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
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Tidspunkt for siste endring på objektet<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>date-time (string)</td>
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
      <td><strong>datauttaksdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>date-time (string)</td>
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
      <td><strong>kvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Posisjonskvalitet</td>
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
      <td><strong>kvalitet.målemetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
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
      <td><strong>kvalitet.nøyaktighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>integer</td>
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
      <td><strong>medium</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Medium</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- alltidIVann<br />- iBygning<br />- iLuft<br />- påIsbre<br />- påSjøbunnen<br />- påTerrenget<br />- påVannoverflaten<br />- tidvisUnderVann<br />- ukjent<br />- underIsbre<br />- underSjøbunnen<br />- underTerrenget</td>
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
      <td><strong>opphav</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
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
      <td><strong>toktNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Unikt navn på måleoppdrag</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
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
      <td><strong>linjeNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Linjenummer i et tokt. Sammen med toktnummer gir denne et unikt navn for linjen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
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
      <td><strong>datafangsttid</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Klokkeslett når objektet ble registrert/observert/målt i felt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
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
      <td><strong>vanndyp</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Vanndyp der prøven er tatt.<br />-- Definition –<br />Water depth where the sample is taken.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>string</td>
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
      <td><strong>gassøyleHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Estimert høyde på en gassøyle i vann</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>integer</td>
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
      <td><strong>styrke</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Relativ styrke på akustisk signal i en gassøyle</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>integer</td>
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
      <td><strong>pålitelighetProsent</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Pålitelighet i prosent (10-100) som viser hvor stor sannsynligheten er for at signaler i vannkolonnedata viser et gassoppkomme</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>integer</td>
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
      <td><strong>geolPavisningstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GeolPavisningstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- 0<br />- 1<br />- 10<br />- 11<br />- 12<br />- 13<br />- 14<br />- 2<br />- 21<br />- 22<br />- 23<br />- 24<br />- 25<br />- 26<br />- 27<br />- 28<br />- 29<br />- 3<br />- 30<br />- 31<br />- 32<br />- 33<br />- 4<br />- 5<br />- 6<br />- 7<br />- 8<br />- 9</td>
    </tr>
  </tbody>
</table>

### Kodelister

#### «Enumeration» Medium

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
      <td>alltidIVann</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>iBygning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>iLuft</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>påIsbre</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>påSjøbunnen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>påTerrenget</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>påVannoverflaten</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>tidvisUnderVann</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>ukjent</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>underIsbre</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>underSjøbunnen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>underTerrenget</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» GeolPavisningstype

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
      <td></td>
      <td></td>
      <td>0</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>1</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>10</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>11</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>12</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>13</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>14</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>2</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>21</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>22</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>23</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>24</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>25</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>26</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>27</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>28</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>29</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>3</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>30</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>31</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>32</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>33</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>4</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>5</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>6</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>7</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>8</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>9</td>
    </tr>
  </tbody>
</table>
