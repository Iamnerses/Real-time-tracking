# Հետագիծ

## Իրական ժամանակում հետեւման համակարգ
**Նախագծի անուն:** Հետագիծ  
**Պատրաստող:** Ներսես Սարգսյան  
**Փաստաթղթի նպատակ:** Նախագծի պահանջների փաստաթութղթ  
**Փաստաթղթի կարգավիճակ:** Ընթացքում  
**Վերջին փոփոխութիւն:** 25 մարտ 2025  

---

## Բովանդակութիւն
1. [Ներածութիւն](#ներածութիւն)
   - [Փաստաթղթի մասին](#փաստաթղթի-մասին)
   - [Յղումներ](#յղումներ)
   - [Կարճ նկարագրութիւն](#կարճ-նկարագրութիւն)
   - [Աշխատանքի ընթացք](#աշխատանքի-ընթացք)
2. [Պահանջներ](#պահանջներ)
   - [Գործառութային պահանջներ](#գործառութային-պահանջներ)
3. [Համակարգի գծապատկեր](#համակարգի-գծապատկեր)

---

## Ներածութիւն

### Փաստաթղթի մասին
Այս փաստաթղթում սահմանվում են "Հետագիծ" նախագծի պահանջները։

### Յղումներ
- [1]

### Կարճ նկարագրութիւն
Հետագիծը իրական ժամանակում գործողությունների տեղադրությունը վերահսկելու համակարգ է, որը թույլ է տալիս գործողության գործող անձանց կամ օբյեկտների գտնվելու վայրը շարունակաբար տեսնել քարտեզի վրա։ Համակարգը նաև պետք է աշխատի արտակարգ իրավիճակի (օրինակ՝ մասնակցին շտապ դուրս բերելու (էվակուացիայի) դէպքում  անհրաժեշտության դէպքում) եւ միաժամանակ կարողանա անցանց տարբերակով փոխանցել տեղադրութեան տուեալները, որը արագ արձագանքման խումբը կընդունի և կաւգտագործի։
Համակարգը բաղկացած է հետեւեալ մասնիկներց․

- **Բջջային Յաւելուած**
  - Նախատեսուած է տուեալների շարժուն ձեւով ցուցադրման համար, ինչպէս նա եւ սարքի հետ համագործակցելով ստանում եւ փոխանցում է տեղադրութեան տուեալները։
- **Տեղորոշիչ եւ փոխանցող / ընդունող սարք**
  - Ունի GPS եւ ստանում է տեղադրության տուեալներ, նախատեսուած է գործողութեան մասնակիցի (տուեալների փոխանցոեւմ) եւ արագ արձագանքման խմբի (տուեալների ընդունում) աւգտագործման համար։
Հետագիծը իրական ժամանակում գործողությունների տեղադրությունը վերահսկելու համակարգ է, որը թույլ է տալիս գործողության գործող անձանց կամ օբյեկտների գտնվելու վայրը շարունակաբար տեսնել քարտեզի վրա։ Համակարգը նաև պետք է աշխատի արտակարգ իրավիճակի դեպքում (օրինակ՝ մասնակցին շտապ դուրս բերելու՝ էվակուացիայի անհրաժեշտության ժամանակ) և միաժամանակ կարողանա անցանց տարբերակով փոխանցել տեղադրության 
տվյալները, որը արագ արձագանքման խումբը կընդունի և կօգտագործի։
          
Մանրամասն կներկայացուոի գործառութային պահանջներ բաժնում։

### Աշխատանքի ընթացք
Համակարգը ունի երեք հիմնական դերակատար՝
1. **Մասնակից** – Վերահսկվող անձ, տեխնիկա կամ օբյեկտ։
2. **Վերահսկող** – Վերահսկող անձ ԿԿ-ում (կառավարման կենտրոնում)։
3. **Արագ արձագանքման խումբ** – Արտակարգ կարգավիճակ ստանալու դեպքում արձագանքող խումբ։

Յուրաքանչյուրի համար սահմանված են առանձնահատուկ գործառույթներ։
![System Diagram](assets/մասն..png)
![System Diagram](assets/Վերասհ.jpg)
![System Diagram](assets/ախումբ.png)



---

## Պահանջներ

### Գործառութային պահանջներ
Ստորև ներկայացված են բջջային հավելվածի պահանջները։

| Ցուցիչ | Նկարագրություն | Առաջնահերթություն |
|--------|--------------|----------------|
| MA-001 | Ըստ աւգտատերի հասանալիութեան գործողութիւնների եւ տուեալներից ցուցադրում | Պարտադիր |
| MA-002 | Քարտեզի վրա տուեալներիա արտապատկերում եւ փոփոխութեան հնարաւորութիւն | Պարտադիր |
| MA-003 | BLE սարքաւորման հետ կցման հնարաւորութեան հնարաւորութիւն | Պարտադիր |
| MA-004 | Գործողութիւնների որոնում եւ զտում (ըստ ամսաթվի, երթուղու եւ այլն): | Ցանկալի է |
| MA-005 | GPS տուեալների ստացում հեռախոսի տուիչներից | Պարտադիր |
| MA-006 | Կցուած սարքի ուղղարկուած տվյալների ստացում եւ մշակում | Պարտադիր |
| MA-007 | Սարքից եւ հեռախոսից ստացուած տուեալների համադրում, ըստ ճշտութեան եւ ողարկում սպասարկիչ | Պարտադիր |

### Համակարգի գծապատկեր
Համակարգի ճարտարապետության գծապատկեր։

![System Diagram](assets/կառռ.png)

### Սարքի գործառութային պահանջներ

| Ցուցիչ | Նկարագրություն | Առաջնահերթություն |
|--------|--------------|----------------|
| EP-001 | GPS ընդունող եւ մշակող մաս | Պարտադիր |
| EP-002 | BLE միացման հնարաւորութիւն | Պարտադիր |
| EP-003 | Ելքի / մուտքի միջերեսներ | Ցանկալի է |
| EP-004 | GPRS կապի հնարաւորութիւն | Կարող է ունենալ |
| EP-005 | LoRa կապի հնարաւորութիւններ | Ցանկալի է |
| EP-006 | Տուեալների թարմացման եւ փոխանցման հաճախականութիւն առաւելագոյնը 10 վ | Պարտադիր |


---

## Եզրակացություն
Այս փաստաթուղթը հանդիսանում է Հետագիծ իրական ժամանակում հետևման համակարգի մշակման հիմքը։ Հետագայում մանրամասները առաւել կը հստակեցուեն։
