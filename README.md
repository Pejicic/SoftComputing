# SoftComputing
Potrebno je skinuti dataset sa linka na issue-u, te ga smjestiti u unutar foldera SoftComputing u novi folder sa imenom Leaves . Odabrati 5-6 listova od svake vrste te ga prebaciti iz Leaves u novi folder Test, koji se nalazi na istom nivou kao i Leaves. Slike iz ovog foldera će zatim biti korišćene za pokušaj klasifikacije na obučenom svm klasifikatoru.
Zatim je potrebno pokrenuti PreprocessingLeaf da bi se izdvojili i ucitali feature-i u Leaf.csv.
Nakon toga se pokrene TrainLeaf u kom se svm klasifikator obučava nad podacima iz Leaves foldera (koje su u pretprocesingu pretvorene u numericke podatke i upisane u Leaf.csv) , te se bg_sub funkciji proslijedi slika koja želi da se klasifikuje (u Test folderu su smješteni novi podaci nad kojim svm klasifikator nije obučavan).
