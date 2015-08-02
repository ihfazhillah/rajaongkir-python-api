# rajaongkir-python-api

Python api untuk mengakses rajaongkir.com

# installasi
python setup.py install

# contoh penggunaan

Pastikan anda telah memiliki apikey raja ongkir.com, bila belum silahkan regristasi kesana.

import rajaongkir

cari = rajaongkir.RajaOngkir("Your APi key")

print cari.hitungOngkos("kota dari", "kota tujuan", "berat", "nama kurir")
