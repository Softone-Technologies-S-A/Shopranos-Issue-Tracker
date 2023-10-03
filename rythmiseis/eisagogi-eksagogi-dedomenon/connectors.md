# Connectors

<mark style="color:yellow;">**ΔΙΑΣΥΝΔΕΣΗ ERP-SHOPRANOS**</mark>

1. **Εμφάνιση  του Web service Shopranos στο ERP.**

Για τη διασύνδεση του Shopranos χρειάζεται να υπάρχει στο ERP το web service με id 955 **(Μενού στις Παραμετροποιήσεις > WEB and Mobile > Υπηρεσίες Web) και** βεβαιώνεστε πως υπάρχει στη λίστα (βλ. Εικόνα 1).

<figure><img src="../../.gitbook/assets/web service.png" alt=""><figcaption><p>Εικόνα 1</p></figcaption></figure>

Εάν δεν εμφανίζεται, θα πρέπει από το εικονίδιο του χρήστη στο top bar του ERP να ανοίξετε την επιλογή: **Άδειες Web and Mobile** και να προχωρήσετε σε **Ανανέωση** ούτως ώστε να εμφανιστεί το web service 955. Σε περίπτωση που πάλι δεν είναι ορατό, θα χρειαστεί update η έκδοση του ERP (βλ. Εικόνα 2).

<figure><img src="../../.gitbook/assets/web_acount.png" alt=""><figcaption><p>Εικόνα 2</p></figcaption></figure>



2. **Δημιουργία Web account**

Από το Μενού **Παραμετροποιήσεις > WEB and Mobile > Λογαριασμοί Web** προβαίνετε σε δημιουργία νέου λογαριασμού, δηλώνοντας Υπηρεσία χρήστη, το service 955 του Shopranos, Username, Password και Email (βλ. Εικόνα 3)

<figure><img src="../../.gitbook/assets/web_acount (1).png" alt=""><figcaption><p>Εικόνα 3</p></figcaption></figure>



3. **Δημιουργία του Connector στο Shopranos**

{% hint style="success" %}
Μεταβείτε: **Ρυθμίσεις > Εισαγωγή – Εξαγωγή Δεδομένων > Connectors**, για να δημιουργήσετε έναν Connector με βάση τα παραπάνω στοιχεία από το ERP (βλ. Εικόνα 4).
{% endhint %}

<figure><img src="../../.gitbook/assets/ScreenHunter 1007.png" alt=""><figcaption><p>Εικόνα 4</p></figcaption></figure>

Δηλώνετε το όνομα πχ. Softone, επιλέγετε την πηγή και στο επόμενο βήμα δηλώνετε τα στοιχεία (βλ. Εικόνα 5):

* Σειριακός αριθμός (SN του ERP)
* App Id (το 955)
* Όνομα χρήστη και Κωδικός (το όνομα και ο κωδικός του web account που δημιουργήσατε στο ERP).

{% hint style="info" %}
Στη συνέχεια, επιλέγετε <Υποβολή> και <Αποθήκευση>.
{% endhint %}

<figure><img src="../../.gitbook/assets/ScreenHunter 1009.png" alt=""><figcaption><p>Εικόνα 5</p></figcaption></figure>
