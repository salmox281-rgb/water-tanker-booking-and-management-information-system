# Water Tanker Booking and Management Information System (MIS)
### Nidaamka Maamulka iyo Dalbashada Booyadaha Biyaha

Mashruuc Jaamacadeed oo Dhammaystiran (Comprehensive University Capstone / Coursework Project).

---

## 🌟 Dulmar Guud (Project Overview)

**Water Tanker Booking and Management Information System (MIS)** waa nidaam casri ah oo loogu talagalay shirkadaha biyaha iyo maamulka booyadaha, si ay si fudud ugu maamulaan:
1. Dalabaadka macaamiisha ee biyaha (Guryaha, Dhismaha, Huteellada, Warshadaha).
2. Xaaladda booyadaha iyo darawallada (Fleet & Drivers Dispatch).
3. Dakhliga, rasiidhada iyo lacag-bixinta (EVC Plus, Zaad, Sahal, Kaash).
4. Warbixinnada maalinlaha ah iyo jaantusyada tirokoobka (Interactive Charts & Reports).

Nidaamkan waxa loo dhisay inuu si toos ah uga shaqeeyo kombuyuutar kasta iyo telefoon kasta **adigoon u baahnayn wax barnaamijyo dheeraad ah ama server lacag ah**.

---

## 🚀 10-ka Qaybood ee Nidaamku ka Kooban yahay

1. **Bogga Hore (Public Landing Page):**
   - Hero section soo jiidasho leh, xog-koobka shirkadda, adeegyada biyo gaarsiinta.
   - Foomka dalabka degdegga ah (Quick Booking Widget).
   - Shaxda cabbirka booyadaha iyo qiimaha ($25, $45, $65, $85, $120).
   - Sharaxaadda tallaabooyinka dalbashada (How it works).

2. **Dashboard-ka Maamulka (Admin Dashboard):**
   - 6 Kaar oo tirokoobyo toos ah muujinaya (Macaamiisha, Dalabaadka, Booyadaha Gaaray, Sugaya, Dakhliga Guud, Litirada Biyaha).
   - Jaantus dakhli (Revenue Trend Line Chart).
   - Jaantus xaaladaha dalabka (Status Doughnut Chart).
   - Liiska 5-ta dalab ee ugu dambeeyey iyo xaaladda baabuurta.

3. **Maamulka Macaamiisha (Customer Management):**
   - Diiwaangelinta macaamiil cusub (Add Customer Modal).
   - Wax ka beddelka xogta macmiilka (Edit Customer).
   - Tirtiridda macmiilka (Delete Customer).
   - Raadinta degdegga ah (Instant Customer Search).

4. **Dalbashada Booyadaha Biyaha (Booking Form):**
   - Xulashada macmiil hore ama gelin macmiil cusub.
   - Dooro cabbirka booyadda (5,000L, 10,000L, 15,000L, 20,000L, 30,000L).
   - Xisaabiye qiimo oo toos ah (Dynamic Pricing Calculator).
   - Qoondeynta darawalka iyo taariikhda/waqtiga la rabo.

5. **Maamulka Dalabaadka (Bookings Management):**
   - Shaandheynta xaaladaha: *Pending*, *Approved*, *In Progress*, *Delivered*, *Cancelled*.
   - Beddelka xaaladda dalabka (Change Status Modal).
   - Daabacaadda Rasiidka Rasmiga ah (Official Printable Invoice / Receipt).

6. **Maamulka Gaarsiinta (Delivery & Fleet Management):**
   - Safka dalabaadka waddada ku jira (Live Dispatch Queue).
   - Maamulka booyadaha (Truck plates, Drivers, Capacity).
   - Beddelka xaaladda booyadda (Diyaar ah, Waddada ku jira, Dayactir).

7. **Maamulka Lacagaha (Payment Management):**
   - Diiwaanka lacag-bixinta (Payment Ledger).
   - Lacagaha harsan (Unpaid Balances) iyo badhanka tooska ah ee "Bixi Hadda".
   - Hababka: EVC Plus, Zaad, Sahal, Kaash.

8. **Warbixinnada & Tirokoobyada (Reports & Analytics):**
   - Jaantuska dalabka cabbirrada booyadaha (Bar Chart).
   - Jaantuska degmooyinka ugu dalabka badan (District Demand Chart).
   - Daabacaadda warbixinta guud (Print Report).
   - Soo dejinta kaydka xogta (JSON Data Export).

9. **Bogga Gelitaanka (Login & Security):**
   - 1-Click Demo Login sida Admin (Maamule Guud).
   - 1-Click Demo Login sida Staff (Shaqaale).
   - Ka bixid nidaamka (Logout Session).

10. **Raadinta & Shaandhaynta (Search & Filters):**
    - Raadin toos ah oo bilaa dib-u-kicin ah (Real-time filtering).

---

## 🛠️ Tiknoolajiyada loo Isticmaalay (Technologies Used)

- **Frontend:** HTML5, CSS3, JavaScript (ES6+ Vanilla).
- **Styling:** Tailwind CSS (via CDN) & Custom CSS.
- **Icons:** Font Awesome 6 Pro / Free CDN.
- **Jaantusyada (Charts):** Chart.js CDN.
- **Kaydinta Xogta (Data Storage):** Browser `localStorage` (Offline-first, xogtu kuma lumayso haddii bogga la cusboonaysiiyo).

---

## 📁 Qaab-dhismeedka Faylasha (File Structure)

```
salmo x/
│
├── index.html            # Bogga weyn ee nidaamka (All-in-One SPA)
├── css/
│   └── style.css         # Naqshadda gaarka ah, animations & habka daabacaadda rasiidka
├── js/
│   ├── store.js          # Kaydka xogta (CRUD, LocalStorage, Sample Data)
│   ├── charts.js         # Jaantusyada Chart.js (Dakhliga, Xaaladaha, Degmooyinka)
│   └── app.js            # Habka shaqada ee badhannada, foomamka & navigation-ka
├── assets/
│   └── favicon.svg       # Astaanta booyadda biyaha (Water Droplet Icon)
├── README.md             # Sharaxaadda guud ee mashruuca
└── TILMAAMAHA_ARDEYGA.md # Hagaha tallaabo-tallaabo ee ardayga & sida loo daabaco
```

---

## 🌐 Sida Internet-ka loogu Daabaco Bilaash (Free Hosting)

Waxaad ku daabacan kartaa **Netlify Drop** 30 ilbiriqsi gudahood:
1. Booqo: [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Jiid (Drag and Drop) gal-faylka `salmo x` oo ku rid barta Netlify.
3. Isla markiiba waxaad helaysaa link toos ah oo bilaash ah (tusaale: `https://water-tanker-somalia.netlify.app`).
4. Link-gaas u dir macallinkaaga!
