# Ujian kelompok 5


## Anggota
Terdapat enam orang anggota pada kelompok 5 ini dengan fraksi kontribusinya pada pengerjaan tiap soal dapat dilihat dalam tabel berikut.

| NIM      | Nama                  | Peran pada soal (dan fraksi kontribusinya)   |
|----------|-----------------------|----------------------------------------------|
|          |                       |                                              |
| 10217010 | Panglima Einstein III | 1 (0.10) 2 (0.00) 3 (0.20) 4 (0.30) 5 (0.16) |
| 10250098 | Teman Maxwell Jr.     | 1 (0.20) 2 (0.00) 3 (0.20) 4 (0.30) 5 (0.17) |
| 10250123 | Densitas Kanonika     | 1 (0.10) 2 (0.00) 3 (0.20) 4 (0.30) 5 (0.16) |
| 10250199 | Dualisma Singulariadi | 1 (0.20) 2 (0.00) 3 (0.00) 4 (0.10) 5 (0.17) |
| 10250201 | Antrodinamika Laten   | 1 (0.20) 2 (0.50) 3 (0.20) 4 (0.00) 5 (0.17) |
| 10250278 | Ergodik Kekal Tunak   | 1 (0.20) 2 (0.50) 3 (0.20) 4 (0.00) 5 (0.17) |
|          |                       |                                              |
|          | Total                 | 1 (1.00) 2 (1.00) 3 (1.00) 4 (1.00) 5 (1.00) |



# Jawaban

## Soal 1 | Sistem bandul dengan sistem koordinat kartesian
![](UASFiskom0101.png)

### a
Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

		\item
		 Didapat persamaan dalam setiap arah gerak bandul sebagai berikut, untuk gerak  sumbu $x$:
		\begin{equation}
		\Sigma F_x = m \ddot{x}
		\end{equation}
		Pertama-tama, dengan melihat gambar dapat ditemukan hubungan
		\begin{equation}
		T \cos \theta -F_{visko_x}= m \ddot{x}
		\end{equation}
		Jika dianalisa gaya searah $\hat{r}$,
		\begin{equation}
		T -\omega sin  \theta= \dfrac{mv^2}{l}
		\end{equation}
		sehingga
		\begin{equation}
		T =\omega sin  \theta + \dfrac{mv^2}{l}
		\end{equation}
		dan
		\begin{equation}
		F_{visko_x}= 3\eta\pi D\ddot{x}.
		\end{equation}
		Jika disubstitusikan,
		\begin{equation}
		-mg \cos\theta \sin\theta+\dfrac{mv^2}{l}cos\theta - 3\pi\eta D \dot{x} -  =m \ddot{x}
		\end{equation}
		Substitusikan persamaan $\cos \theta =\dfrac{x}{l} $ , $\sin \theta =\dfrac{y}{l} $, dan $ w =-mg$, 
		sehingga akan didapat
		\begin{equation}
		\ddot{x} +\dfrac{gxy}{l^2} + \dfrac{3\pi\eta D \dot{x}}{m} -\dfrac{v^2}{l^2}x =0 
		\end{equation} \\
		
		Selanjutnya, akan diturunkan persamaan gerak untuk sumbu y. 
		\begin{equation}
		\Sigma F_y = m \ddot{y}
		\end{equation}
		Dengan melihat gambar, dapat dilihat gaya yang bekerja di sumbu y adalah
		\begin{equation}
		T \sin\theta -mg - F_{visko_y} =m\ddot{y}
		\end{equation}
		Substitusikan persamaan $F_{visko_y}= 3\eta\pi D\ddot{y}$ dan $\sin \theta =\dfrac{y}{l} $, 
		sehingga akan didapat
		\begin{equation}
		\ddot{y} + \dfrac{3\pi\eta D}{m} \dot{y} + \dfrac {({\dot{x^2}+\dot{y^2}})y}{l^2} -\dfrac{gy^2}{l^2} = -g
		\end{equation}

### b 
Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

		Untuk persamaan gaya di sumbu x, 
		\begin{equation}
		\dfrac{g}{l^2}xy - \dfrac{3\pi\eta D}{m} \dot{x} - \dfrac{(\dot{x^2}+\dot{y^2})}{l^2}x =\ddot{x}
		\end{equation} \\
		terdapat suku $\ddot{x}$ sebagai komponen percepatan,,$ \dfrac{3\pi\eta D}{m} \dot{x} $ 
		sebagai komponen gaya gesek menggunakan hukum Stokes, 
		$-\dfrac{(\dot{x^2}+\dot{y^2})}{l^2}x$ sebagai komponen gaya sentripetal untuk tegangan tali, 
		dan $\dfrac{g}{l^2}xy$ adalah komponen gaya gravitasi di tegangan tali.		
		Untuk persamaan gaya di sumbu y, 
		\begin{equation}
		\ddot{y} + \dfrac{3\pi\eta D}{m} \dot{y} + \dfrac {({\dot{x^2}+\dot{y^2}})y}{l^2} -\dfrac{gy^2}{l^2} = -g
		\end{equation}
		terdapat suku $\ddot{y}$ sebagai komponen percepatan,$ \dfrac{3\pi\eta D}{m} \dot{y} $ 
		sebagai komponen gaya gesek menggunakan hukum Stokes, 
		$-\dfrac{(\dot{x^2}+\dot{y^2})}{l^2}y$ sebagai komponen gaya sentripetal untuk tegangan tali, 
		dan $\dfrac{gy^2}{l^2}$ adalah komponen gaya gravitasi di tegangan tali. 
		Selain itu, terdapat juga komponen $-g$ sebagai komponen gravitasi (vertikal sumbu y).

