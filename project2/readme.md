Q1 : Δημθιουργήθηκε μια απλή συνάρτηση η οποία αυξάνει το score ανάλογα με την απόσταση που εχει η θέση με τα φαγητά (Όσο πιο κοντά τόσο το καλύτερο)
και μειώνει τους πόντους ανάλογα με τις αποστάσεις των φαντασμάτων(Οσο πιο κοντα τόσο το χειρότερο.)

Q2:Για κάθε πιθανή κίνηση του agent κάθε φορά καλείται αναδρομικά μέχρι να βρεί τις τιμές στον πάτο του δέντρου,και τις κρατάει σε έναν πίνακα,συκγρίνοντάς
και επιστρέφοντας την καλύτερη ανάλογα με τον agent.Καθώς η αναδρομη ξετιλύγεται απιστρέφεται γίνεται το ίδιο σε κάθε επίπεδο μέχρι που επιστεφεται η καλύτερη κίνηση
του pacman.Ο κώδικας εξηγείται και στα σχόλια.

Q3:Η λογική είναι παρόμοια μονο που τωρα η αναδρομική συνάρτηση επιστρέφει τις τιμές όρια a,b οι οποίες χρησιμοποιούνται για το κλάδεμα των κόμβων που δεν 
πρόκειται να επιστρέψουν προτιμότερη τιμή.

Q4:Η ίδια λογική επαναλαμβάνεται μόνο που τώρα αντί για agents που επιλέγουν τη μικρότερη τιμή από τα παιδιά τους,έχουμε chance nodes οι οποίοι παίρνουν τιμές
από το μέσο όρο των τιμών των παιδιών τους.

Q5:Η συνάρτηση που χρησιμοποιήθηκε είναι ίδια με την evaluationfunction του ερωτήματος 1 και παίρνει 4/5 μονάδες.
