# CE352-UTH
Επεξεργασία Εικόνας


## Δημιουργία περιβάλλοντος Python με χρήση του Anaconda

Εγκαταστείστε το **Miniconda** (ένα ελαφρύ version του Anaconda) ακολουθώντας τις οδηγίες που βρίσκονται [εδώ](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) για κάθε λειτουργικό σύστημα.

Αφού εγκαταστάθηκε το Miniconda, ανοίγουμε μια κονσόλα και χρησιμοποιούμε εντολές από το [Conda cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf) για να δημιουργήσουμε το περιβάλλον μας:

1) Δημιουργία περιβάλλοντος Python 3.11 - `conda create --name ece352_env python=3.11`
2) Επαλήθευση δημιουργίας του περιβάλλοντος - `conda env list`
3) Ενεργοποίηση του περιβάλλοντος - `activate ece352_env`
4) Εγκατάσταση βιβλιοθηκών στο περιβάλλον της Python 3.11 (θα δούμε ποιές θα χρειαστούμε στο μάθημα) - **παράδειγμα** `pip install matplotlib`
5) Επαλήθευση εγκατάστασης της κάθε βιβλιοθήκης - `pip list` και εύρεση της βιβλιοθήκης στη λίστα που εμφανίζεται στην κονσόλα

Εγκαταστείστε το **Jupyter Notebook** στο περιβάλλον Python που δημιουργήσαμε με την εντολή `pip install notebook` και στην συνέχεια ανοίξτε το notebook με την εντολή `jupyter notebook`.

Αν έχει γίνει σωστά η παραπάνω διαδικασία, το jupyter notebook θα έχει ανοίξει ένα νέο παράθυρο στον browser που έχετε ορίσει ως default στην πόρτα 8888 και θα βλέπετε το user directory.