### c
Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

		\item 
		Untuk benda jatuh bebas tanpa gesekan udara,  maka persamaan (2) (gaya di sumbu x)  berubah menjadi }
		\begin{equation}
		\ddot{x} = 0
		\end{equation}
		Persamaan (3) (gaya di sumbu y)  berubah menjadi }
		\begin{equation}
		\ddot{y} = -g
		\end{equation}
		Saat gaya jatuh bebas tanpa ada gesekan, komponen tegangan dan viskositas bisa diabaikan, 
		sehingga $\eta =0$ dan $ l \approx \infty$.
### d
Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

		Untuk simpangan kecil, maka $\dfrac{y}{l} \approx 1$ dan $\dfrac{x}{l} \approx \theta$. 
		Tanpa gaya gesek, maka $\eta =0$.
		Sehingga, didapat 
		\begin{equation}
		\ddot{x} - \dfrac{(\dot{x^2}+\dot{y^2})}{l}\theta + g\theta =0
		\end{equation} \\
		\begin{equation}
		\ddot{y} - \dfrac{(\dot{x^2}+\dot{y^2})}{l}\theta + g =-g
		\end{equation}} \\
## Soal 2 | Bandul dengan sistem koordinat polar
![](UASFiskom0101.png)
### a Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

			Pertama diketahui posisi bandul sebagai berikut:
			T adalah gaya tegang tali, Fv adalah gaya viskositas akibat udara, dan W adalah berat.\\
			Persamaan gerak pada sumbu $\hat{\theta}$ dapat diturunkan 
			dengan mengingat $\alpha = \dfrac{d^2\theta}{dt^2} =\dfrac{M}{I}$, 
			dimana $\alpha$ adalah momentum sudut, M adalah momen, dan I adalah inersia.
			
			Torsi ditentukan oleh proyeksi gaya ke arah tangensial:
			\begin{equation}
			M = -mgL\sin \theta
			\end{equation} 
			Momen inersia pendulum adalah momen inersia lingkaran:
			\begin{equation}
			I = mL^2
			\end{equation} 
			Sehingga, persamaan gerak di sumbu $\hat{\theta}$ adalah, 
			dengan mencoret suku-suku yang sama:
			\begin{equation}
			\dfrac{d^2\theta}{dt^2} = \dfrac {M}{I} =\dfrac{g \sin\theta}{L} 
			\end{equation} 
			\begin{equation}
			\dfrac{d^2\theta}{dt^2} +  \dfrac{g  \sin\theta}{L}  =0
			\end{equation} 
			
			Untuk persamaan gerak pada sumbu $ \hat{r}$, berlaku
			\begin{equation}
			w \cos \theta +T = \dfrac{mv^2}{r} + m\dot{\theta^2}R
			\end{equation}
			\begin{equation}
			-mg \cos \theta +T = m \dot{\theta^2}l
			\end{equation} 
			\begin{equation}
			 \dot{\theta^2}+\dfrac{g}{l} \cos \theta =\dfrac{T}{ml}
			\end{equation} 
