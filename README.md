\documentclass[12pt]{article}
\usepackage{amsfonts}
\usepackage{amsmath}
\usepackage{amsthm}
\usepackage[utf8]{inputenc}
\usepackage{enumitem}
\usepackage{graphicx}
\title{Jawaban UAS Fisika Komputasi (FI-3201) Semester 2 2019-2020}
\author{M Nauval FR 10217023\\
	Steffan\\
	Humam\\
	Awla\\
	Hans\\
	Wilbert\\}
\begin{document}
	\maketitle
Catatan: jawaban dituliskan dalam format .tex, lalu dikonversi ke format MD dengan https://cloudconvert.com/tex-to-md. Di GitHub akan diberikan 2 file, versi konversi markdown dan versi  .tex (dalam format txt notepad).\\
% Nomor 01	
\section{Soal No.1}
	\includegraphics[scale=0.25]{UASFiskom0201.png}\\
	\begin{enumerate}[label=(\alph*)]
		%1a%--------------------------------------------------------------------------------
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
		Substitusikan persamaan $\cos \theta =\dfrac{x}{l} $ , $\sin \theta =\dfrac{y}{l} $, dan $ w =-mg$, \textbf{sehingga akan didapat}
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
		Substitusikan persamaan $	F_{visko_y}= 3\eta\pi D\ddot{y}	$ dan $\sin \theta =\dfrac{y}{l} $, \textbf{sehingga akan didapat}
		\begin{equation}
		\ddot{y} + \dfrac{3\pi\eta D}{m} \dot{y} + \dfrac {({\dot{x^2}+\dot{y^2}})y}{l^2} -\dfrac{gy^2}{l^2} = -g
		\end{equation}
		%1b%--------------------------------------------------------------------------------
		\item Untuk persamaan gaya di sumbu x, 
		\begin{equation}
		\dfrac{g}{l^2}xy - \dfrac{3\pi\eta D}{m} \dot{x} - \dfrac{(\dot{x^2}+\dot{y^2})}{l^2}x =\ddot{x}
		\end{equation} \\
		terdapat suku $\ddot{x}$ sebagai \textbf{komponen percepatan},$ \dfrac{3\pi\eta D}{m} \dot{x} $ sebagai \textbf{komponen gaya gesek menggunakan hukum Stokes}, $-\dfrac{(\dot{x^2}+\dot{y^2})}{l^2}x$ sebagai \textbf{komponen gaya sentripetal untuk tegangan tali}, dan $\dfrac{g}{l^2}xy$ adalah \textbf{komponen gaya gravitasi di tegangan tali}.
		
		Untuk persamaan gaya di sumbu y, 
		\begin{equation}
		\ddot{y} + \dfrac{3\pi\eta D}{m} \dot{y} + \dfrac {({\dot{x^2}+\dot{y^2}})y}{l^2} -\dfrac{gy^2}{l^2} = -g
		\end{equation}
		terdapat suku $\ddot{y}$ sebagai \textbf{komponen percepatan},$ \dfrac{3\pi\eta D}{m} \dot{y} $ sebagai \textbf{komponen gaya gesek menggunakan hukum Stokes}, $-\dfrac{(\dot{x^2}+\dot{y^2})}{l^2}y$ sebagai \textbf{komponen gaya sentripetal untuk tegangan tali}, dan $\dfrac{gy^2}{l^2}$ adalah \textbf{komponen gaya gravitasi di tegangan tali}. Selain itu, terdapat juga \textbf{komponen $-g$ sebagai komponen gravitasi (vertikal sumbu y)}.
		%1c%--------------------------------------------------------------------------------
		\item 
		Untuk benda jatuh bebas tanpa gesekan udara,  maka persamaan (2) (gaya di sumbu x) \textbf{ berubah menjadi }
		\begin{equation}
		\ddot{x} = 0
		\end{equation}
		Persamaan (3) (gaya di sumbu y)  \textbf{berubah menjadi }
		\begin{equation}
		\ddot{y} = -g
		\end{equation}
		Saat gaya jatuh bebas tanpa ada gesekan, komponen tegangan dan viskositas bisa diabaikan, sehingga $\eta =0$ dan $ l \approx \infty$.
		%1d%--------------------------------------------------------------------------------
		\item 
		Untuk simpangan kecil, maka $\dfrac{y}{l} \approx 1$ dan $\dfrac{x}{l} \approx \theta$. Tanpa gaya gesek, maka $\eta =0$.
		\textbf{	Sehingga, didapat 
		\begin{equation}
		\ddot{x} - \dfrac{(\dot{x^2}+\dot{y^2})}{l}\theta + g\theta =0
		\end{equation} \\,
		\begin{equation}
		\ddot{y} - \dfrac{(\dot{x^2}+\dot{y^2})}{l}\theta + g =-g
		\end{equation}} \\,
	\end{enumerate}
