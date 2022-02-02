# ANN ile belli bir değer aralığındaki bağımlı değişkenlerin kuadratik denklemdeki çıktılarına göre model oluşturma
<img id="equationview" name="equationview" src="https://latex.codecogs.com/svg.latex?ax%5E%7B2%7D%20&amp;plus;%20bx%20&amp;plus;%20c%20%3D%200">

a ∈ [1,4],
b ∈ [-3,-1],
c ∈ [-4,-2],

<img src="https://latex.codecogs.com/svg.latex?\Large&space;x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" title="\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" />

Yukarıdaki değer arlığındaki tam sayılar ile kuadratik denklemin sonuçları hesaplanacak ve 2 katmanlı bir yapay sinir ağında eğitilecek. Eğitim sonunda değer aralıklarında kalan ondalık değerler ile model teste tabi tutulacaktır. <br>
**Pytorch** framework'ü kullanılmıştır.
