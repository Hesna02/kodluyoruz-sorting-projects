# Sorting Projesi
## Insertion Sort Projesi
### Proje 1 
## Sorular

[22,27,16,2,18,6] -> Insertion Sort

*Yukarıda verilen dizinin sort türüne aşamalarını yazınız.*

*Big-0 gösterimini yazınız.*
* Time Complexity: 
* Average case:
Aradığımız sayının sonda olması,
* Wort case:
Aradığınız saynın sonda olması
* Best case: Aradığımız sayının dizinin en başında olması.

*Dizi sıralandıktan sonra 18 sayısı hangi case kapsımına girer? Yazınız.*


*[7,3,5,8,2,9,4,15,6]

## Cevaplar

## Insertion Sort -1

[22,27,16,2,18,6]

[22|27,16,2,18,6]

[22,27|16,2,18,6]

[16,22,27|2,18,6]

[2,16,22,27|18,6]

[2,16,18,22,27|6]

[2,6,16,18,22,27]

## Big0 Notation

Worst Case= O(n²)

Average Case= O(n²)

Best Case= O(n²)

>**18 Sayısı Average Case kapsamına girer çünkü orta kısımda yer alır.**

### Insertion Sort -2

[7,3,5,8,2,9,4,15,6]

- [7|3,5,8,2,9,4,15,6] 

- [3,7|5,8,2,9,4,15,6]

- [3,5,7|8,2,9,4,15,6]

- [2,3,5,7,8|9,4,15,6]

- [2,3,4,5,7,8,9|15,6]