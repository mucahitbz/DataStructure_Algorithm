# Proje 3
### `[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]`

---
### 1. Binary-Search-Tree aşamalarını yazınız.
![binarysearchtree](file:///C:/Users/Mucahit/Desktop/VeriYapilariveAlgoritmalar/bstree.png)
## Detaylar
1.Öncelikle 7 değerini ekliyoruz. Daha önceden eklenmiş bir değer olmadığı için 7 değeri ağacımızın root değeri olarak belirlenmiş olur.

2.Sonrasında 5 değeri geliyor. 5, 7'den küçük olduğu için root’un solunda yer alır.

3.Daha sonrasında 1 değeri geliyor. 1, 7'den küçük olduğu için root’un solunda yer alır. Ancak 7'in solunda daha önceden eklediğimiz 5 değerli node bulunmaktadır. O zaman bu 1 değerinde olan node’u bu seferde 5 değeri ile karşılaştırırız. Böylelikle 1 değerine sahip node’un 5 değerine sahip node’un hangi tarafına child node olarak ekleneceği belirleriz. Bunun sonucunda soluna eklenir.

4.Dizideki diğer sayılar da aynı yöntem ile binary tree'ye eklenir.

