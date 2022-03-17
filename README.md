# i2c-Haberlesme-Protoku

MPU6050 entegresini geliştirme kartınıza bağlayınız.

i2c open_drain bağlantıdır ve pull-up direncine ihtiyaç duyar.
Çift taraflı bir haberleşmedir master-slave arasında bir hat üzerinden senkron data gönderilir.
Clk bizim belirlediğimiz frekanslarda sürekli bir sinyal üretir.
Birden fazla cihaz chip_select piniyle bağlanabilir.

SDA pini LOW olduğunda haberleşmebaşlar.
8 bit data gider.

i2c protokollü cihazın datasheetini inceleyerek okuma ve yazma işlemlerini yapabilirsiniz.
