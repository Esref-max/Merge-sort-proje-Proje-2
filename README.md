# Merge-sort-proje-Proje-2
Kodluyoruz Eğitimi kapsamında Merge sort proje Proje 2 Ödevi
# Merge Sort Aşamaları
  ##   1. Diziyi bölme aşaması:
    ###   İlk adımda dizi iki alt diziye bölünür:
    [16, 21, 11] ve [8, 12, 22]
  ##   2. Alt dizileri bölme:
    ### İlk alt dizi [16, 21, 11] tekrar ikiye bölünür:
    [16] ve [21, 11]
    ### [21, 11] dizisi de tekrar ikiye bölünür:
    [21] ve [11]
    ### İkinci alt dizi [8, 12, 22] tekrar ikiye bölünür:
    [8] ve [12, 22]
    ### [12, 22] dizisi de tekrar ikiye bölünür:
    [12] ve [22]
  ##   3. Alt dizileri birleştirme (ve sıralama) aşaması:
    [21] ve [11] birleştirilir ve sıralanır:
    ### [11, 21]
    [16] ve [11, 21] birleştirilir ve sıralanır:
    ### [11, 16, 21]
    [12] ve [22] birleştirilir ve sıralanır:
    ### [8, 12, 22]
    Son olarak, [11, 16, 21] ve [8, 12, 22] birleştirilir ve sıralanır:
    ### [8, 11, 12, 16, 21, 22]

# Big-O Gösterimi
  ## Merge sort'un zaman karmaşıklığı:
    ### En iyi durum    :𝑂(𝑛log𝑛)
    ### Ortalama durum  :𝑂(𝑛log𝑛) 
    ### En kötü durum   :𝑂(𝑛log𝑛)
 Merge sort'un uzay karmaşıklığı ise 𝑂(𝑛)
O(n)'dir çünkü ek bir dizi kullanılarak elemanlar birleştirilir.   
