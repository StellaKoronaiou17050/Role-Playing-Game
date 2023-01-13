# Lesson: Digital & Serious Games

### First and Last Name: Stella Koronaiou Gkourlia
### University Registration Number: dpsd17050
### GitHub Personal Profile: https://github.com/StellaKoronaiou17050
### Digital & Serious Games Personal Repository: https://stellakoronaiou17050.github.io/Role-Playing-Game/

# Introduction

Στα πλαίσια της εργασίας εξαμήνου του μαθήματος Ψηφιακά Παιχνίδια και Παιγνιώδης Μάθηση κληθήκαμε να δημιουργήσουμε ένα 2D παιχνίδι στο Unity.


# Summary

Όλες οι πηγές που έχουν χρησιμοποιηθεί κατά την διάρκεια του εξαμήνου, για όλα τα παραδοτέα της εργασίας βρίσκονται στο τέλος του Report, στα Sources.


# 1st Deliverable

Για το πρώτο παραδοτέο επέλεξα να εργαστώ στον σταθερό υπολογιστή του εργαστηρίου της Σχολής όπου υπήρχαν ήδη εγκατεστημένα το Unity Hub και το Unity.
Άνοιξα ένα νέο project στο Unity και ξεκίνησα να ακολούθω το tutorial που υπάρχει στην περιγραφή του παραδοτέου μέχρι το βήμα που μας ζητήθηκε.
Όταν το ολοκλήρωσα, ήμουν έτοιμη να ξεκινήσω το δικό μου παιχνίδι στο Unity και δημιούργησα το νεο project "Stella".

Με την βοήθεια του αρχικού tutorial και ενός Youtube video (υπάρχει στα sources) ξεκίνησα να διακοσμώ το map μου. Βρήκα το Tilemap μου από ένα site με διάφορα templates χρησιμοποιώντας κατά την αναζήτηση keywords όπως "grass" και "island", εφόσον ήθελα να δημιουργήσω ένα περιβάλλον εξοχής/μικρού νησιού. Από το ίδιο site βρήκα και τον βασικό μου χαρακτήρα και τον κατέβασα. Κατεβάζοντας το Tilemap, το μετέφερα στο pallette μου και δημιούργησα το map του παιχνιδιού.

