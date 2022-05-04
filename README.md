# UPN-projektna-naloga
## DVIGALO HRANE
V restavraciji je jedilnica v drugem nadstropju kot kuhinja. Zato je vgrajeno dvigalo (vrtenje motorja naprej/nazaj preko tranzistorja) za tovorjenje hrane. Za pomik gor (vrtenje motorja v eno smer) je potrebno držati tipko GOR. Dviganje se konča, ko doseže dvigalo zgornji položaj, kar zazna senzor Kzg. Pomik dol poteka, če držimo tipko DOL. Ko dvigalo doseže spodnji položaj (senzor Ksp)  se spuščanje ustavi. Hkratni pritisk obeh tipk naj krmilje ignorira. Če je dvigalo v gibanju, to signalizira rdeča LED. Senzorje

## AVTOR:
* Luka Košir
* Tilen Šuštar

### BREADBOARD IN SHEMA
SLIKA BREADBOARDA:

<img width="800" alt="BRD" src="https://user-images.githubusercontent.com/83816742/165065481-2d10d512-d01e-4735-96c7-7cc3759c0878.png">

SLIKA SHEME:

<img width="800" alt="SHEMA" src="https://user-images.githubusercontent.com/83816742/166655495-cfedf580-866f-4ac3-afa0-1ae1cb74e0ba.png">

### SLIKA VEZAVE:
![SLIKA ](https://user-images.githubusercontent.com/83816742/166651538-1cbbf395-715b-498a-bb1b-7edbe52ac66a.png)

### KOSOVNICA:
- 4x stikala
- 3x LED lučke 
- 7x 1kΩ uporov
- 1x breadboard
- 1x arduino uno

### VHODI
| **Oznaka v načrtu** | **Naslov operanda** | **Vrsta kontaknta** | **Pomen**                          |
|-----------------|-----------------|-----------------|--------------------------------|
| A               | X0              | N.C.            | Gumb za igralca 1.             |
| B               | X1              | N.C.            | Gumb za igralca 2.             |
| C               | X2              | N.C.            | Gumb za igralca 3.             |
| R               | X3              | N.C.            | Gumb za resetiranje kviza.     |
| TRIMER          |                 |                 | Nastavljanje kontrasta za LCD. |

### IZHODI
| **Oznaka v načrtu** | **Naslov operanda** | **Aktiven pri** | **Pomen**                                                        |
|---------------------|---------------------|-----------------|------------------------------------------------------------------|
| LED1                | Y0                  | 1               | Prižgana zelena led dioda, če noben gumb ni bil pritisjen.       |
| LED2                | Y1                  | 1               | Prižgana rumena led dioda, če sta pritisnjena ena ali dva gumba. |
| LED3                | Y2                  | 1               | Utripa rdeča led dioda, če so vsi gumbi bili pritisjeni          |
| LCD                 |                     |                 | Prikaz vrstnega reda igralcev, ter zmagovalca.                   |

 
 
### KODA:


### VIDEO:


### KOMENTAR:
Projektna naloga, ki sva jo naredila ni bila pretežka. Lahko bi izboljšala, da bi dodala motorček ampak ni bilo mogoče, ker nisva imela pravih komponent za izdelavo. Kodo bi lahko morda tudi še izboljšala tako, da bi jo skrajšala. Nalogo bi lahko izboljšala z senzorjem za zaznavanje višine dvigala.
