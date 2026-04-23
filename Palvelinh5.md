# h5

## Tiivistelmä 

Getting Started - What is Git?

  - Git ei tallenna pelkästään pieniä tekstejä
  - Kaikki tapahtuu omalla koneella, joten se on tosi nopeaa ja toimii vaikka ilman nettiä
  - Git varmistaa kaiken tiedon säilymisen muuttumattomana antamalla jokaiselle tiedostolle oman tunnisteen
  - Gittiin tallennettuja asioita on lähes mahdotonta hävittää vahingossa, joten voi vapaasti testailla eri juttuja ilman pelkoa siitä, että hävität jotain lopullisesti.
  - Muokataan tiedostoja, jonka jälkeen otettaan mukaan haluamat muutokset ja lopuksi tallennetaan Gittiin.

git add --all && git commit; git pull && git push

  - git add --all: Valmistelee kaikki projektin muutokset. 
  - git commit: Lyö lukkoon ja tallentaa muutokset pysyväksi. 
  - git pull: hakee uusimmat tiedostot ja yhdistää ne omiin tiedostoihin. 
  - git push: Siirtää omat paikalliset tallennukset githubiin muiden nähtäville ja käytettäväksi.

## Tehtävä A

<img width="882" height="813" alt="image" src="https://github.com/user-attachments/assets/343e84e8-4c5c-49d8-82d7-1a03223a5407" />

loin uuden sunshine nimisen repositorion ja lisäsin sille lyhyen kuvauksen. Valitsin julkisen asetuksen, jotta kuka tahansa voi nähdä projektin. 
Heti perään lisäsin myös README tiedoston helpottamaan sisällön lisäämistä. Valitin peruslisenssin ja jätin .gitignore iedoston tässä vaiheessa pois.

## Tehtävä B

<img width="786" height="262" alt="image" src="https://github.com/user-attachments/assets/a5d540ae-c09c-4d6a-9b07-0ddfec47d9ff" />
<img width="552" height="193" alt="image" src="https://github.com/user-attachments/assets/25e5072e-5d1b-4489-82b4-dc01dd315d4b" />
<img width="806" height="407" alt="image" src="https://github.com/user-attachments/assets/63ecbcf4-210c-4154-a3c4-092c092ad811" />
<img width="857" height="577" alt="image" src="https://github.com/user-attachments/assets/945eaf9f-4b7d-43f5-a40f-f49c62359dae" />

Komenolla clone kloonasin sunshine repositoryn omalle koneelleni SSH yhteyden kautta, minkä jälkeen lisäsin README tiedostoon "testuas :D" tekstin. Ajoin git pull komennon ja tein commit tallennuksen viestillä 'lisätty uusi kansio'. 
Lopuksi lähetin muutokset GitHubiin git push komennolla. Kun päivitin selaimen, kirjoittamani teksti näkyi README teidostossa.

## Tehtävä C 

<img width="542" height="255" alt="image" src="https://github.com/user-attachments/assets/05da296b-c6ea-4e37-aad4-62d0d35ba481" />

<img width="502" height="106" alt="image" src="https://github.com/user-attachments/assets/fcd9fc4e-65da-496a-b411-975f94f1d90d" />

<img width="552" height="193" alt="image" src="https://github.com/user-attachments/assets/b91d3b5f-122d-4180-ba76-ba781bc060fa" />


Kirjoitin README.md-tiedostoon 'hölmötekstiä', mutta en puskenut niitä githubbiin. 
Ajoin komennon git reset --hard, joka pyyhki tallentamattomat muutokset ja palautti viimeisimmän commitin.


## Tehtävä D 

<img width="1163" height="451" alt="image" src="https://github.com/user-attachments/assets/f8627fbc-52ca-4f1b-91e6-ed9cfa223430" />

Ajoin komennon git log --patch, joka tulostaa historiikin. Commit 62cf1d28431812e4df53c4740c34d357a0da511a kohta todistaa sen, että minun tekemäni muutokset ovat lisätty Githubbiin ja vihreä väri todistaa sen myös. 
Kohta "Commit 1460bdd7e2be3e7ad3d619972af5e6f06aab3e4a" on gitHubin automaattinen alustus, josta näkee kanssa omsitajan ja päivämäärän. 

## Tehtävä E

<img width="727" height="97" alt="image" src="https://github.com/user-attachments/assets/7049d0b4-441a-4c40-b62c-00f5e3fe5786" />
<img width="727" height="97" alt="image" src="https://github.com/user-attachments/assets/e4db80bb-01ba-4669-873d-f843d38d4b68" />

Ensin avasin ansible kansion jonne ajoin git init sekä git add --all. Komentojen jälkeen kirjoitin site.yml kansioon hastagailla tehtävä e testaus.
Tämän jälkeen ajoin git pull ja git commit tallennuksen, jolla lukitsin muutoksen projektin historiaan. Lopulta ajoin Git log, josta näkee muutokset. 

## Lähteet

https://medium.com/@itsmepankaj/git-workflow-add-commit-push-pull-69adf44cf812

https://terokarvinen.com/palvelinten-hallinta/#laksyt

https://git-scm.com/book/en/v2

https://github.com/kiminyrhi-pixel/sunshine