![paleta](https://user-images.githubusercontent.com/101730746/201399703-88df3c1b-e70d-436f-bf10-22ca213ca1df.png)
![xaraktiras](https://user-images.githubusercontent.com/101730746/201399707-f046029b-bd05-4514-a392-7199dfba6da7.png)
![xaraktiraskontino (2)](https://user-images.githubusercontent.com/101730746/201399711-36e27647-1118-4c59-8012-5221617df5ee.png)
![olotonisi](https://user-images.githubusercontent.com/101730746/201400181-b3281777-2bd8-4849-b5ab-8e8004b0912d.png)



Αντιμετώπισα ορισμένα προβλήματα με το scale του χαρακτήρα μου όπου ήταν πολύ μικρότερο σε σχέση με αυτό του map. Επίσης είχα μερικά προβλήματα με τους άξονες αλλά ευτυχώς επιλύθηκαν στην πορεία. Επίσης δεν κατάφερα να κάνω την κάμερα να ακολουθεί τον χαρακτήρα και επομένως σε αυτό το στάδιου του παραδοτέου φαίνεται στην οθόνη μόνο το κεντρικό μέρος του νησιού. 
![nisikontino](https://user-images.githubusercontent.com/101730746/201400139-db7e50f9-6d6e-48f5-8b4b-97c905e2aaed.png)


Αφού τελείωσα με όλα τα steps του παραδοτέου, το έκανα Build βάσει του tutorial της περιγραφής και το αντίστοιχου εργαστηρίου που είχαμε κάνει. Αφού έγινε το Build, το έτρεξα για να δω πως δουλεύει μέσω της WebGl. Δυσκολεύτηκα να το ανεβάσω μέσω του GitHub Desktop και εν τέλη το ανέβασα από την web έκδοση του GitHub.

![builded](https://user-images.githubusercontent.com/101730746/201400011-a7e6d73d-a688-4a29-944d-72d96d2d3ffb.png)


# 2nd Deliverable
Blocking Movement

Για τα colliders, δημιούργησα box colliders ξεχωριστά για τα αντικείμενα που βρίσκονται στο top ground tilemap και ξεχωριστά για την περίμετρο της πίστας του νησιού μου, γύρω από το νερό.

![box colliders](https://user-images.githubusercontent.com/101730746/208316619-1084f25e-6610-4f9d-b775-41d003cfa944.png)



Collectibles

Για τα collectibles, χρησιμοποίησα τα μήλα απο το sprite set που είχα κατεβάσει και τα έκανα duplicate για να τα μοιράσω σε διάφορα μέρη του νησιού μου. Ακολουθώντας το tutorial πρόσθεσα ζωή στον χαρακτήρα μου.

![mila](https://user-images.githubusercontent.com/101730746/208316919-b47d02b7-7e6e-4a90-b0df-2583942d9658.png)

Damage Zone - Enemy

Για το damage zone στην πίστα μου επέλεξα μερικές πέτρες που στην συνέχεια άπλωσα και πολλαπλασίασα στην σκηνή μου με την βοήθεια του Sprite Renderer, ακολουθώντας το tutorial. Ο εχθρός του χαρακτήρα μου είναι ένα μωβ τερατάκι που περιπολεί το μήλο μέσα στους ξύλινους φράχτες. Στη συνέχεια εφτιαξα τα animation του εχθρού (ένα για δεξιά και ένα για αριστερά) και τα συνέδεσα με το animator. Αρχικά ο εχθρός μου έκανε moonwalking στην σκηνή (παρέμενε στην ίδια θέση και απλά άλλαζε κατευθύνσεις περπατήματος) και μου πήρε αρκετή ώρα να τον κάνω να περπατάει κανονικά στην σκηνή. Εν τέλη τα κατάφερα αλλάζοντας το speed από 1 σε 0.
![pink sto fraxti](https://user-images.githubusercontent.com/101730746/208316817-c54e80ed-23ad-4207-a623-38c11aa204e7.png)
![ss milo koyti](https://user-images.githubusercontent.com/101730746/208316827-895a1a4f-96d4-4f83-8723-ce9d32b75f9e.png)

![stella ola](https://user-images.githubusercontent.com/101730746/208316685-dd97afd5-7ea0-4b9e-9e65-fd58ddd819a1.png)



Animation

Για το animation του χαρακτήρα μου χρησιμοποίησα τα αρχικά sprites από το sprite set που είχα κατεβάσει. Έκοψα τα κατάλληλα καρε και έφτιαξα animation για να idle mode, walk left/ right, walk up/down. Όπως και για τον εχθρό, έτσι και για τον χαρακτήρα μου, για κάποιο λόγο δεν μου λειτουργούσε η εντολή ‘flip X’ στο animation και έτσι τους άλλαξα τις κατευθύνσεις κάνοντας mirror τις εικόνες του περπατήματος στον photo editor του υπολογιστή. Στη συνέχεια δημιούργησα το StellaController που φαίνεται παρακάτω. Μετά από κάποιες προσπάθειες έκανα τον χαρακτήρα μου να κινείται στις κατάλληλες κατευθύνσεις.
![stella tree](https://user-images.githubusercontent.com/101730746/208316743-809a6def-de21-48e3-adf8-629acb448008.png)
![stella an](https://user-images.githubusercontent.com/101730746/208316767-0434fae0-c3ba-44d9-841d-029945c14f69.png)
![enemy an](https://user-images.githubusercontent.com/101730746/208316777-19ade415-72d3-4dfc-a317-df47fd703530.png)




Projectile

Για το projectile αντικείμενο που θα πετάει ο χαρακτήρας μου στον εχθρό, χρησιμοποίησα ένα sprite σφαίρας που το βρήκα στον φάκελο Assets του Lab07 του μαθήματος. Οι σφαίρες εκτοξεύονται από τον χαρακτήρα μου πατώντας το πλήκτρο C.

![projectile](https://user-images.githubusercontent.com/101730746/208317042-bbd9ac46-8bcc-4835-a7c5-5a19f2a981b0.png)



Cinemachine

Τέλος, για το Cinemachine εφάρμοσα τα βήματα το tutorial και έτσι η κάμερά μου μπορει να ακολουθεί τον χαρακτήρα κατά την κίνησή του στη σκηνή. Πλέον μπορεί να περιηγηθεί σε όλο το νησί και όχι μόνο σε ένα μέρος του, όπως στο προηγούμενο παραδοτέο.
![Screenshot (22)](https://user-images.githubusercontent.com/101730746/208317132-e2161b53-69d8-4170-a2db-9a6a7ace1d8a.png)




Build and Run

Έκανα Build and Run και ανέβασα το παιχνίδι μου από το GitHub Desktop.



# 3rd Deliverable 

Visual Styling - Particles.
 
Για τα particles, ακολουθώντας το tutorial, χρησιμοποίησα ένα sprite καπνού το οποίο φαίνεται να βγαίνει από το κεφάλι του θυμωμένου εχθρού. Το διαμόρφωσα κατάλληλα ώστε να ταιριάζει στις διαστάσεις του εχθρού και να μετακινείται μαζί του.

![kakos smoke](https://user-images.githubusercontent.com/101730746/212221837-42f39e30-691f-4a47-8359-4158fca99e0f.png)
![smoke sprite](https://user-images.githubusercontent.com/101730746/212221924-f9f6c350-e7e3-40ad-82fb-df8fec3148a2.png)
![smoke effect](https://user-images.githubusercontent.com/101730746/212221946-eea7f5eb-286f-4d9d-afd5-726ef21b0230.png)


Visual Styling - User Interface - Head-Up Display.

Με την βοήθεια του tutorial κατάφερα να δημιουργήσω ένα Health Bar και να το τοποθετήσω στην αριστερή πάνω γωνία της σκηνής μου. Βρήκα τα sprites που χρειάστηκα online. Δυστυχώς δεν κατάφερα να κάνω την HealthBar να αυξομειώνεται και επομένως πρόσθεσα και ένα score counter με την βοήθεια ενός youtube tutorial (βρίσκεται με λινκ στα sources). 

![score healthbar](https://user-images.githubusercontent.com/101730746/212222037-91427e0e-8285-4779-94a4-5a99756cc1a8.png)
![makrino](https://user-images.githubusercontent.com/101730746/212222394-cc058863-bec3-4868-b36d-754e24cb3d75.png)


World Interactions 

Παρακολουθώντας ορισμένα youtube tutorials που έχω προσθέσει στα sources, έκανα τον χαρακτήρα μου να κάνει teleport από την μια άκρη του νησιού στην άλλη. Ως πύλες πρόσθεσα δύο κρεβατάκια που βρήκα στο αρχικό tileset μου. Όταν ο χαρακτήρας εισέρχεται σε ένα από αυτά, αυτόματα μεταφέρεται στο άλλο.

![teleport1](https://user-images.githubusercontent.com/101730746/212222128-eb3f4ddf-3ec7-4a15-bd6f-ae81e717820f.png)
![teleport2](https://user-images.githubusercontent.com/101730746/212222142-b6b6209b-cf2a-4343-b972-051b7b9d07a7.png)


Audio
Για τον ήχο ακολούθησα τις οδηγίες και πρόσθεσα background music από την στιγμή που ξεκινά το παιχνίδι. Βρήκα το τραγούδι που επέλεξα από ένα άλμπουμ στο bandcamp το οποίο βρίσκεται στην περιγραφή. Το συνέδεσα στον χαρακτήρα μου για να ακούγεται καθόλη την διάρκεια του παιχνιδιού.
 
 ![bandcamp](https://user-images.githubusercontent.com/101730746/212222176-eda69075-6e74-4c2e-8e7d-1a13f7355b96.png)
 ![music](https://user-images.githubusercontent.com/101730746/212222190-f3611ae0-5060-477e-a4aa-6f5504844ea7.png)


Menu

Με των βίντεο της περιγραφής και του tutorial Lab9 του εργαστηρίου δημιούργησα ένα αρχικό μενού σε μία νέα σκηνή. Πρόσθεσα ένα στιγμιότυπο από το παιχνίδι μου ως background photo, Logo και Play Button.

![menu kai skines](https://user-images.githubusercontent.com/101730746/212222299-dbe3d838-c71c-4cb1-be58-26e65cc5c530.png)
![bg menu](https://user-images.githubusercontent.com/101730746/212222327-8956afcf-a2b6-48c7-9c61-0da2df0b9ca2.png)
![menu](https://user-images.githubusercontent.com/101730746/212222348-6a3f98ca-a9eb-47e9-a7f8-21d431ae38c8.png)

Build and Run

Έκανα Build and Run και ανέβασα το παιχνίδι μου από το GitHub Desktop.

# Conclusions

Ήταν πολύ ενδιαφέρον project και με έκανε να εξοικειωθώ με το πρόγραμμα του unity. Υπήρχε ένας βαθμός δυσκολίας αλλά με βοήθησε αρκετά το υλικό που υπάρχει online. Εάν υπήρχε περισσότερος χρόνος θα ήθελα να συνεχίσω να χτίζω το νησί μου και να προσθέσω περισσότερες πίστες και χαρακτήρες. Επίσης θα ήθελα στο μέλλον να μάθω πως να χρησιμοποιώ τον φωτισμό.

# Sources

https://www.youtube.com/watch?v=DTp5zi8_u1U

https://itch.io/game-assets/free/tag-royalty-free/tag-unity

https://cupnooble.itch.io/sprout-lands-asset-pack

https://www.spriters-resource.com/

https://www.youtube.com/watch?v=qHvbgvYcCeg

https://www.youtube.com/watch?v=FfaG9TvCe5g

https://www.youtube.com/watch?v=zc8ac_qUXQY

https://www.youtube.com/watch?v=J77CMuAwVDY

https://www.youtube.com/watch?v=evDKHClDxU8

https://www.youtube.com/watch?v=wNj84aWxNy4

https://touhoujam.bandcamp.com/album/touhou-jam-jams
