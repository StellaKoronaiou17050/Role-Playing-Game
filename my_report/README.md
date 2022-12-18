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
![Screenshot (16)](https://user-images.githubusercontent.com/101730746/208316717-0455e4cd-4a81-4fed-a444-85d4fc52da71.png)


Build and Run

Έκανα Build and Run και ανέβασα το παιχνίδι μου από το GitHub Desktop.



# 3rd Deliverable 


# Conclusions


# Sources

https://www.youtube.com/watch?v=DTp5zi8_u1U

https://itch.io/game-assets/free/tag-royalty-free/tag-unity

https://cupnooble.itch.io/sprout-lands-asset-pack
