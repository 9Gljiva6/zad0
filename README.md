# JMBAG
0036494316

# pitanje 1
Primjecujem da su nastala 2 nova sadrzaja: ClassLibrary1.dll i ClassLibrary.pdb
Nakon sto maknem .dll program se ne zeli izvrsiti, a to se dogodi zato sto program pokusava pronaci referencu na ClassLIbrary1 koji smo izradili, a nemoze ju pronaci jer smo ju izbrisali
Kada bih vam slao aplikaciju, posalo bih vam .exe datoteku main koda i sve .dll datoteke libraryja

# pitanje 2
Konzolna aplikacija koristila je staru verziju libraryja zato sto smo samo izmjenili kod, ali ga nismo compilali stoga izvrsne datoteke ostaju nepromjenjene

# pitanje 3
Ispisalo se Pero: Hello World, no iz nekog razloga to radi jedino kada maknem referencu na ClassLibrary1

# pitanje 4
Stvorio se novi PeroClassLibrary.dll

# pitanje 5
Ako obrisem original .dll program i dalje radi zato sto je build promijenio path do .dll na onaj novi koji je nastao u build/debug folderu

# pitanje 6
Build proces je uspio, a packages direktorij se ponovno stvorio