% nomor 02%--------------------------------------------------------------------------------
\section{Soal No.2}
		\begin{enumerate}[label=(\alph*)]
			%2a%--------------------------------------------------------------------------------
			\item 

			Pertama diketahui posisi bandul sebagai berikut:\\
			\includegraphics[scale=0.2]{UASFiskom0201.png}\\
			
			T adalah gaya tegang tali, Fv adalah gaya viskositas akibat udara, dan W adalah berat.\\
			Persamaan gerak pada sumbu $\hat{\theta}$ dapat diturunkan dengan mengingat $\alpha = \dfrac{d^2\theta}{dt^2} =\dfrac{M}{I}$, dimana $\alpha$ adalah momentum sudut, M adalah momen, dan I adalah inersia.
			
			Torsi ditentukan oleh proyeksi gaya ke arah tangensial:
			\begin{equation}
			M = -mgL\sin \theta
			\end{equation} 
			Momen inersia pendulum adalah momen inersia lingkaran:
			\begin{equation}
			I = mL^2
			\end{equation} 
			Sehingga, persamaan gerak di sumbu $\hat{\theta}$ adalah, dengan mencoret suku-suku yang sama
			\begin{equation}
			\dfrac{d^2\theta}{dt^2} = \dfrac {M}{I} =\dfrac{g \sin\theta}{L} 
			\end{equation} 
			\begin{equation}
			\dfrac{d^2\theta}{dt^2} +  \dfrac{g  \sin\theta}{L}  =0
			\end{equation} 
			
			\textbf{Untuk persamaan gerak pada sumbu $ \hat{r}$, berlaku}
			\begin{equation}
			w \cos \theta +T = \dfrac{mv^2}{r} + m\dot{\theta^2}R
			\end{equation}
			\begin{equation}
			-mg \cos \theta +T = m \dot{\theta^2}l
			\end{equation} 
		\begin{equation}
			 \dot{\theta^2}+\dfrac{g}{l} \cos \theta =\dfrac{T}{ml}
			\end{equation} 
			

			%2b%--------------------------------------------------------------------------------
			\item
			\begin{equation}
			\dfrac{d^2\theta}{dt^2} - \dfrac{g\theta}{l} =0 
			\end{equation} 
			Persamaan diferensial ini adalah persamaan diferensial karakteristik, sehingga  dengan memisalkan $\lambda_{12} = \pm \dfrac{g}{l}i$, sehingga:
			\begin{equation}
			\theta = C\exp{\lambda_1t}+D\exp{\lambda_2t}
			\end{equation} 
			\begin{equation}
			\theta = C (\cos \dfrac{g}{l}t + i \sin \dfrac{g}{l}t) +D(\cos \dfrac{g}{l}t - i \sin \dfrac{g}{l}t)
			\end{equation} 
			\begin{equation}
			\theta = (C+D) \cos \dfrac{g}{l}t +  i (C-D) \sin \dfrac{g}{l}t
			\end{equation} 		
			\begin{equation}
			\theta = A \cos \dfrac{g}{l}t +   B \sin \dfrac{g}{l}t
			\end{equation} 	
			Saat t = 0, asumsikan \textbf{bandul berada di amplitudo} sehingga sudut maksimum.
			\begin{equation}
			\theta_{max} = A \cos 0 + 0 \Rightarrow \theta_{max} = A
			\end{equation} 	
			Didapat A = amplitudo, B  = 0.
			Sehingga, pada akhirnya akan didapat 
			\begin{equation}
			\theta = A \cos  \dfrac{g}{l}t, \\ \dot{\theta} =-\dfrac{g}{l} A \sin \dfrac{g}{l}t
			\end{equation} 	
			Untuk persamaan kedua, dengan mensubstitusikan persamaan sebelumnya,
			\begin{equation}
			\dot{\theta^2} + \dfrac{g}{l}cos\theta = \dfrac{T}{lm}
			\end{equation} 
			Karena menggunakan pendekatan sudut kecil, maka	
			\begin{equation}
			T \approx \left((\dfrac{g}{l}A\sin \dfrac{g}{l}t)^2 +\dfrac{g}{l}\cos\theta\right)lm
			\end{equation} 	

			%2c%--------------------------------------------------------------------------------
			\item Dengan metode Euler,
			\begin{equation}
			\dfrac{df}{dx}= \dfrac{f(x+L)-f(x)}{h} \Rightarrow \dfrac{f^{i+1}-f^i}{\Delta x}
			\end{equation}
			Persamaan $\ddot{\theta}$ dan $\dot{\theta}$ dapat dirubah menjadi
		\begin{equation}
			\dot{\theta}=\dfrac{d\theta}{dt}=  \dfrac{\theta^{i+1}-\theta^i}{\Delta t} \Rightarrow \theta^{i+1} = \dot{\theta}^i\Delta t+ \theta^i
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
			Hasil dari perhitungan menggunakan metode numerik digrafikkan di 			\begin{verbatim}https://plotly.com/~Avestory/1/#/
			\end{verbatim}
			
			%2d%--------------------------------------------------------------------------------
			\item 
			Untuk menyelesaikan secara numerik, dibuat kode di C++ sebagai berikut:
			\begin{verbatim}
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
			
			myfile <<t[i]<< " " << theta[i] << " "<< thetadot[i] <<" "<< T[i] <<"\n";
			
			cout << "t[" << i << "]: " << t[i] << "\n";
			cout << "theta[" << i << "]: " << theta[i] << "\n";
			cout << "thetadot[" << i << "]: " << thetadot[i] << "\n";
			cout << "T[" << i << "]: " << T[i] << "\n" << "\n";
			}
			myfile.close();
			
			
			/* terminasi program */
			return 0;
			}
			\end{verbatim}
			Kode juga akan disertakan di GitHub.
		\end{enumerate}
% nomor 03
\section{Soal No.3}
\begin{enumerate}[label=(\alph*)]
	\item Dalam proses penyelesaian masalah, dataset yang telah diberikan dimasukkan terlebih dahulu ke dalam perangkat lunak Microsoft Excel untuk dianalisa bentuk persebaran datanya. Untuk tabel data pertama, terdapat persebaran data seperti berikut.
\section{Soal No.4}
\begin{enumerate}[label=(\alph*)]
	\item 
	Fungsi untuk mengekstrak informasi dari masing-masing kromsom adalah sebagai berikut:
	\begin{verbatim}
	[x, y, c] = getValues(p);
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
	\end{verbatim}
	\item
	Fungsi \textit{fitness} yang diminta dibuat sebagai berikut:
	\begin{verbatim}
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
	\end{verbatim}
\end{enumerate}
\end{document}
%--------------------------------------------------------------------------------
