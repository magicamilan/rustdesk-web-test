# RustDesk Web — test GitHub Pages

Acest repository publică o versiune experimentală a clientului web independent [rdweb](https://github.com/bropines/rdweb), prin GitHub Actions și GitHub Pages.

**Important:** acesta NU este clientul oficial RustDesk și nu a fost auditat aici. Nu include și nu trebuie să includă ID-ul calculatorului, parola sau alte credențiale. Nu folosiți pentru date sensibile înainte de o evaluare independentă.

Aplicația statică este compilată automat dintr-un commit fixat al proiectului rdweb (vezi `.github/workflows/pages.yml`). Conexiunile de control la distanță nu sunt transportate de GitHub Pages; clientul are nevoie de conexiuni WebSocket (WSS) către serverele RustDesk. Opțiunea pentru serverul public este experimentală și poate să nu funcționeze, inclusiv din cauza autentificării obligatorii sau restricțiilor de rețea.

Pentru activare: **Settings → Pages → Build and deployment → Source: GitHub Actions**. Apoi verificați tabul **Actions**.
