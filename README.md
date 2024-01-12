Üdvözlök mindenkit! 👋

Ma egy kicsit mélyebben szeretném megvizsgálni a felügyelt Machine Learning algoritmusok közül a lineáris regressziót. 📊 A Scikit-learn (sklearn) python library kiválóan alkalmas arra, hogy belevessük magunkat az adatelemzés és a gépi tanulás világába.
A lineáris regresszió az egyik alapvető eszköze az adatok közötti összefüggések modellezésének. Az sklearn-ben található, jelen példánkban egyszerű lineáris regresszió segítségével könnyen illeszthetünk egy lineáris modellt adatainkhoz, és becsléseket készíthetünk az ismeretlen értékekre.

Létrehoztam egy python kódot Jupyter Notebookban, ami a lakóhelyem aktuális lakás áraival foglalkozik. Az adatokat a jelenleg aktuális szolnoki lakásárakról éa a lakások területéről én magam gyűjtöttem össze egy csv fájlba, az egyik legnagyobb ingatlanos portál első 30 találata alapján. Független változó: alapterület, függő változó: ár.
Egy rövid áttekintés arról, hogy mit csinál a kód:

Adatbetöltés: a kód beolvassa a szolnoki lakásárak adathalmazát
Adatfeldolgozás: szétbontja az adathalmazt tanulási és teszt adathalmazra
Gépi Tanulási modell: a scikit-learn könyvtár segítségével lineáris regressziós modellt készít
Modell tanítás: a kód betanítja a modellt a tanulási adathalmazon
Chartok nyomtatása: megnézzük a tanulási ‘Training’ és teszt ‘Test’ adathalmaz szórási diagramját
Predikció: a betanított modellt felhasználva predikciót készítünk a 30 - 150 négyzetméter alapterületű lakások árára
Eredmények exportálása: az eredményt egy Excel fájlba mentjük további elemzések és megosztás céljából
