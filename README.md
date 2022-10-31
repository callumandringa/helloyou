# verhaallijn
![alt text](https://github.com/callumandringa/helloyou/blob/main/Untitled.jpg)

```python

def begin():
    print("BZZZ BZZZ BZZZ BZZZ BZZZ de wekker gaat af")
    print("je wordt wakker op een nieuwe dag")
    print("Je hebt 2 keuzes die je kan maken A Wakker worden\n B door slapen")
    answer = input()
    if answer == ("A"):
        print("Je staat op en je word wakker")
        je_bent_nogsteeds_moe()
    elif answer == ("B"):
        print("je klikt op snooze en slaapt verder")
        wekker_gaat_af()

def je_bent_nogsteeds_moe():
    print("je begint te gapen omdat je moe bent je ogen vallen dicht maar je kan nog bewegen")
    print("je wilt slapen en coffee maken maar je kan niet allebij doen wat ga je kiezen")
    print("A coffee maken\n B door slapen")
    answer = input()
    if answer == ("A"):
        print("glub glub glub slik aahhhhhh i'm ready to go")
        school_tijd()
    elif answer == ("B"):
        print("je zet een wekker en je slaapt")
        print("zzz zzz zzz")
        wekker_gaat_af()


def wekker_gaat_af():
    print("BZZZ BZZZ BZZZ BZZZ de wekker gaat af")
    print("je wordt wakker")
    print("A je wordt wakker\n B slaappilletjes nemen\n C door slapen en dromen")
    answer = input()
    if answer == ("A"):
        print ("je wordt wakker")
        pilletjes_inemen()
    elif answer == ("B"):
        print("je neemt te veel pilletjes in en je kan niet meer wakker worden")
        dom_einde()
    elif answer == ("C"):
        print("je negeert de wekker en je valt in slaap en droomt")
        leraar_probleem()
    
def school_tijd():
    print("je bent eindelijk klaar om naar school te gaan")
    print("A je kan fietsen\n B je kan lopen\n C je kan gebracht worden want je moeder is thuis")
    answer = input()
    if answer == ("A"):
        print("je fietst naar school terwijl je fiets steek je ene weg over maar omdat je moe bent kijk je niet naar links en rechts je bent halverwege over de weg en dan komt er een vrachtwagen die je aanrijdt")
        dom_einde()
    elif answer == ("B"):
        print("je loopt naar school maar je hebt de verkeerde afslag genomen en je bent beland in de bos")
        print("je ziet een paar deuren en je staat voor ze allemaal")
        geheime_deuren()
    elif answer == ("C"):
        print("je moeder vind het goed idee omdat je nog moe bent")
        leraar_probleem()
    
def pilletjes_inemen():
    print("je bent bijna klaar om naar school te gaan")
    print("je moet alleen je elke dag pilletjes nemen en je bent op pad")
    print("je loopt naar de badkamer maar de licht doet het niet je beweegt met je armen totdat je denkt je pilletjes te hebben gevonden")
    print("A de linkerkant\n B de rechter kant")
    answer = input()
    if answer == ("A"):
        print("je grijpt de pilletjes aan de linker kant en je neemt ze in")
        print("je valt op de grond en slaapt")
        leraar_probleem()
    elif answer == ("B"):
        print("je grijpt de pilletjes van de rechter kanbt en je neemt ze in")
        print("je zoekt de deur en je loopt naar buiten om te gaan lopen naar school")
        optijd

def leraar_probleem():
    print("je bent op de een of andere manier op school gekomen vanwege je moeder")
    print("je moet op bezoek komen met je mentor ")
    print("A je kan kiezen voor een schorsing\n B 1 week niet op school hoeven te komen")
    answer= input()
    if answer == ("A"):
        print("je neemt de schorsing en je moeder vind het erg dom dat je die keuze hebt gemaakt")
        print("Later op een dag pleeg je zelfmoord")
        dood()
    elif answer == ("B"):
        print("je neemt 1 week geen school je moder vind het een verstandig keuze")
        print("1 week later")
        je_komt_op_school()

def geheime_deuren():
    print("je ziet 3 deuren voor je neus staan")
    print("deur 1 heeft een boom\n deur 2 heeft een leeuw\n deur 3 heeft een tovenaar")
    print("waar ga je in deur1\n deur2\n of deur3")
    answer = input()
    if answer == ("deur1"):
        print("het is een sprookjesboom en je word gestuurd naar de goede kant van de wereld")
        goed_einde()
    elif answer == ("deur2"):
        print("de leeuw ruikt verder en je word kwaad")
        kwaad_einde()
    elif answer == ("deur3"):
        print("de tovenaar heeft een spreuk op je gegooit waarmee je slaapt")
        leraar_probleem()

def optijd():
    print("je bent optijd op school de mentor vind het erg leuk dat je erbij bent vandaag")
    print("je hebt nu mentor les hoe ga je dit voorbereriden")
    print("A opletten in de les\n B huiswerk maken")
    answer = input()
    if answer == ("A"):
        print("je let op in de les")
        naar_huis()
    elif answer == ("B"):
        print("je maakt je huiswerk voor de volgende les")
        naar_huis()

def je_komt_op_school():
    print("na 1 week thuis zitten ben je eindelijk weer terug op school")
    print("je hebt zometeen mentor les om je mentor te zien hoe ga je gedragen")
    print("A je gaat hem in elkaar slaan\n B je forgeeft de mentor en je word vrienden")
    answer = input()
    if answer == ("A"):
        print("je maakr de mentor dood")
        kwaad_einde()
    elif answer == ("B"):
        print("je frogeeft en je word vrienden met de mentor")
        goed_einde()

def naar_huis():
    print("school is voorbij je fiets heeft een lekke band hoe gaan we naar school")
    print("A lopen\n B moeder bellen om optehalen")
    answer = input()
    if answer == ("A"):
        print("je loopt naar hujius en je zet muziek op en je denkt wat een goede dag vandaag")
        goed_einde()
    elif answer == ("B"):
        print("je moeder neemt niet op en je word gekidnapped bij school")
        dom_einde()

def kwaad_einde():
    print("je bent kwaad geworden")

def goed_einde():
    print("je bent aan de goede kant gekomen gefeliciteerd")

def dood():
    print(".......")

def dom_einde():
    print("je bent gewoon dom")

begin()
```
BZZZ BZZZ BZZZ BZZZ BZZZ de wekker gaat af
je wordt wakker op een nieuwe dag"
Je hebt 2 keuzes die je kan maken A Wakker worden of B door slapen
A
Je staat op en word wakker
B	
Je slaapt verder
je begint te gapen omdat je moe bent je ogen vallen dicht maar je kan nog bewegen
je wilt slapen en coffee maken maar je kan niet allebij doen wat ga je kiezen
A coffee maken of B door slapen
glub glub glub slik aahhhhhh i'm ready to go
e zet een wekker en je slaapt
zzz zzzz zzz 
BZZZ BZZZ BZZZ BZZZ de wekker gaat af
je wordt wakker
A je wordt wakker B slaappilletjes nemen C door slapen en dromen
A
je wordt wakker
B
je neemt te veel pilletjes in en je kan niet meer wakker worden
C
je negeert de wekker en je valt in slaap en droomt
je bent eindelijk klaar om naar school te gaan
A je kan fietsen B je kan lopen C je kan gebracht worden want je moeder is thuis
A
je fietst naar school terwijl je fiets steek je ene weg over maar omdat je moe bent kijk je niet naar links en rechts je bent halverwege over de weg en dan komt er een vrachtwagen die je aanrijdt
B
loopt naar school maar je hebt de verkeerde afslag genomen en je bent beland in de bos
je ziet een paar deuren en je staat voor ze allemaal
C
je moeder vind het goed idee omdat je nog moe bent
je bent bijna klaar om naar school te gaan
je moet alleen je elke dag pilletjes nemen en je bent op pad
je loopt naar de badkamer maar de licht doet het niet je beweegt met je armen totdat je denkt je pilletjes te hebben gevonden
A de linkerkant B de rechter kant"
A
je grijpt de pilletjes aan de linker kant en je neemt ze in
je valt op de grond en slaapt
B
je grijpt de pilletjes van de rechter kanbt en je neemt ze in
je zoekt de deur en je loopt naar buiten om te gaan lopen naar school
je bent op de een of andere manier op school gekomen vanwege je moeder
je moet op bezoek komen met je mentor
A je kan kiezen voor een schorsing B 1 week niet op school hoeven te komen
A
je neemt de schorsing en je moeder vind het erg dom dat je die keuze hebt gemaakt
Later op een dag pleeg je zelfmoord
B
je neemt 1 week geen school je moder vind het een verstandig keuze
1 week later
je ziet 3 deuren voor je neus staan
deur 1 heeft een boom deur 2 heeft een leeuw deur 3 heeft een tovenaar
waar ga je in deur1 deur2 of deur3
deur1
het is een sprookjesboom en je word gestuurd naar de goede kant van de wereld
deur2
de leeuw ruikt verder en je word kwaad
deur3
de tovenaar heeft een spreuk op je gegooit waarmee je slaapt
je bent optijd op school de mentor vind het erg leuk dat je erbij bent vandaag
je hebt nu mentor les hoe ga je dit voorbereriden
A opletten in de les B huiswerk maken
A
je let op in de les
B
je maakt je huiswerk voor de volgende les
na 1 week thuis zitten ben je eindelijk weer terug op school
je hebt zometeen mentor les om je mentor te zien hoe ga je gedragen"
A je gaat hem in elkaar slaan B je forgeeft de mentor en je word vrienden
A
je maakr de mentor dood
B
je frogeeft en je word vrienden met de mentor
school is voorbij je fiets heeft een lekke band hoe gaan we naar school
A lopen B moeder bellen om optehalen
A
je loopt naar hujius en je zet muziek op en je denkt wat een goede dag vandaag
B
je moeder neemt niet op en je word gekidnapped bij school
je bent kwaad geworden
je bent aan de goede kant gekomen gefeliciteerd
.......
je bent gewoon dom



