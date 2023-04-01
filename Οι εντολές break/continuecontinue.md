# my-java-exersises
java practise for my studies

Οι εντολές break/continue

Πολλές φορές θέλουμε να διακόψουμε την εκτέλεση των εντολών σε ένα loop πρίν από
τη προκαθορισμένη στιγμή. Π.χ. να φύγουμε από ένα infinite loop, ή όταν το πρόγραμμα
λάβει κάποιο σήμα (signal) για έξοδο (π.χ. Control-C).

for (int i = 1; i < 20; i += 3) {
if ( i*i > 100)
break;
System.out.println(i);
}

Το αποτέλεσμα θα είναι:

1
4
7

Η εντολή break χρησιμοποιείται σε όλα τα loops, for, while, do/while.
Αντίστοιχη με την break είναι η continue, η οποία όμως διακόπτει την εκτέλεση μόνο
του τρέχονος iteration και όχι ολόκληρου του loop. Συνεχίζει από το επόμενο iteration.
Στο προηγούμενο παράδειγμα:

for (int i = 1; i < 20; i += 3) {
// να μην τυπωθούν οι άρτιοι(ζυγοί) αριθμοί
if ( i % 2 = 0)
continue;
System.out.println(i);
}

Το αποτέλεσμα θα είναι:
1
7
13
19
