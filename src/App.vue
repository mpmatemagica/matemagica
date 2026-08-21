<script setup>
import logo from '@/assets/logo.png'
</script>

<template>
  <header>
    <nav>
      <a href="/"><img :src="logo" alt="My Website" class="logo" /></a>

      <div class="nav-links">
        <a href="#matura">Matura</a>
        <a href="#cjenik">Cjenik</a>
        <a href="#contact">Kontakt</a>
      </div>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h1 style="text-align: center; font-size: 4rem;">MATEMAGICA</h1>
      <h2 style="text-align: center; margin-bottom: 30px; margin-top: 10px;">Instrukcije iz matematike</h2>
      <h2>Pozdrav!</h2>
      <p>
        Ja sam Massimo, nastavnik matematike s višegodišnjim iskustvom u nastavi i instrukcijama iz matematike.<br>
        Nudim instrukcije iz matematike za osnovnu i srednju školu te pripreme za <a href="#matura">državnu maturu</a> za A i B razinu.
      </p>
    </section>

    <section id="why">
      <h2>Zašto instrukcije?</h2>
      <p>
        U današnje vrijeme, mnoštvo učenika diljem Hrvatske ima problema s matematikom i ostalim predmetima iz znanstvenog područja i trebaju pomoć stručne osobe kako bi lakše shvatili gradivo koje ne shvaćaju. Često učenici trebaju samo malo više motivacije i objašnjenja da bi dostigli svoj potencijal!<br>Na instrukcijama:
      </p>
      <ul>
        <li>Uz podučavanje gradiva, učimo i kako učiti matematiku.</li>
        <li>Uzimamo u obzir predznanje učenika te krećemo od njega.</li>
        <li>Gradimo most između učenikovog trenutnog znanja i željenog znanja.</li>
        <li>Podučavamo kako se snaći u raznim matematičkim problemima i situacijama tako da učenik bude samostalan.</li>
      </ul>
      <p>
        Ukoliko ste zainteresirani, <a href="#contact">kontaktirajte</a> me!
      </p>
    </section>

    <section id="matura">
      <h2>Državna matura</h2>
      <p>
        Državna matura iz matematike je ispit koji polaže gotovo svaki učenik četvrtog razreda srednje škole u Hrvatskoj. Učenici često strahuju od tog ispita jer je on obvezan za nastavak školovanja na fakultetu i teško je prisjetiti se cijelog gradiva matematike osnovne i srednje škole.<br>Instrukcije za državnu maturu organizirane su na način da:
      </p>
      <ul>
        <li>Uzimamo u obzir predznanje učenika te se fokusiramo na područja gdje je učenik slabiji.</li>
        <li>Objašnjavamo detaljan program državne mature ovisno o razini.</li>
        <li>Rješavamo zadatke s prošlih državnih matura zajedno.</li>
        <li>Prolazimo gradivo u organiziranim i smislenim cjelinama.</li>
        <li>Učenik nakon svakog sata instrukcija dobiva malu zadaću za sljedeći sat da bi se osigurao kontinuirani rad, ne samo za vrijeme instrukcija.</li>
      </ul>
      <p>
        Program priprema za državnu maturu je osmišljen da traje 30 sati (tj. 30 tjedana), od listopada do lipnja. Osim instrukcija fokusiranih na temeljno gradivo i zadatke s prošlih državnih matura, uključuje i:
      </p>
      <ul>
        <li>Početni dijagnostički test</li>
        <li>Personalizirani plan učenja za ispit državne mature</li>
        <li>Kontinuirano praćenje napretka</li>
        <li>Tjedno zadavanje i kontrolu domaće zadaće</li>
      </ul>
      <p>
        Ukoliko ste zainteresirani, <a href="#contact">kontaktirajte</a> me!
      </p>
    </section>

    <section id="cjenik">
      <h2>Cjenik</h2>
      <table>
        <thead>
          <tr>
            <th>Opis</th>
            <th>Cijena</th>
          </tr>
        </thead>

        <tbody>
          <tr>
            <td>Instrukcije OŠ, SŠ i matura - 60 min</td>
            <td>20 €</td>
          </tr>

          <tr>
            <td>Instrukcije - 5x60 min</td>
            <td>80 €</td>
          </tr>

          <tr>
            <td>Individualna godišnja priprema za maturu (30 tjedana)</td>
            <td>450 €</td>
          </tr>
          <tr>
            <td>Godišnja priprema za maturu - grupa 2 učenika</td>
            <td>300 € po učeniku</td>
          </tr>
          <tr>
            <td>Godišnja priprema za maturu - grupa 3 učenika</td>
            <td>250 € po učeniku</td>
          </tr>
          <tr>
            <td>Godišnja priprema za maturu - grupa 4 učenika</td>
            <td>200 € po učeniku</td>
          </tr>
        </tbody>
      </table>
      <br>
      Instrukcije se provode online na platformi Google Meet (uživo za sjeverozapadnu Istru). Potreban je samo mobitel/računalo, papir, kemijska i kalkulator!
    </section>

    <section id="contact">
      <h2>Kontakt</h2>
      <p>
        E-mail:
        <a href="mailto:kontakt@matemagica.hr">
          kontakt@matemagica.hr
        </a><br>
        WhatsApp / Viber: 091 322 2031
      </p>
    </section>
  </main>

  <footer style="text-align: right; font-size: 0.8rem">
    <p>© 2026 Matemagica, obrt za poduke<br>vl. Massimo Pincin</p>
  </footer>
</template>