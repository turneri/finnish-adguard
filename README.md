# 🇫🇮 Suomalainen estolista AdGuardille ja Pi-holelle
## Varhaisessa vaiheessa – palaute on tervetullutta!

**Tämä on DNS-estolista, joka keskittyy pääasiassa suomalaisiin mainos-, analytiikka- ja seurantadomaineihin.**  
Lista on tarkoitettu käytettäväksi AdGuard Homen, Pi-holen tai muiden DNS-tason estotyökalujen kanssa.  
Tällä hetkellä lista on melko tiukka, mutta jos kiinnostusta riittää, saatan tehdä eri suojaustason versioita.

**Minulla ei ole paljon kokemusta estolistojen tekemisessä tai Githubin käytöstä, ja tämä on ensimmäinen kumpaakin.**  
Tein tämän, koska en löytänyt kunnollista suomalaista estolistaa, joka olisi tarkoitettu Pi-holelle tai AdGuardille.  
Listassa on varmaan vielä jotain ongelmia, mutta käytän sitä kuitenkin päivittäisessä käytössä ja en ole törmännyt suurempiin ongelmiin  
Pull requestit ja bugiraportit ovat erittäin tervetulleita! Projektiin voi myös halutessaan liittyä mukaan.

### Mitä tämä lista estää?

- Suomalaisia mainosdomaineja 
- Seurantapalveluita suomalaisilla sivuilla  
- Kumppanuus- ja analytiikkadomaineja 
- Joitakin kansainvälisiä seurantapalveluita

### Käyttö Pi-holella

1. Mene kohtaan **Group Management → Lists**  

2. Lisää URL:  
   `https://raw.githubusercontent.com/ImFromKazakstan/finnish-adguard/main/blocklist.txt`  

3. Paina **Add**, ja suorita terminaalissa:  
   `pihole -g` tai klikkaa käyttöliittymässä **Update Gravity**

### Käyttö AdGuard Homella  

1. Mene kohtaan **Filters → DNS blocklists**  

2. Klikkaa **Add blocklist → Add a custom list**  

3. Lisää URL:  
   `https://raw.githubusercontent.com/ImFromKazakstan/finnish-adguard/main/blocklist.txt`  
4. Paina **Save**, ja sitten **Check for updates**
###
###
###
# 🇬🇧 Finnish AdGuard / Pi-hole Blocklist
## Early Stage – Feedback Welcome! 

This is a custom blocklist focused on **Finnish ad, analytics, and tracking domains**.  
It's meant to be used with AdGuard Home, Pi-hole, or other DNS-level blocking tools.  
Currently, the list is quite strict, but if there’s demand, I might create light/medium/strict variants.

I'm new to making blocklists, and this is my first attempt.  
I created this list because I couldn’t find a good Finnish-specific list.  
It works fine for me so far — but it's still early.  
Pull requests and issue reports are very welcome!

### What does it block?  

- Finnish advertising domains
- Trackers on Finnish sites  
- Affiliate and analytics domains  
- Some common international trackers 

### How to use with Pi-hole 

1. Go to **Group Management → Lists**  

2. Add the raw URL:  
   `https://raw.githubusercontent.com/ImFromKazakstan/finnish-adguard/main/blocklist.txt`  

3. Click **Add**, then run:  
   `pihole -g` or in GUI click **Update Gravity**

### How to use with AdGuard Home  

1. Go to **Filters → DNS blocklists**  

2. Click **Add blocklist → Add a custom list**  

3. Paste the raw URL:  
   `https://raw.githubusercontent.com/ImFromKazakstan/finnish-adguard/main/blocklist.txt`  

4. Click **Save**, then **Check for updates**
