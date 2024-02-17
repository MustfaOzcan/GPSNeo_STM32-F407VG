#GPSNeo_STM32-F407VG
 STM32-F407VG kartı programlama  CubeIDE üzerinde NEO-7M GPS Modülü ile uydu ile haberleşme 

| GPS PIN | STM PIN |
|---------|---------|
| VCC     | 5V      |
| GND     | GND     |
| RX      | TX      |

<div class="alert alert-info" role="alert">
  <strong>NOT:</strong> Gps modülü gönderici konumda olup STM'e verileri göndermektedir. STM'den GPS'e bir şey göndermediğimiz için GPS modülün TX bacağı kullanılmadı.
</div>



Devre 
=====
![WhatsApp Image 2024-02-07 at 12 37 41](https://github.com/MustfaOzcan/MustfaOzcan-GPSNeo_STM32-F407VG/assets/103693735/1deae815-559e-4c19-af97-ef891c410171)

<div class="alert alert-info" role="alert">
  <strong>NOT:</strong>  Gps modülünü bir çubuğun üzerine bantladım sinyalleri daha iyi almak için.Ayrıca iç ortamda gps'in uydulara bağlanması zor olmaktadır.Pencere kenarında çalışmanız önerilir.
</div>




Ekran Çıktısı
===========
![stmcubeide9fd](https://github.com/MustfaOzcan/MustfaOzcan-GPSNeo_STM32-F407VG/assets/103693735/2419e67c-8281-4eb3-8e44-cd138ea1bbde)

