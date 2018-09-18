# JavaScript-Verk3


1. Útskýrðu Prototype kerfið í JavaScript. Hver er munurinn á því t.d. og ObjectOriented
   forritun (OOP) í öðrum málum eins og Python? (1%)
   * *Prototype i JS gerir manni kleift að gera fleira og gera hluti á auðvedari hátt.*
   * *Munurinn á Prototype og OOP er að í öðrum málum en JS þá þarf maður alltaf að nota base class til þess að gera inheritance en í JS getur maður notað Inheritance með prototype á hvað sem er einsog t.d. Object.*

2. Útskýrðu eins vel og þú getur hvað gerist í kóðanum(1%)
 * a. Þegar prototype er sleppt
 
 * b. Hvað gerir prototype í 
```javascript
Book.prototype.getIsbn
function Book(isbn) {
 this.isbn = isbn;
}
// Book.prototype.getIsbn
Book.getIsbn = function () {
 return "Isbn is " + this.isbn;
};
```
3. Classical Model (function constructor and prototype) (2%)
   * a. Búðu til þrjár geimflauga objecta með function smið sem hafa
      mismunandi heiti. Geimflaugarnar eiga einnig að hafa eigindin speed og
      life með upphafsgildinu 10.
      Spaceship-name generator:
      http://www.fantasynamegenerators.com/spaceshipnames.php#.WnQsPqhl-M8
   * b. Gefðu geimflaugunum mismunandi speed gildi.
   * c. Notaðu Prototype til að bæta við nýrri method fly sem hækkar gildið
      speed um 1. Þetta fá allar flaugarnar.
   * d. Búðu til undirhóp flauga (2 flaugar) af einni geimflauginni sem þú bjóst til
      að ofan. Gefðu þessum flaugum einhver eigindi og gildi. Þessar flaugar
      eiga að auki að hafa aðferðina setLife() sem hækkar life um 1.

4. Gerðu það sama og í lið 3 en með notkun class (ES2015). Notaðu constructor,
   get, set, static, extends, super, mix-ins eftir þörfum. (2%)
