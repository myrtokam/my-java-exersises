# my-java-exersises
java practise for my studies

Η εντολή switch

Η εντολή switch χρησιμοποιείται όταν έχουμε πολλαπλές επιλογές ή τιμές για μια
μεταβλητή και θέλουμε να εκτελεστούν διαφορετικές εντολές για κάθε τιμή. Με την
switch, το προηγούμενο παράδειγμα θα πάρει τη μορφή:

switch (x) {
case 1;
System.out.println(“x is one.”);
break;
case 2;
System.out.println(“x is two.”);
break;
case 3:
System.out.println(“x is three.”);
break;
case 4:
System.out.println(“x is four.”);
break;
default:
System.out.println(“x is not between 1-4.”);
break;
}

Προσέξατε την χρήση της break. Χωρίς την break η εκτέλεση του προγράμματος θα
συνεχίσει μέχρι την επόμενη break ή μέχρι το τέλος της εντολής switch. Αυτό μπορούμε
να το εκμεταλευτούμε αν θέλουμε κοινή αντιμετώπιση ορισμένων περιπτώσεων.

switch (x) {
case 1;
System.out.println(“x is one.”);
case 2;
System.out.println(“x is two.”);
case 3;
System.out.println(“x is three.”);
case 4;
System.out.println(“x is four.”);
System.out.println(“x is between one and four.”);
break;
case 5;
System.out.println(“x is five.”);
case 6;
System.out.println(“x is six.”);
case 7;
System.out.println(“x is seven.”);
case 8;
System.out.println(“x is eight.”);
System.out.println(“x is between five and eight.”);
break;
default:
System.out.println(“x is not between one and eight.”);
break;
}
