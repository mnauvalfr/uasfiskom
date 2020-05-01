 uasfiskom
Ujian Akhir Semester FI3201 Fisika Komputasi
Catatan: jawaban dituliskan dalam format .tex, lalu dikonversi ke format MD dengan https://cloudconvert.com/tex-to-md. Di GitHub akan diberikan 2 file, versi konversi markdown dan versi .tex (dalam format txt notepad).

Soal No.1
=========

![image](UASFiskom0101.png)

1.  Didapat persamaan dalam setiap arah gerak bandul sebagai berikut, untuk gerak sumbu \(x\):

    \[\Sigma F_x = m \ddot{x}\]

    Pertama-tama, dengan melihat gambar dapat ditemukan hubungan

    \[T \cos \theta -F_{visko_x}= m \ddot{x}\]

    Jika dianalisa gaya searah \(\hat{r}\),

    \[T -\omega sin  \theta= \dfrac{mv^2}{l}\]

    sehingga

    \[T =\omega sin  \theta + \dfrac{mv^2}{l}\]

    dan

    \[F_{visko_x}= 3\eta\pi D\ddot{x}.\]

    Jika disubstitusikan,

    \[-mg \cos\theta \sin\theta+\dfrac{mv^2}{l}cos\theta - 3\pi\eta D \dot{x} -  =m \ddot{x}\]

    Substitusikan persamaan \(\cos \theta =\dfrac{x}{l} \) , \(\sin \theta =\dfrac{y}{l} \), dan \( w =-mg\), **sehingga akan didapat**

    \[\ddot{x} +\dfrac{gxy}{l^2} + \dfrac{3\pi\eta D \dot{x}}{m} -\dfrac{v^2}{l^2}x =0\]

    Selanjutnya, akan diturunkan persamaan gerak untuk sumbu y.

    \[\Sigma F_y = m \ddot{y}\]

    Dengan melihat gambar, dapat dilihat gaya yang bekerja di sumbu y adalah

    \[T \sin\theta -mg - F_{visko_y} =m\ddot{y}\]

    Substitusikan persamaan \(   F_{visko_y}= 3\eta\pi D\ddot{y} \) dan \(\sin \theta =\dfrac{y}{l} \), **sehingga akan didapat**

    \[\ddot{y} + \dfrac{3\pi\eta D}{m} \dot{y} + \dfrac {({\dot{x^2}+\dot{y^2}})y}{l^2} -\dfrac{gy^2}{l^2} = -g\]

2.  Untuk persamaan gaya di sumbu x,

    \[\dfrac{g}{l^2}xy - \dfrac{3\pi\eta D}{m} \dot{x} - \dfrac{(\dot{x^2}+\dot{y^2})}{l^2}x =\ddot{x}\]

    terdapat suku \(\ddot{x}\) sebagai **komponen percepatan**,\( \dfrac{3\pi\eta D}{m} \dot{x} \) sebagai **komponen gaya gesek menggunakan hukum Stokes**, \(-\dfrac{(\dot{x^2}+\dot{y^2})}{l^2}x\) sebagai **komponen gaya sentripetal untuk tegangan tali**, dan \(\dfrac{g}{l^2}xy\) adalah **komponen gaya gravitasi di tegangan tali**.

    Untuk persamaan gaya di sumbu y,

    \[\ddot{y} + \dfrac{3\pi\eta D}{m} \dot{y} + \dfrac {({\dot{x^2}+\dot{y^2}})y}{l^2} -\dfrac{gy^2}{l^2} = -g\]

    terdapat suku \(\ddot{y}\) sebagai **komponen percepatan**,\( \dfrac{3\pi\eta D}{m} \dot{y} \) sebagai **komponen gaya gesek menggunakan hukum Stokes**, \(-\dfrac{(\dot{x^2}+\dot{y^2})}{l^2}y\) sebagai **komponen gaya sentripetal untuk tegangan tali**, dan \(\dfrac{gy^2}{l^2}\) adalah **komponen gaya gravitasi di tegangan tali**. Selain itu, terdapat juga **komponen \(-g\) sebagai komponen gravitasi (vertikal sumbu y)**.