### b Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).
Hasil dari perhitungan menggunakan metode analitik digrafikkan di https://plotly.com/~Avestory/3/#/
			
			\begin{equation}
			\dfrac{d^2\theta}{dt^2} - \dfrac{g\theta}{l} =0 
			\end{equation} 
			Persamaan diferensial ini adalah persamaan diferensial karakteristik, 
			sehingga dengan memisalkan $\lambda_{12} = \pm \sqrt{\dfrac{g}{l}}i$, sehingga:
			\begin{equation}
			\theta = C\exp{\lambda_1t}+D\exp{\lambda_2t}
			\end{equation} 
			\begin{equation}
			\theta = C (\cos \sqrt{\dfrac{g}{l}}t + i \sin \sqrt{\dfrac{g}{l}}t) +
			D(\cos \sqrt{\dfrac{g}{l}}t - i \sin \sqrt{\dfrac{g}{l}}t)
			\end{equation} 
			\begin{equation}
			\theta = (C+D) \cos \sqrt{\dfrac{g}{l}}t +  i (C-D) \sin \sqrt{\dfrac{g}{l}}t
			\end{equation} 		
			\begin{equation}
			\theta = A \cos \sqrt{\dfrac{g}{l}}t +   B \sin \sqrt{\dfrac{g}{l}}
			\end{equation} 	
			Saat t = 0, asumsikan bandul berada di amplitudo ($\theta_{max}$) sehingga sudut maksimum.
			\begin{equation}
			\theta_{max} = A \cos 0 + 0 \Rightarrow \theta_{max} = A
			\end{equation} 	
			Didapat A = amplitudo, B  = 0.
			Sehingga, pada akhirnya akan didapat 
			\begin{equation}
			\theta = A \cos  \sqrt{\dfrac{g}{l}}t, \\ \dot{\theta} =-\sqrt{\dfrac{g}{l}} A \sin \sqrt{\dfrac{g}{l}}t
			\end{equation} 	
			Untuk persamaan kedua, dengan mensubstitusikan persamaan sebelumnya,
			\begin{equation}
			\dot{\theta^2} + \dfrac{g}{l}cos\theta = \dfrac{T}{lm}
			\end{equation} 
			Karena menggunakan pendekatan sudut kecil, maka	
			\begin{equation}
			T \approx \left((\sqrt{\dfrac{g}{l}}A\sin \sqrt{\dfrac{g}{l}}t)^2 +\sqrt{\dfrac{g}{l}}\cos\theta\right)lm
			\end{equation} 	
			\begin{equation}
			T \approx A^2 g \sin^2 (\sqrt{\dfrac{g}{l}}t) +m\sqrt{gl}  \cos \theta
			\end{equation} 
			
			
	
			
### c 
Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).Hasil dari perhitungan menggunakan metode numerik digrafikkan di https://plotly.com/~Avestory/1/#/ 

		
			Dengan metode Euler,
			\begin{equation}
			\dfrac{df}{dx}= \dfrac{f(x+L)-f(x)}{h} \Rightarrow \dfrac{f^{i+1}-f^i}{\Delta x}
			\end{equation}
			Persamaan $\ddot{\theta}$ dan $\dot{\theta}$ dapat dirubah menjadi
			\begin{equation}
			\dot{\theta}=\dfrac{d\theta}{dt}=  
			\dfrac{\theta^{i+1}-\theta^i}{\Delta t} \Rightarrow \theta^{i+1} = \dot{\theta}^i\Delta t+ \theta^i
			\end{equation}
			dan
			\begin{equation}
			\ddot{\theta}=\dfrac{g}{l} \sin \theta \Rightarrow  \dfrac{d\dot{\theta}^i}{dt} =  \dfrac{g}{l} \sin \theta
			\end{equation}
			\begin{equation}
			 \dfrac{\dot{\theta}^{i+1}-\dot{\theta}^i}{\Delta t} = \dfrac{g}{l} \sin \theta^{i} 
			\end{equation}
			\begin{equation}
			\theta^{i+1}=\dfrac{g}{l} \sin \dot{\theta}^{i}\Delta t+\dot{\theta}^i 
			\end{equation}
### d
Untuk menyelesaikan secara numerik, dibuat kode di C++ sebagai berikut:

```C++
/*
	kodeno2d.cpp
	
	Menghitung solusi PDB menggunakan metode numerik
*/

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
```

dapat dijalankan secara daring menggunakan [http://cpp.sh/](http://cpp.sh/) atau aplikasi lainnya. Kode juga tersedia di repository GitHub ini di https://github.com/mnauvalfr/uasfiskom/blob/master/kodeno2d.cpp

## Soal 3 | Jaringan saraf tiruan dengan aplikasi TensorFlow

### a
Dalam proses penyelesaian masalah, dataset yang telah diberikan dimasukkan terlebih dahulu ke dalam perangkat lunak Microsoft Excel untuk dianalisa bentuk persebaran datanya. Untuk tabel data pertama, terdapat persebaran data seperti berikut.
![](UASFiskom0301.png)
Berdasarkan persebaran data yang terdapat di tabel di atas, terlihat jelas bahwa data dapat dipisahkan dengan metode perceptron. Dengan data yang telah didapatkan, dilakukan uji coba di laman daring Artificial Neural Network Playground yang disediakan oleh Tensorflow. Ketentuan dan batasan uji coba yang terdapat adalah sebagai berikut. 
![](UASFiskom0302.png)
### b

### c

### d


## Soal 4 | Algoritma genetik sederhana dengan JS

### a
Fungsi yang dimaksud adalah

```JavaScript
// Get interpretation of position and group from chromosome
function getValues() {
	var p = arguments[0];
	
	var xs = p.slice(0, 3);
	var ys = p.slice(3, 6);
	var gs = p.slice(6);
	
	var x = -1;
	var y = -1;
	var g = -1;
	
	/*
	x = xs;
	y = ys;
	g = gs;
	*/
	
	return [x, y, g];
}
```

dengan .. (penjelasannya).

### b

### c

### d


## Soal 5 | Research based learning

### a Tujuan

### b Rumusan masalah

### c Metode

### d Hasil dan diskusi

### e Referensi
1. Penulis, "Judul", Website, ..
2. Penulis, "Judul", Journal, vol. no., pp. Bulan Tahun, DOI ..
