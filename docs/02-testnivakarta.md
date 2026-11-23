# Testnivåkarta CityBike

## T1
Nivå: enhetstest
Motivering: Det ar ett enhetstest eftersom att man inte behover det ovriga i systemet for att testa resultatet

## T2
Nivå: enhetstest
Motivering: Det ar ett enhetstest eftersom att man inte behover det ovriga i systemet for att testa resultatet

## T3
Nivå: systemtest 
Motivering: Det kors genom en test server som ska efterlikna den verkliga miljon.

## T4
Nivå: enhetstest
Motivering: vi testar logiken, tex att vi ersatter testklienten med en dubbel

## T5
Nivå: systemtest
Motivering: Flera viktiga delar behovs for att testa. kommuikation med apiet tex.

## T6
Nivå: acceptanstest
Motivering: test kunder och projektledaren testar och bekraftar resultatet

## T7
Nivå: integrationstest
Motivering: kors mot en riktigt databas, traffar verklig data

## T8
Nivå: systemtest
Motivering: stresstestar serven

## T9
Nivå: enhetstest
Motivering: testar logiken, ska returna false om man ar < 18 

## T10
Nivå: acceptanstest
Motivering: en ansvarig person kollar/kontrollerar att priser matchar.

## T11
Nivå: integrationstest
Motivering: kors mot ett riktigt api och gor http requests

## T12
Nivå: systemtest
Motivering: hela flodet kors i test miljon som ska efterlikna den verkliga.

## T13
Nivå: enhetstest
Motivering: kontrollerar att en ogiltig email inte ger sant.

## T14
Nivå: acceptanstest
Motivering: Kundtjansten tastar att det kan go fore i kon och bekraftar det.

## T15
Nivå: integrationstest
Motivering: testar delar av systemet. Ser till att stationsservice ger ratt antal cyklar

## T16
Nivå: systemtest
Motivering: testar manga delar i ett testsystem, upplasning och gps.



## Sammanställning
Enhet: 5
Integration: 3
System: 5
Acceptans: 3

## Eget testfall
Krav: Produkten ska kontrolleras emot farliga temperaturer
Givet: cykeln laddas
När: nar batteriest blir 60 grader
Då: Overhettas och slutar fungera tills den kommer under 60 grader.
Nivå: systemtest
Testtyp: funktionellt svartlåda


## kontrolfrågor

1. enhetstest

2. t15, tvekade lite om det var ett enhetstest eller integrationstest. Kom sedan pa att det ar en riktigt databas sa den uteslots.