3.  Untuk benda jatuh bebas tanpa gesekan udara, maka persamaan (2) (gaya di sumbu x) ** berubah menjadi **

    \[\ddot{x} = 0\]

    Persamaan (3) (gaya di sumbu y) **berubah menjadi **
    \[\ddot{y} = -g\]
    Saat gaya jatuh bebas tanpa ada gesekan, komponen tegangan dan viskositas bisa diabaikan, sehingga \(\eta =0\) dan \( l \approx 0\).
4.  Untuk simpangan kecil, maka \(\dfrac{y}{l} \approx 1\) dan \(\dfrac{x}{l} \approx \theta\). Tanpa gaya gesek, maka \(\eta =0\).
    ,
Soal No.2
=========
1.  Pertama diketahui posisi bandul sebagai berikut:
    ![image](UASFiskom0101.png)
    T adalah gaya tegang tali, Fv adalah gaya viskositas akibat udara, dan W adalah berat.
    Persamaan gerak pada sumbu \(\hat{\theta}\) dapat diturunkan dengan mengingat \(\alpha = \dfrac{d^2\theta}{dt^2} =\dfrac{M}{I}\), dimana \(\alpha\) adalah momentum sudut, M adalah momen, dan I adalah inersia.
    Torsi ditentukan oleh proyeksi gaya ke arah tangensial:
    \[M = -mgL\sin \theta\]
    Momen inersia pendulum adalah momen inersia lingkaran:
    \[I = -mL^2\sin \theta\]
    Sehingga, persamaan gerak di sumbu \(\hat{\theta}\) adalah, dengan mencoret suku-suku yang sama
    \[\dfrac{d^2\theta}{dt^2} = \dfrac {M}{I} =\dfrac{g \sin\theta}{L}\]
    \[\dfrac{d^2\theta}{dt^2} +  \dfrac{g  \sin\theta}{L}  =0\]
    **Untuk persamaan gerak pada sumbu \( \hat{r}\), berlaku**

    \[w \cos \theta +T = \dfrac{mv^2}{r} + m\dot{\theta^2}R\]

    \[-mg \cos \theta +T = m \dot{\theta^2}l\]

    \[\dot{\theta^2}+\dfrac{g}{l} \cos \theta =\dfrac{T}{ml}\]

2.  \[\dfrac{d^2\theta}{dt^2} - \dfrac{g\theta}{l} =0\]

    Persamaan diferensial ini adalah persamaan diferensial karakteristik, sehingga dengan memisalkan \(\lambda_{12} = \pm \dfrac{g}{l}i\), sehingga:

    \[\theta = C\exp{\lambda_1t}+D\exp{\lambda_2t}\]

    \[\theta = C (\cos \dfrac{g}{l}t + i \sin \dfrac{g}{l}t) +D(\cos \dfrac{g}{l}t - i \sin \dfrac{g}{l}t)\]

    \[\theta = (C+D) \cos \dfrac{g}{l}t +  i (C-D) \sin \dfrac{g}{l}t\]

    \[\theta = A \cos \dfrac{g}{l}t +   B \sin \dfrac{g}{l}t\]

    Saat t = 0, asumsikan **bandul berada di amplitudo** sehingga sudut maksimum.

    \[\theta_{max} = A \cos 0 + 0 \Rightarrow \theta_{max} = A\]

    Didapat A = amplitudo, B = 0. Sehingga, pada akhirnya akan didapat

    \[\theta = A \cos  \dfrac{g}{l}t, \\ \dot{\theta} =-\dfrac{g}{l} A \sin \dfrac{g}{l}t\]

    Untuk persamaan kedua, dengan mensubstitusikan persamaan sebelumnya,

    \[\dot{\theta^2} + \dfrac{g}{l}cos\theta = \dfrac{T}{lm}\]

    Karena menggunakan pendekatan sudut kecil, maka

    \[T \approx \left((\dfrac{g}{l}A\sin \dfrac{g}{l}t)^2 +\dfrac{g}{l}\cos\theta\right)lm\]

