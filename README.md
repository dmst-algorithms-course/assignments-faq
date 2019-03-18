# Συχνές Ερωτήσεις για τις Εργασίες (Assignments FAQ)

* [Ποια Python;](#which-python)

* [Πού βρίσκω την Python;](#where-python)

* [Πρέπει να προσέξω κάτι στην εγκατάσταση;](#installation-attention)

* [Πώς ξέρω ότι η Python έχει εγκατασταθεί σωστά;](#check-installation)

* [Σε τι θα γράψω το πρόγραμμά μου;](#program-editing)

* [Τι είναι αυτά τα Emacs και Vim;](#emacs-vim)

* [Γιατί editors και όχι IDEs;](#editors-vs-ides)

* [Πώς τρέχω ένα πρόγραμμα Python;](#running-python-programs)

* [H Python δεν βρίσκει το πρόγραμμά μου!](#python-program-wont-run)

* [Τι είναι κατάλογος και τι φάκελος;](#directory-vs-folder)

* [Πώς χρησιμοποιούμε τη γραμμή εντολών;](#command-line-launch)

* [Αυτό το Git είναι κάτι για να μας κάνει τη ζωή δύσκολη;](#whats-the-deal-with-git)

* [Πού μπορώ να μάθω παραπάνω για το Git;](#learn-git)

* [Εκτός από τη γραμμή εντολών, υπάρχει άλλος τρόπος να δουλέψω με το Git στο GitHub;](#git-desktop)

* [Πού μπορώ να μάθω περισσότερα για το GitHub Desktop;](#learn-github-desktop)

* [Ποια είναι η διαφορά μεταξύ του Git και του GitHub;](#git-vs-github)

* [Κάθε πότε πρέπει να αποθηκεύω κάτι στο GitHub;](#commit-early-commit-often)
  
* [Το αποθετήριό μου είναι ιδιωτικό ή δημόσιο;](#repository-private-public)

* [Πώς μπορώ αν ελέγξω ότι το πρόγραμμά μου έχει την ίδια έξοδο με τις λύσεις που δίνετε;](#diffing-linux-tools)

* [Πού μπορώ να μάθω περισσότερα για τη γραμμή εντολών και το λειτουργικό σύστημα Linux;](#command-line-linux)

* [Δεν μπορώ να βγάλω άκρη, να σας στείλω ένα μήνυμα με φωτογραφία του προβλήματος;](#code-photo)

* [Δεν μπορώ να βγάλω άκρη, να σας στείλω ένα μήνυμα με τον κώδικά μου;](#code-mail)

* [Μπορώ να ψάξω στο Google, Stack Overflow, κ.λπ. για απορίες;](#web-solution-search)

* [Είναι αλήθεια ότι ελέγχετε όλες τις εργασίες για αντιγραφές;](#plagiarism)

* [Κοντεύουν ξημερώματα και έχω κολλήσει σε πέντε γραμμές που δεν ξέρω τι λάθος κάνω. Έχω πρόβλημα;](#have-i-got-a-problem)

* [ Κοντεύουν ξημερώματα και έχω κολλήσει σε πέντε γραμμές που δεν ξέρω τι λάθος κάνω. Τι μου προτείνετε;](#dont-know-what-to-do)


## <a name="which-python"/></a>Ποια Python;

Θα πρέπει να χρησιμοποιήσετε την πιο πρόσφατη έκδοση της σειράς 3 της Python.

## <a name="where-python"/></a>Πού βρίσκω την Python;

Στον [ιστότοπο της Python](https://www.python.org), στο σύνδεσμο
downloads. Εναλλακτικά, μπορεί να βολεύει (ειδικά τους χρήστες
MS-Windows) η διανομή
[Anaconda](https://www.anaconda.com/distribution/) της Python.

## <a name="installation-attention"></a>Πρέπει να προσέξω κάτι στην εγκατάσταση;

Σε περίπτωση που χρησιμοποιείτε MS-Windows:

* Αν δεν χρησιμοποιείτε τη διανομή Anaconda, θα πρέπει να διαλέξετε την
  επιλογή με την οποία η Python θα προστεθεί στο PATH του συστήματός
  σας.

* Αν χρησιμοποιείτε τη διανομή Anaconda και δεν έχετε επιλέξει κατά
  την εγκατάσταση να προστεθεί η Python στο PATH του συστήματός σας,
  τότε θα πρέπει να τρέχετε τα προγράμματά σας μέσω της γραμμής
  εντολών Anaconda (Anaconda prompt).

## <a name="check-installation"></a>Πώς ξέρω ότι η Python έχει εγκατασταθεί σωστά;

Θα πρέπει όταν βρίσκεστε στη γραμμή εντολών του συστήματος ή στη
γραμμή εντολών Anaconda, αναλόγως της διανομής, να δίνετε `python` και να
εμφανίζεται ο διερμηνέας της γλώσσας.

## <a name="program-editing"></a>Σε τι θα γράψω το πρόγραμμά μου;

Το πρόγραμμα μπορείτε να το γράψετε σε έναν επιμελητή κειμένου
(editor). Οι τέσσερεις προτεινόμενοι είναι:

1. [Atom](https://atom.io/)
2. [Sublime Text](https://www.sublimetext.com/)
3. [Visual Studio Code](https://code.visualstudio.com/) (με το Python
   extension). 
3. [Emacs](https://www.gnu.org/software/emacs/)
4. [Vim](https://www.vim.org/)

O Sublime είναι ο μόνος από τους παραπάνω που είναι εμπορικό προϊόν.
Οι άλλοι τέσσερεις δίνονται ελεύθερα, με άδειες ανοιχτού κώδικα.

## <a name="emacs-vim"></a>Τι είναι αυτά τα Emacs και Vim;

Ιερά τέρατα. 

Πρόκειται για τους ισχυρότερους editors που υπάρχουν, με ιστορία
δεκαετιών. *Δεν είναι εύκολοι στη χρήση*. Αν θέλετε να τους
χρησιμοποιήσετε, θα πρέπει να αφιερώσετε χρόνο για να δείτε πώς
δουλεύουν και τι δυνατότητες έχουν.

## <a name="editors-vs-ides"></a>Γιατί editors και όχι IDEs;

Τα ολοκληρωμένα περιβάλλοντα ανάπτυξης (Integrated Development
Environments, IDEs) είναι χρήσιμα εργαλεία, αλλά δεν είναι απαραίτητα
για τις εργασίες σας. Επιπλέον, η δημοτικότητά τους ποικίλει ανά
γλώσσα. Ενώ είναι πολύ δημοφιλή στις γλώσσες Java και C#, δεν
συμβαίνει το ίδιο με άλλες γλώσσες, όπως π.χ. Python. Αυτό δεν
σημαίνει ότι δεν υπάρχουν και για Python.

Η χρήση editors έναντι IDEs έχει τα εξής πλεονεκτήματα:
1. Είναι πιο γρήγοροι.
2. Δουλεύουν για όλες τις γλώσσες προγραμματισμού. Δεν χρειάζεται να
   μαθαίνετε ένα εργαλείο για κάθε γλώσσα.
3. Όταν τους μάθετε, μπορείτε να δουλεύετε αποτελεσματικότερα.
4. Είναι χρήσιμοι για κάθε χρήση, και όχι μόνο για συγγραφή
   προγραμμάτων. Το παρόν κείμενο είναι γραμμένο με τον Emacs, όπως
   και το σύνολο των σημειώσεων και των διαφανειών του μαθήματος.

Η χρήση IDEs πλεονεκτεί έναντι editors όταν:
1. Η γλώσσα που χρησιμοποιούμε έχει πολύ γραφειοκρατία (πρέπει να
   γράψουμε πολλά πράγματα και πολλές πανομοιότυπες μεθόδους για να
   κάνουμε τη δουλειά μας, και αυτά μπορούν να αυτοματοποιηθούν).
2. Θέλουμε να κάνουμε αποσφαλμάτωση του κώδικά μας παρακολουθώντας την
   εξέλιξη των τιμών μεταβλητών και των περιεχομένων θέσεων μνήμης.

Πάντως, τα IDEs τις περισσότερες φορές μας γλυτώνουν από κουτή
δουλειά. Ο περισσότερες κόπος στον προγραμματισμό δεν έγκειται στη
συγγραφή μεθόδων `get()` και `set()`, αλλά σε λίγες και ουσιώδεις
γραμμές κώδικα. Δεν είναι σπάνιο το φαινόμενο να περάσει κάποιος μία
ημέρα σε ένα πρόγραμμα και να καταφέρει να γράψει μόνο 10 γραμμές
κώδικα. Και μπορεί να είναι οι πιο κρίσιμες γραμμές κώδικα όλου του
προγράμματος.

## <a name="running-python-programs"></a>Πώς τρέχω ένα πρόγραμμα Python;

Στη γραμμή εντολών δίνουμε:

```bash
python my_program.py
```
όπου `my_program.py` είναι το όνομα του προγράμματός μας. 

## <a name="python-program-wont-run"></a>H Python δεν βρίσκει το πρόγραμμά μου!

Όταν τρέχουμε:
```bash
python my_program.py
```

πρέπει να βρισκόμαστε στην ίδια θέση (κατάλογο, φάκελο) που βρίσκεται το αρχείο `my_program.py`.

## <a name="directory-vs-folder"></a>Τι είναι κατάλογος και τι φάκελος;

Το ίδιο πράγμα. Ο όρος *φάκελος* (folder) έχει επικρατήσει όταν
επεξεργαζόμαστε αρχεία με γραφική διεπαφή, γιατί χρησιμοποιούμε τη
«μεταφορά του γραφείου» (desktop metaphor), όπου ο υπολογιστής μας
είναι μια επιφάνεια εργασίας που περιέχει φακέλους, και αυτοί
περιέχουν αρχεία.

Στην πραγματικότητα οι φάκελοι υλοποιούνται στο λειτουργικό σύστημα
του υπολογιστή ως *κατάλογοι* (directories). Γι' αυτό και οι εντολές
για να δημιουργήσετε και να χειριστείτε φακέλους από τη γραμμή εντολών
στην πραγματικότητα αναφέρονται σε καταλόγους (π.χ. `cd` ή `chdir`
σημαίνει change directory, `mkdir` σημαίνει make directory, κ.λπ.).

## <a name="command-line-launch"></a>Πώς χρησιμοποιούμε τη γραμμή εντολών;

Σε λειτουργικό σύστημα MS-Windows τρέχουμε το πρόγραμμα `cmd`.
Δυστυχώς έχει τα χάλια του. Εναλλακτικά μπορούμε να χρησιμοποιήσουμε
το [ConEmu](https://conemu.github.io). 

Αν εγκαταστήσετε το [Git for
Windows](https://git-scm.com/download/win), τότε θα έχετε στη διάθεσή
σας το Git Shell, το οποίο σας δίνει γραμμή εντολών
[Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) η οποία
περιέχει τα βασικά εργαλεία του Linux και μπορείτε να εργαστείτε πολύ
αποδοτικότερα από τη γραμμή εντολών των MS-Windows.

Σε λειτουργικό σύστημα Mac OS τρέχουμε το πρόγραμμα Terminal, ή
εναλλακτικά το [iTerm2](https://www.iterm2.com/).

Αν χρησιμοποιείτε λειτουργικό σύστημα Linux και έχετε αυτήν την
απορία, κάτι πολύ λάθος κάνετε.

## <a name="whats-the-deal-with-git"></a>Αυτό το Git είναι κάτι για να μας κάνει τη ζωή δύσκολη;

Όχι. Το Git είναι για να μοιράζεστε τον κώδικά σας με άλλους, και για
κρατάτε την ιστορία όλων των αλλαγών που κάνετε στον κώδικά σας.

## <a name="learn-git"></a>Πού μπορώ να μάθω παραπάνω για το Git;

Αν κάνετε μια αναζήτηση για Git tutorials θα βρείτε πάρα πολύ υλικό,
υπάρχουν ολόκληρα βιβλία. 

* Υλικό για τη χρήση του Git μπορείτε να βρείτε στο <https://try.github.io>.

* Δείτε τις σελίδες βοήθειας του GitHub στο <https://help.github.com/>.

## <a name="github-desktop"></a>Εκτός από τη γραμμή εντολών, υπάρχει άλλος τρόπος να δουλέψω με το Git στο GitHub; 

Ναι, το [GitHub Desktop](https://desktop.github.com/).

## <a name="learn-github-desktop"></a>Πού μπορώ να μάθω περισσότερα για το GitHub Desktop;

Στη σχετική [ιστοσελίδα βοήθειας](https://help.github.com/desktop/).

## <a name="git-vs-github"></a>Ποια είναι η διαφορά μεταξύ του Git και του GitHub;

Το Git είναι ένα σύνολο προγραμμάτων με τα οποία μπορούμε να
δουλεύουμε, μαζί με συνεργάτες, στον κώδικά μας. Μπορεί να κρατήσει
την πλήρη ιστορία των αλλαγών μας, να μας προφυλάξει από τυχόν αλλαγές
που κάνουν άλλοι σε αρχεία στα οποία δουλεύουμε ταυτόχρονα εμείς,
κ.λπ. Αυτό όμως δεν σημαίνει ότι δεν είναι χρήσιμο και για ατομική
χρήση: αποτελεί έναν σίγουρο τρόπο φύλαξης αντιγράφων ασφαλείας της
δουλειάς μας, μας δίνει τη δυνατότητα να γυρίσουμε πίσω στο χρόνο,
κ.ά. Αυτή τη στιγμή το συντριπτικά μεγαλύτερο μέρος του λογισμικού
στον κόσμο αποθηκεύεται χρησιμοποιώντας το Git.

Το Git αποθηκεύει τον κωδικά μας σε *αποθετήρια* (repositories). Το
GitHub είναι μία εταιρεία η οποία παρέχει τέτοια αποθετήρια. Τα
παρέχει δωρεάν όταν είναι δημόσια, επί πληρωμή όταν είναι ιδιωτικά,
εκτός από εξαιρέσεις υπό προϋποθέσεις.

Ενώ στα αποθετήρια βάζουμε κώδικα, δεν σημαίνει ότι δεν μπορούμε να
βάλουμε και άλλο υλικό. Ό,τι υλικό έχει βάση το κείμενο μπορεί
κάλλιστα να αποθηκευθεί σε ένα αποθετήριο, ώστε να έχουμε την πλήρη
ιστορία του, να μπορούμε να δούμε την εξέλιξή του, και αν θέλουμε να
το μοιραστούμε με άλλους. Το παρόν κείμενο είναι αποθηκευμένο σε
αποθετήριο. Σε αποθετήριο γράφτηκαν όλες οι σημειώσεις και οι
διαφάνειες του μαθήματος. Σε αποθετήρια επίσης δουλεύουν ομάδες οι
οποίες από κοινού γράφουν συλλογικά κείμενα.

## <a name="commit-early-commit-often"></a>Κάθε πότε πρέπει να αποθηκεύω κάτι στο GitHub;

Κάθε φορά που τελειώνετε κάτι που έχει νόημα να το αποθηκεύσετε. Αν
δουλέυετε κάθε μέρα, και κάθε μέρα φτιάχνετε από κάτι, τότε κάθε μέρα
θα το βάζετε στο αποθετήριο. Αν φτιάχνετε πολλά πράγματα στη διάρκεια
της ημέρας, θα τα συγχρονίζετε στο αποθετήριο κάθε φορά που
ολοκληρώνετε κάτι από αυτά. Όπως λέμε, *commit early, commit often*.
Δείτε πόσες φορές έχει συγχρονιστεί αυτή η σελίδα που έχετε μπροστά
σας στο GitHub.

Μην αποπειραθείτε να βάλετε την εργασία σας στο αποθετήριο άπαξ, όταν
την τελειώσετε, ειδικά αν αυτό προβλέπετε να συμβεί κοντά στο τέλος
της προθεσμίας υποβολής. Θα ταλαιπωρηθείτε, θα στενοχωρηθείτε, και θα
έχετε χάσει όλο το νόημα του Git.

## <a name="repository-private-public"></a>Το αποθετήριό μου είναι ιδιωτικό ή δημόσιο;

Το αποθετήριο στο οποίο θα δουλέψετε είναι ιδιωτικό και σε αυτό έχουν
πρόσβαση μόνο εσείς και ο διδάσκοντας.

## <a name="diffing-linux-tools"></a>Πώς μπορώ αν ελέγξω ότι το πρόγραμμά μου έχει την ίδια έξοδο με τις λύσεις που δίνετε;

Οι εκφωνήσεις των εργασιών περιέχουν παραδείγματα και υποδείγματα
λύσεων. Αν θέλετε να ελέγξετε ότι η λύση σας είναι η ίδια με το
υπόδειγμα, θα πρέπει να την αποθηκεύσετε σε ένα αρχείο και να
συγκρίνετε το αρχείο αυτό με το αρχείο του υποδείγματος. Για να μην το
κάνετε αυτό με το χέρι και με το μάτι, μπορείτε να χρησιμοποιήσετε
έτοιμα εργαλεία και λειτουργίες για το σκοπό αυτό.

1. Υποθέτουμε ότι στο υπολογιστή σας μπορείτε να χρησιμοποιήσετε το
   κέλυφος και τα εργαλεία του λειτουργικού συστήματος Linux. Αν ο
   υπολογιστής σας είναι Apple, αυτό ήδη ισχύει. Αν ο υπολογιστής σας
   είναι MS-Windows, μπορείτε να εγκαταστήσετε το [Git for
   Windows](https://git-scm.com/download/win), βλ. και
   [παραπάνω](#command-line-launch). Εναλλακτικά, μπορείτε να
   εγκαταστήσετε στον υπολογιστή σας το Windows Subsystem for Linux,
   βλ. οδηγίες
   [εδώ](https://docs.microsoft.com/en-us/windows/wsl/about).
   
2. Αν το πρόγραμμά σας ονομάζεται `my_program.py`, το τρέχετε ως εξής
   μέσα από ένα Bash shell (π.χ. το Git Bash, θα πρέπει να έχετε
   εξασφαλίσει ότι η Python είναι στο μονοπάτι, PATH, του συστήματος):

   ```bash
   python my_program.py > my_program_results
   ```
 
   Στο παραπάνω, `my_program_results` (ή όποιο άλλο όνομα θέλετε) είναι το
   όνομα του αρχείου στο οποίο θα αποθηκευτούν τα αποτελέσματα της
   εκτέλεσης του προγράμματός σας αντί να εμφανιστούν στην οθόνη.
   
3. Αν το υπόδειγμα λύσης είναι το αρχείο `solution_example`, τότε για
   να ελέγξετε τη δική σας λύση ως προς αυτή, δίνετε:
   
   ```bash
   diff my_program_results solution_example
   ```
   
Αν το `diff` δεν εμφανίσει τίποτε στην οθόνη, τότε όλα είναι καλά, τα
αρχεία ταυτίζονται. Διαφορετικά, θα σας εμφανίζει όλες τις γραμμές που
διαφέρουν. 

Σε περίπτωση που συνειδητοποιήσετε ότι όλες οι γραμμές διαφέρουν, αλλά
εσάς με το μάτι σας φαίνονται ίδιες, ο λόγος είναι ότι διαφορετικά
λειτουργικά συστήματα μπορεί να χρησιμοποιούν διαφορετικό χαρακτήρα
για το τέλος της γραμμής. Έτσι, τα MS-Windows χρησιμοποιούν το ζευγάρι
χαρακτήρων `\r\n` (carriage return, line feed) ενώ το Linux και το Mac
OS χρησιμοποιούν τον χαρακτήρα `\n` (line feed).

Για να μη δώσει το `diff` σημασία σε αυτή τη διαφορά, όπως και σε
όποια άλλη διαφορά οφείλεται σε χαρακτήρες κενών, δίνετε:

```bash
diff my_program_results solution_example
```

## <a name="command-line-linux"></a>Πού μπορώ να μάθω περισσότερα για τη γραμμή εντολών και το λειτουργικό σύστημα Linux;

Υπάρχουν πολλές πηγές στο διαδίκτυο, όπως η
[LinuxCommand.org](http://linuxcommand.org/)· σε κάθε περίπτωση, με
μια αναζήτηση στο διαδίκτυο μπορείτε να βρείτε το υλικό που σας ταιριάζει.

## <a name="code-photo"></a>Δεν μπορώ να βγάλω άκρη, να σας στείλω ένα μήνυμα με φωτογραφία του προβλήματος;

Ο χρόνος μου είναι πολύ περιορισμένος και ο καλύτερος τρόπος να με
ρωτήσετε απορίες είναι είτε στις ώρες γραφείου είτε στο φροντιστήριο.
Άλλες απορίες μέσω ηλεκτρονικού ταχυδρομείου δεν είναι βέβαιο ότι
μπορώ να τις απαντήσω.

Σε κάθε περίπτωση, *μην στέλνετε μηνύματα με φωτογραφίες του κώδικα
και του προβλήματος*. Ο μόνος τρόπος να πάρετε ίσως απάντηση είναι να
στείλετε σύνδεσμο στον κώδικα που έχετε ανεβάσει στο GitHub, και
ακριβή περιγραφή του προβλήματος. Το μήνυμά σας θα πρέπει να περιέχει
μόνο κείμενο και υπερσυνδέσμους. Ανάμεσα στις άλλες ευκολίες που
παρέχει το GitHub είναι και η δυνατότητα να στείλετε συνδέσμους σε
κομμάτια από τον κώδικά σας, βλ. τη [σχετική απάντηση στο
Stack Overflow](https://stackoverflow.com/questions/23821235/how-to-link-to-specific-line-number-on-github).

## <a name="code-mail"></a>Δεν μπορώ να βγάλω άκρη, να σας στείλω ένα μήνυμα με τον κώδικά μου;

Η αποστολή μηνύματος που περιέχει τον κώδικα, είτε στο σώμα του, είτε
ως συνημμένο, είναι ελαφρώς καλύτερη από την αποστολή φωτογραφίας (βλ.
[παραπάνω](#code-photo)). Πλην όμως δεν επιτρέπει την εύκολο
ταυτοποίηση του προβλήματος. Το πρόβλημα θα πρέπει να είναι
αναπαράξιμο· αυτό σημαίνει ότι θα πρέπει κάποιος να μπορεί να
ακολουθήσει τα βήματά σας και να του εμφανιστεί η ίδια συμπεριφορά.
Για να γίνει αυτό, θα πρέπει να συμπεριλάβετε όλον τον σχετικό κώδικα
στο μήνυμά σας, και όλα τα σχετικά αρχεία που τυχόν χρησιμοποιεί ο
κώδικάς σας, τα οποία ο παραλήπτης του μηνύματος θα πρέπει να τα σώσει
για να τα εξετάσει. Αυτό μπορεί να είναι μεγάλος μπελάς, εκτός από
άκομψο. Μεγιστοποιείτε την πιθανότητα να πάρετε απάντηση αν στέλνετε
συνδέσμους στο GitHub.


## <a name="web-solution-search"></a>Μπορώ να ψάξω στο Google, Stack Overflow, κ.λπ. για απορίες;

Στις σημειώσεις του μαθήματος και του φροντιστηρίου υπάρχει ό,τι
χρειάζεστε για να ολοκληρώσετε τις εργασίες σας, αλλά βεβαίως δεν
περιέχουν όλη τη γνώση του κόσμου, ούτε τη λεπτομέρεια που μπορεί να
χρειάζεται ο καθένας. Μπορείτε να χρησιμοποιείτε πληροφορίες από το
διαδίκτυο στις παρακάτω περιπτώσεις:

* Θέματα της γλώσσας Python. Για παράδειγμα, αν δεν θυμάστε:
  * πώς μπορείτε να περιδιαβείτε σε όλα τα στοιχεία ενός
    λεξικού
  * πώς να δημιουργήσετε ένα λεξικό μέσω comprehension
  * πώς κάνουμε ένωση συνόλων
  * πώς αντιγράφουμε μια λίστα ή μια άλλη δομή δεδομένων
  * κ.λπ.
  
  Με άλλα λόγια, μπορείτε να χρησιμοποιήσετε ό,τι θέλετε και
  σχετίζεται με τη γλώσσα Python *αυτή καθ' αυτή*.
  
* Θέματα χρήσης εργαλείων, όπως editors, Git, κ.λπ.

* Πληροφορίες για βιβλιοθήκες που έχουμε παρουσιάσει στο μάθημα.

* Δεν μπορείτε να χρησιμοποιήσετε πληροφορίες από το διαδίκτυο για
  οτιδήποτε σχετίζεται με τη λύση του προβλήματος της εργασίας,
  υλοποίηση μέρους της, ή του συνόλου της, για βιβλιοθήκες που
  πιστεύετε ότι σας λύνουν το πρόβλημα.*

## <a name="plagiarism"></a>Είναι αλήθεια ότι ελέγχετε όλες τις εργασίες για αντιγραφές;

Ναι.

## <a name="have-i-got-a-problem"></a>Κοντεύουν ξημερώματα και έχω κολλήσει σε πέντε γραμμές που δεν ξέρω τι λάθος κάνω. Έχω πρόβλημα; 

Όχι. Είναι φυσιολογικό. Όλοι το έχουμε περάσει.

## <a name="dont-know-what-to-do"></a>Κοντεύουν ξημερώματα και έχω κολλήσει σε πέντε γραμμές που δεν ξέρω τι λάθος κάνω. Τι μου προτείνετε;

Κάντε κάτι για να καθαρίσει το μυαλό σας, όπως:

1. Ντους / μπάνιο.
2. Περίπατος.
3. Μουσική και βιβλίο.
4. Ύπνος, ξημερώνει καινούργια μέρα.
