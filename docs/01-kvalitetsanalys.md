# Kvalitetsanalys CityBike
 
## 1. Observationer och egenskaper
 
### K1
Egenskap: Performance efficiency
Delegenskap: Time behaviour
Motivering: Kartan är för långsam under belastning (9 sekunder för 300 användare).
 
### K2
Egenskap: Reliabilty
Delegenskap: fault tolarnace
Motivering: Kunden far betala 2 gånger på grund av dalig teckning

### K3
Egenskap: reliabilty
Delegenskap: availabilty 
Motivering: ska kunna användas även vid dåligt teckning.
 
 ### K4
Egenskap: interaction capabilty
Delegenskap: Readabilty
Motivering: användaren ska kunna lista ut hur man avslutar utan hjälpa av en support.
 
 ### K5
Egenskap: information security
Delegenskap: integrity
Motivering: En person ska inte kunna spåras
 
 ### K6
Egenskap: Maintainabilty
Delegenskap: changeabilty
Motivering: man ska kunna ändra affärslogik utan att vara rädd.
 
 ### K7
Egenskap: interaction
Delegenskap: operabilty
Motivering: Det är svårt att navigera eftersom knapparna ligger utanför vyn.
 
 ### K8
Egenskap: saftey
Delegenskap: Risk identification
Motivering: Riskerar att skada användaren eller miljön om batteriet överhettas.
 
 ### K9
Egenskap: flexibilty
Delegenskap: Replaceabilty
Motivering: system ska hantera nya modeller utan för mycket skada.

### K10
Egenskap: maintainabilty
Delegenskap: reusabilty
Motivering: Man ska inte behöva ändra samma sak 12 gånger. Systemet borde ha byggts på återanvändbarkod då man skipper just detta.



## 2. De fyra viktigaste egenskaperna för CityBike

1. saftey

2. reliabilty

3. Interaction ability

4. security


## 3. Mätbara krav

### Mätbarakrav 1 saftey
Krav: Produkten ska kontrolleras emot farliga temperaturer
Mått: När tempraturen är större > 60 ska det avbrytas.
Gränsvärde: får inte överstiga 60 grader.
Hänvisning: k8 avsnitt 7
 
### Mätbarakrav 2 reliabilty
Krav: Produkten ska vara användbar vid dålig teckning. Resan ska inte avbrytas.
Mått: vid förlorad teckning tex under en tunnel 
Gränsvärde: Hämtar all data då den var nere.
Hänvisning: k3 avsnitt 6

### Mätbarakrav 3 interaction cability
Krav: Användaren ska kunna avsluta tjänsten utan hjälp av support
Mått: Många antal sammtal som kommer in till support.
Gränsvärde: inga samtal kommer in till support
Hänvisning: k4 avsnitt 4

### Mätbarakrav 4 security
Krav: Man ska inte komma åt andra användares data.
Mått: 403 error om du försöker komma åt en annan användare sida.
Gränsvärde: alltid nekad om du inte har rätt autenisering
Hänvisning: k5 avsnitt 3