3.  Dengan metode Euler,

    \[\dfrac{df}{dx}= \dfrac{f(x+L)-f(x)}{h} \Rightarrow \dfrac{f^{i+1}-f^i}{\Delta x}\]

    Persamaan \(\ddot{\theta}\) dan \(\dot{\theta}\) dapat dirubah menjadi

    \[\dot{\theta}=\dfrac{d\theta}{dt}=  \dfrac{\theta^{i+1}-\theta^i}{\Delta t} \Rightarrow \theta^{i+1} = \theta^i\Delta t+ \theta^i\]

    dan

    \[\ddot{\theta}=\dfrac{g}{l} \sin \theta \Rightarrow  \dfrac{d\theta^i}{dt} =  \dfrac{g}{l} \sin \theta\]

    \[\dfrac{\theta^{i+1}-\theta^i}{\Delta t} = \dfrac{g}{l} \sin \theta^{i}\]

    \[\theta^{i+1}=\dfrac{g}{l} \sin \theta^{i}\Delta t+\theta^i\]

    Hasil dari perhitungan menggunakan metode numerik digrafikkan di

        https://plotly.com/~Avestory/1/#/


4.  Untuk menyelesaikan secara numerik, dibuat kode di C++ sebagai berikut:

                    #include <iostream>
                    #include <cmath>
                    #include <fstream>

                    using namespace std;

                    int main(){
                    /* variabel yang digunakan */
                    float g,l,h,m,tt;
                    int i,n;
                    
                    g = 9.82;
                    
                    /*besar panjang tali*/
                    l=1;
                    /*besar massa*/
                    m=0.5;
                    /*total waktu analisis*/
                    tt = 10;
                    /*step waktu yang digunakan*/
                    h = 0.1;

                    n = tt/h;
                    float theta[n],thetadot[n],f[n],T[n],t[n];

                    for (i=0;i<n;i++){
                    t[i] = 0;
                    f[i] = 0;
                    T[i] = 0;
                    theta[i] = 0;
                    thetadot[i] = 0;
                    }

                    /* pendefinisian awal */
                    theta[0] = 30*3.14/180;
                    thetadot[0] = 0;
                    
                    /* logika euler dan input data yang didapat ke file theta.txt */
                    ofstream myfile;
                    myfile.open ("theta.txt");
                    for (i=0; i<=n; i++){
                    theta[i+1] = theta[i] + thetadot[i]*h;
                    f[i] = (g/l)*sin(theta[i+1])*-1;
                    thetadot[i+1] = thetadot[i] + f[i]*h;
                    T[i] = l*m*(thetadot[i]*thetadot[i] + g*cos(theta[i])/l);
                    
                    t[i+1] = t[i] + h;
                    
                    myfile <<  t[i]  << "  "  << theta[i] << "  " << thetadot[i] << "  " << T[i] << "\n";
                    
                    cout << "t[" << i << "]: " << t[i] << "\n";
                    cout << "theta[" << i << "]: " << theta[i] << "\n";
                    cout << "thetadot[" << i << "]: " << thetadot[i] << "\n";
                    cout << "T[" << i << "]: " << T[i] << "\n" << "\n";
                    }
                    myfile.close();
                    
                    
                    /* terminasi program */
                    return 0;
                    }
                    
    Kode juga akan disertakan di GitHub.
Soal No.3
=========
Soal No.4
=========
1.      [x, y, c] = getValues(p);
            x = getValues(p)
            // hasilnya 3 digit
            main();
            
            
            // Define main function
            function main() {
            var p = "0010110";
            [xs, ys, cs] = getValues(p);
            console.log("p =",p);
            console.log("x =",xs);
            console.log("y =",ys);
            console.log("c =",cs);
            
            }
            
            
            
            function getValues() {
            var p = arguments[0];
            
            var xs = p.slice(0, 3);
            var ys = p.slice(3, 6);
            var cs = p.slice(6);
            
            return [xs, ys, cs];
            }
            
2.  Fungsi *fitness* yang diminta dibuat sebagai berikut:

            main();

            // Define main function
            function main() {
            var p = "1010110";
            [xs, ys, cs] = getValues(p);
            var hasil = 1/(1+fitness(xs,ys));
            console.log("p =",p);
            console.log("x =",xs);
            console.log("y =",ys);
            console.log("c =",cs);
            console.log("hasil = ",hasil);

            }

            function getValues() {
            var p = arguments[0];

            var xs = p.slice(0, 3);
            var ys = p.slice(3, 6);
            var cs = p.slice(6);

            return [xs, ys, cs];
            }

            function fitness(a, b) {
            return(Math.sqrt(Math.pow((a - 111), 2) + Math.pow((b - 111),2)));
            }


