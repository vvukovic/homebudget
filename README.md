# URL #

Gitlab projekt URL:
https://gitlab.com/vvedran86/homebudgetapp

Slack kanal URL:
https://algebrafe.slack.com/archives/C011LE4L0MD

Trello board URL:
https://trello.com/b/DDUl6Ser/algebra-house-budget

Git:
- Branching: https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging
- Pull request: https://www.atlassian.com/git/tutorials/making-a-pull-request

# Upute za koristenje #
1. Nakon prvog povlacenja repozitorija, obratite pozornost na 2 branch-a, master i develop. Kao sto smo ucili, koristite develop za push svega sto trenutno radimo a onda cemo naknadno povlaciti u master kad se osiguramo da je testirano i da radi kako treba. Razlog tome je da se upoznate s radom na Git-u te da osvjezite znanje komandi. Ne morate nuzno koristiti komande, ja osobno inace koristim alate poput SourceTree ili Fork, sto god Vam je lakse.
*Zakljucak: master je glavni branch, develop je radni branch.*

2. Kada lokalno radite promjene ili neki novi feature, koristite svoje brancheve i onda kada ste gotovi s kodom, mozete napraviti PR (pull request) koji cemo moci svi pregledati i sudjelovati sa komentarima i sugestijama. Ovo nije da se osjecate pracenim ili da se ne vjeruje, to je nacin koji se koristi u industriji, jako je jednostavan i efektivan te dodatno vas educira u koristenju Git-a te standardnih normi prilikom testiranja/verifikacije koda. Prilikom PR-a moci cete davati komentare, sugestije te cak i ne sloziti se s kodom i predloziti promjene, prije nego se spoji u develop. Sto se tice PR-a, nakon sto napravite push, Visual Studio Code (ukoliko koristite ugradjeni Terminal) izbacuje informaciju da klikom na link mozete napraviti PR, a to ce izgledati ovako:

> remote:
> remote: To create a merge request for develop, visit:
> remote:   https://gitlab.com/vvedran86/homebudgetapp/-/merge_requests/new?merge_request%5Bsource_branch%5D=develop
> remote:
> To gitlab.com:vvedran86/homebudgetapp.git

*Ukoliko ne koristite VS Code za Git komande, unutar GitLab-a ce vas docekati poruka da kreirate PR, na vrhu stranice. Ako zapnete, pitajte u Slack kanalu, a vise informacija sam stavio na linkove u pocetku.*

**Paznja: pazite da ne odaberete opciju "Delete source branch / Delete source branch when merge request is accepted." jer onda cete obrisati cijeli develop branch (ukoliko niste napravili svoj branch) i sve stvari koje su ikada napravljene. Odaberite "Delete source branch / Delete source branch when merge request is accepted." samo ako ste napravili svoj posebni feature branch koji ste nazvali svojim imenom te onda zelite ozeniti (merge) svoj branch s develop-om.**

3. Repozitorij ce imati pocetni boilerplate projekt koji ce biti postavljen da prikaze Hello World stranicu i sav ostali kod podesen. Naravno, puno toga jos nismo prosli pa ce dosta koda vecini biti nepoznanica, tako da se ne morate brinuti da sve morate znati isprva. Sve ce sjesti kroz vrijeme.

4. Ukoliko negdje zapnete, nesto ne radi, pitajte na kanalu od Slacka pod URL-om gore navedenim, ili ako vec imate upaljen Slack, ime kanala je #homebudget_team. Preporuka je slati snippet-s (unutar kanala) ili cak screenshots tako da lakse druga osoba shvati kada cita. Naravno, unutar kanala mozete i pitati prije nego nesto napravite... Uglavnom, vjerujem da ste vec skuzili sve savjete :)

**Ovo gore su smjernice koje se predlazu da pratite tako da kod bude sto cisci te bolji a ujedno da obnovite znanje oko osnovnih radnji koje ce vas cekati na buducim projektima**

# Pokretanje projekta #
1. Klonirati ovaj projekt putem SSH-a
2. U terminal-u napisati `npm install` da bi se povukle sve potrebne skripte
3. Pokrenuti projekt s `npm start` te utvrditi da se projekt pokrece. Trebala bi se otvoriti stranica na localhost:3000 i docekati Vas poruka "Hello World"

Da ne opisujem dodatne opcije, unutar strukture projekta se nalazi README-NPM.md te bacite oko na opcije koje su Vam dostupne.
Ako negdje zapnete, vicite!

## Happy coding ##
