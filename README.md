# 03b_Inheritance_CodeLab_3

## Teil I

Erstellen Sie eine Klasse **App** mit einer Methode **main()**
Erstellen Sie eine Klasse **Mitarbeiter** mit folgenden Attributen

- a) Name, Vorname, Geburtsjahr
- b) Mitarbeiternummer, Abteilung, Job

Implementieren Sie die Attribute unter a) als **private** und erstellen Sie geeignete
Getter/Setter-Methoden.

Implementieren Sie zwei öffentliche Methoden **hasLunch()** & **startsWork()** die für alle
Instanzen gelten sollen.

Erstellen Sie jeweils eine spezifische, private Methode für einen Mitarbeiter in

1. Buchhaltung (Accounting) zB. **callsCustomer()** etc.
2. Produktion (Manufacturing)
3. Werbung (Advertising)

und aktivieren Sie dieses Verhalten über eine geeignete Struktur (zB. switch() )
und eine Parameterübergabe in einer öffentlichen Methode **doYourWork(String flag)**

Legen Sie in der Klasse **App** jeweils **3 verschiedene Mitarbeiter** an.

## Teil II

Bauen Sie die Struktur wie folgt um:

Implementieren Sie eine Superklasse Mitarbeiter (MA etc.)sowie drei Subklassen , in die Sie
das spezifische Verhalten (Advertising/Accounting/Production) auslagern.

Die Attribute in der Superklasse haben die Eigenschaft (Access modification) private.

Erstellen Sie Sie von der entstandenen Struktur ein entsprechendes Klassendiagramm und
speichern Sie dieses ab.

## Teil III

Ergänzen Sie die Struktur ggf. um eine weiter Superklasse **Person**
