+++
title = 'Soal Integral Tentu'
date = 2024-03-10T10:19:18+07:00
draft = true
math = true
+++

1. Tunjukkan bahwa nilai dari $\int_{0}^{1}\sqrt{x+8} \ dx$ terletak antara $2\sqrt{2}$ dan $3$

2. Buktikan Bahwa  $|\int_{a}^{b}f(x)\ dx| \leq \int_{a}^{b}|f(x)|\ dx$

<aside>
💡 Solution

</aside>

- Nomor 1
    
    Dibuktikan bahwa $2\sqrt{2}\leq\int_{0}^{1}\sqrt{x+8} \ dx\leq3$
    
    Kita disini menggunakan Aturan Pertidaksamaan maks-min yakni,
    
    $min\ f\cdot(b-a)\leq\int_{a}^{b}f(x)\ dx\leq maks\ f \cdot (b-a)$
    
    Dengan demikian kita perlu mencari nilai minimum dan nilai maksimum dari fungsi $f(x)$ pada interval $[0,1]$
    
    - Nilai minimum dapat kita cari dengan mensubstitusikan $x=0$ kedalam fungsi $\sqrt{x+8}$, sehingga $\sqrt{0+8}=\sqrt{8}=2\sqrt{2}$
    - Nilai minimum dapat kita cari dengan mensubstitusikan 1 kedalam fungsi $\sqrt{x+8}$, sehingga $\sqrt{1+8}=\sqrt{9}=3$
    
    Dengan telah diketahuinya nilai minimum dan nilai maksimum dari fungsi $f(x)$ serta intervalnya $[0,1]$, sehingga kita dapat langsung mensubstitusikannya kedalam aturan pertidaksamaan maks-min
    
    $2\sqrt{2}\cdot(1-0)\leq\int_{0}^{1}\sqrt{x+8}\ dx\leq 3\cdot (1-0)$
    
    $\Leftrightarrow 2\sqrt{2}\leq\int_{0}^{1}\sqrt{x+8}\ dx\leq 3$  (Terbukti)
    
    Terbukti, bahwa nilai dari $\int_{0}^{1}\sqrt{x+8} \ dx$ terletak antara $2\sqrt{2}$ dan $3$
    
- Nomor 2
    
    Dibuktikan bahwa $|\int_{a}^{b}f(x)\ dx|\leq \int_{a}^{b}|f(x)|\ dx$
    
    Sebelumnya harus kita ketahui bahwa : $\int_{a}^{b}f(x)\ dx =\lim_{n\rightarrow\infty}\Sigma_{k=1}^{n}f(c_k)\cdot(\frac{b-a}{n})$
    
    Sehingga, 
    
    $|\lim_{n\rightarrow\infty}\Sigma_{k=1}^{n}f(c_k)\cdot(\frac{b-a}{n})|\ \leq\  \lim_{n\rightarrow\infty}\Sigma_{k=1}^{n}\ |f(c_k)| \cdot(\frac{b-a}{n})$
    
    Kita abaikan terlebih dahulu limit pada kedua ruas
    
    $|\Sigma_{k=1}^{n}f(c_k)\cdot(\frac{b-a}{n})|\ \leq\  \Sigma_{k=1}^{n}\ |f(c_k)| \cdot(\frac{b-a}{n})$
    
    Kita jabarkan penjumlahan sebagai berikut
    
    $|f(c_1)+f(c_2)+f(c_3)+...+f(c_n)|\cdot|\frac{b-a}{n}|\leq(|f(c_1)|+|f(c_2)|+|f(c_3)|+...+|f(c_n)|)\cdot(\frac{b-a}{n})$
    
    Kita misalkan bahwa hasil kali luas setiap sub-interval dibawah grafik merupakan peubah H
    
    $|H_1+H_2+H_3+...+H_n|\leq|H_1|+|H_2|+|H_3|+...+|H_n|$ (Terbukti)
    
    Menurut ketaksamaan segitiga, hal ini terbukti bahwa $|\int_{a}^{b}f(x)\ dx|\leq \int_{a}^{b}|f(x)|\ dx$