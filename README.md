# Ülesanne 1

### ÜL 1.1
Looge PyCharmis 2 faili:
- Masin.py
- Buss.py

### ÜL 1.2
Masin.py failis kirjeldage üldine klass Masin ja selle init meetod, millel on vähemalt 3 järgmist omadust:
- **mudel**, kuhu saab salvestada masina mudeli nimetuse
- **läbisõit**, kuhu saab salvestada masina läbisõidu arvu
- **istemeteArv**, kuhu saab salvestada masina istmete arvu

Nende omaduste väärtused tuleb init meetodile anda sisendiga.

### ÜL 1.3
Buss.py failis kirjeldage klass Buss, mis on klassi Masin alamklass (tõenäoliselt peate Masin klassi importima) ning pärib nende omadused.

Koostage klassi Buss init meetod, millel on ülemklassi (super()) omadused ning lisage Buss klassile ka 2 uut omadust:
- **piletiHind**, kuhu saab salvestada bussi pileti hinna arvulise väärtuse
- **reisijateArv**, kuhu saab salvestada tegelikult bussiga sõitvate reisijate arvu

### ÜL 1.5
Looge Buss klassis funktsioon arvutaReaalneTulu(self), mis tagastab tegeliku tulu, mida bussis olevate reisijate arvu järgi teenitakse.

### ÜL 1.6
Looge Buss klassis funktsioon arvutaTäituvus(self), mis tagastab bussi täituvuse protsendi, arvestades bussile kirjeldatud istmete ja bussis olevate reisiate arvu.

### ÜL 1.7
Looge Buss klassis funktsioon hindaBussiVanus(self), mis tagastab bussi vanuse. Kui eeldame, et aastas sõidetakse keskmiselt 25000 km, siis saame bussi vanust arvutada jagades tema läbi sõidetud kilomeetrite arvu 25000ga.

### ÜL 1.8
Looge klassist väljas uus muutuja, kuhu salvestate klassi Buss objekti, mille loote järgmiste omadustega:
- **Mudel:** Ford Transit
- **Läbisõit:** 145000
- **Istmete arv:** 15
- **Pileti hind:** 1.35
- **Reisijate arv:** 10

Käivitage selle objekti puhul ülesannetes 1.4 kuni 1.7 loodud funktsioonid. Funktsioonid peaksid tagastama järgmised (arvulised) tulemused:
- Funktsioon **arvutaPotensiaalneTulu** tagastab: 20.25
- Funktsioon **arvutaReaalneTulu** tagastab: 13.5
- Funktsioon **arvutaTäituvus** tagastab: 66.67
- Funktsioon **hindaBussiVanust** tagastab: 5.8