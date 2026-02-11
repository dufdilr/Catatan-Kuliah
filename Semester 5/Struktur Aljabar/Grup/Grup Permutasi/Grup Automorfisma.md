#Definisi #Teorema 

Misalkan $G$ suatu grup. Definisikan
$$
\text{Aut}\left({G}\right) = \{f: G \to G \mid f \text{ isomorfisma grup}\}
$$
Lebih lanjut, $\text{Aut}\left({G}\right)$ dengan operasi komposisi membentuk grup.

***
## Bukti

### Well Defined
Ambil $f, g \in \text{Aut}\left({G}\right)$. Berdasarkan [[Buat Backup/Prerquested/Relasi dan Fungsi/Komposisi Fungsi Bijeksi]], maka $g \circ f$ juga fungsi bijeksi. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Komposisi Homomorfisma Grup]], maka $g \circ f$ juga homomorfisma grup. Maka $g \circ f : G \to G$ adalah isomorfisma, terbukti
$$
g\circ f \in \text{Aut}\left({G}\right)
$$
Terbukti, komposisi terdefinisi dengan baik pada $\text{Aut}\left({G}\right)$.

### Asosiatif
Jelas berdasarkan [[Buat Backup/Prerquested/Relasi dan Fungsi/Komposisi Asosiatif]]

### Identitas
Tinjau $i_G:G \to G$ dengan $i_G(g) = g$ untuk setiap $g \in G$. Jelas untuk setiap $f \in \text{Aut}\left({G}\right)$ berlaku
$$
f\circ i_G = f = i_G \circ f
$$
Maka, $i_G$ adalah identitas di $\text{Aut}\left({G}\right)$.

### Invers
Berdasarkan [[Buat Backup/Prerquested/Relasi dan Fungsi/Fungsi Bijektif Invertibel]], maka terdapat $g:G \to G$ sedemikian sehingga
$$
f\circ g = g\circ f = i_G
$$
Terbukti setiap unsur di $\text{Aut}\left({G}\right)$ memiliki invers.

Perdefinisi, terbukti $\text{Aut}\left({G}\right)$ membentuk grup.

***

## Definition Used
* [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Isomorfisma (Grup)]]