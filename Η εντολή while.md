# my-java-exersises
java practise for my studies

Η εντολή while

Η εντολή while χρησιμοποιείται αντί της for όταν δε μπορούμε να προβλέψουμε εύκολα
πόσες φορές θέλουμε να εκτελεστούν οι εντολές, ή όταν δεν έχει σημασία ο αριθμός των
επαναλήψεων αλλά η ικανοποιήση ή όχι της συνθήκης:

while (συνθήκη) {
εντολές;
}


Παράδειγμα:

bool exit_from_loop = false;
while (exit_from_loop = false) {
// υποθετική ρουτίνα που διαβάζει δεδομένα από ένα αρχείο
read_bytes(file1);
// άλλη ρουτίνα που γράφει δεδομένα σε ένα άλλο αρχείο
write_bytes(file2);
if (file_empty(file1) == true)
exit_from_loop = true;
}
