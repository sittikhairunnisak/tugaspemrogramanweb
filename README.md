# Tugas_pemrograman_web
# Sitti Khairunnisak (22101053032)

Untuk menghitung panjang gelombang suatu gelombang, kita dapat menggunakan rumus:

\lambda = \frac{c}{f}

dimana \lambda adalah panjang gelombang, c adalah kecepatan cahaya, dan $ adalah frekuensi gelombang.

pemrograman kode Python yang menghitung panjang gelombang suatu gelombang dengan frekuensi 5 Hz:


| python                                                           |
| -----------------------------------------------------------------|
| c = 3e8  # kecepatan cahaya dalam m/s                            | 
| f = 5  # frekuensi dalam Hz                                      | 
| panjang gelombang = c / f                                        | 
| print("Panjang gelombang adalah", panjang gelombang, "meter.")   | 



Kode ini menetapkan nilai kecepatan cahaya menjadi `3e8` meter per detik dan frekuensi menjadi `5` Hz. Kemudian menghitung panjang gelombang menggunakan rumus dan menyimpan hasilnya dalam variabel `panjang gelombang`. Terakhir, mencetak hasilnya menggunakan fungsi `print()`.
nilai `c` dan `f` dapat diubah untuk menghitung panjang gelombang untuk gelombang yang berbeda.


{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Lambda Expression - Dictionary dalam Lambda\n",
    "\n",
    "Berikut ini tutorial terkait dictionary dalam lambda."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [],
   "source": [
    "#mendefinisikan data dictionary\n",
    "sales = [{'country':'Indonesia', 'sale':100.5},\n",
    "         {'country':'China', 'sale':200.2}, \n",
    "         {'country':'USA', 'sale':300.3},\n",
    "         {'country':'UK', 'sale':210.4}]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [],
   "source": [
    "#membuat map dan fungsi lambda\n",
    "country_key = map(lambda x: x['country'], sales)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['Indonesia', 'China', 'USA', 'UK']"
      ]
     },
     "execution_count": 3,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#melihat hasil key\n",
    "list(country_key)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [],
   "source": [
    "#membuat map dan fungsi lambda\n",
    "country_value = map(lambda x: x['sale'], sales)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[100.5, 200.2, 300.3, 210.4]"
      ]
     },
     "execution_count": 5,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#menampilkan hasil value\n",
    "list(country_value)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "                
    "                       
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.6.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
