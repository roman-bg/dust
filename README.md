Мръсният въздух е проблем както на големите български градове, така и на малките населени места в България. Ако погледнем карта на проекта AirSofia, обаче забеляваме, че най-много станции има в София, като те последователно намаляват към областните градове и накрая просто липсват в малките населени места. Вероятна причина е и високата цена (120 Евра с доставката от Полша) за една станция. Тъй като в ПП Зелено движение считаме, че харчовете за реклама в предизборната кампания са пари хвърлени на вятъра с този проект местната организация във Велико Търновосе стреми да преодолее горепосочения проблем. Следвайки това просто ръководство вие ще се сдобиете със станция, която ще ви струва около 30 лева, а данните и ще бъдат видими като в мрежата на AirSofia, така и в тази на sensor.community.

За да сглобите вашата станция ще са ви нужни две неща, микроконтролерна платка от вида на Wemos D1 mini и сензор за финни прахови частици от серията PMS1003, PMS300, 3PMS5003, PMS6003, PMS7003. Общата им цена, ако ги поръчате през Aliexspres  е около 30 лева с доставката и ДДС-то. В България също можете да ги намерите, но тогава цената ще е доста по-висока. След като си ги набавите свържете сензота с платката както е посочено на картинката по-долу.

![Image of дуст](https://github.com/roman-bg/dust/blob/main/img/pms5003-d1-mini.png)

Веднъж направили това е време да "флашнете" микроконтролера със фърмуера. Ползвайте кода който ще намерите в папката Code, firmware.bin. За да флашнете платката изтеглете си ESPEasyFlasher от линка тук https://github.com/BattloXX/ESPEasyFlasher. Стартирайте програмата, като предварително сте свързали платката с кабел, към USB порта на вашия компютър и натиснете бутона flash.

![Image of дуст](https://github.com/roman-bg/dust/blob/main/img/screenshot.png)

Ако станцията е изградила връзка с Wi-Fi, може да се свържете с нея, като сканирате съответната мрежа. За сканиране с мобилен телефон или таблет ползвайте безплатното приложение Fing за iOS и Fing за Андроид, за сканиране с компютър ние използваме Advanced IP Scanner. В списъка с устройства в мрежата Ви, търсете устройство с таг „Expressif“. След като я откриете и изберете от менюто, сканирайте я за услуги. Отворете я в браузър на порт 80. Ще видите основната ѝ страница, разгледайте показанията, но не пипайте настройките ако не сте сигурни какво правите! Уверете се, че станцията:
– е закрепена трайно и стабилно;
– не е монтирана в затворено помещение;
– не е изложена на пряка слънчева светлина;
– не е от вътрешната страна на балкон и има достатъчно свободно пространство под нея;
– не пушите наблизо, не приготвяте скара наблизо;
– няма близки инцидентни битови замърсители.

Монтирайте сензора и микроконтролерната платка във водонепропусклива кутия с отвор осигуряващ достъп на въздух до вентилатора на сензора. Време е да регистрирате вашата станция в мрежата на sensor.community! Това можете да направите директно на следния адрес – https://devices.sensor.community/?lang=bg следвайки указанията там. Уверете се преди това, че вашата станция функционира. Това е всичко, вече имате станция измерваща нивата на замърсяване с финни прахови частици PM10, PM2.5 и PM1 и във вашето населено място.


