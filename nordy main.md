#comfyui
https://www.runcomfy.com/ru/comfyui-web
есть платный и бесплатный тарифный план 


MOC

[[Промпты]]
[[Инфлюенсеры по AI]]
## Модели ComfyUI Civit
### Для дизайна

QR-Code
Pilgrim_2D SDXL


SDXL[ Envy Shadow Minimalism](https://civitai.com/models/234128/envy-shadow-minimalism-xl-01)

FLUX

[специально для pod](https://civitai.com/models/125267?modelVersionId=136833)
[ютуб объяснение](https://civitai.com/models/858494/t-shirt-graphic-designs-workflow)



[Отпрвка в телеграм картинок с comfyUI ](https://civitai.com/models/413438/comfyui-custom-node-telegramsender)
NewRealityAllinOne хорошо справился со скелетами


Создание от и до 


![[Pasted image 20250121204301.png]]
[stroke cartoon](https://www.shakker.ai/modelinfo/89c38e448d634573a3b9593e219bddb4/CJ-Outline-Stroke-Cartoon-Illustration?from=search)
Можно продавать и распространять 

[Тест, чего-то похожего на MJ](# Ars MidJourney Style - Flux)
Florence => Описание изображения 
caricature-flux! Подходит под модель, можно продавать изображения!
LORA
[Для америки пойдёт типаб](https://civitai.com/models/1049734/ctai-filmore)
[Иллюстрации](https://civitai.com/models/278626/box-series-trend-illustrationlessgreater) базовая 1.5
![[Pasted image 20250121011459.png]]

[Аниме с чибби](https://civitai.com/models/934628/animepro-flux)
[детская модель](https://civitai.com/images/8920109)
[sfw и nsfw OnlyFans](https://civitai.com/models/226533/iniverse-mixsfw-and-nsfw)
[Lora но почему-то в моделях, рогатка](https://civitai.com/models/824950/stoiqo-afrodite-lora)
[3d cartoon flux для игр, но слишком детская и пластиковая](https://civitai.com/models/662924/3d-cartoon-vision-flux)



## Lora

Coloriong book => Plastic

[ Happy Ai-Claymation-cute 3D characters 3D](https://www.shakker.ai/th/modelinfo/7970c9de326c4825ac70c54e9046dc6c/Happy-Ai-Everything-is-Clay-Halloween-themed-cute-3D-spooky-characters-icons-claymation-world)

Old school tattoo
https://civitai.com/models/726890/old-schoolvintage-tattoo-style-for-flux
Ultra low angle 
СЕТ
AIDMA
[MJ anime ](![[Pasted image 20250126232312.png]])
[steven rhodes ](https://civitai.com/models/491378/retro-comics-sdxl-10)
austin abbey тамплиеры но flux


T'-shirt vector style
tshirt design, cat, retro sunset in the background, in the style of 5h1rt

![[Pasted image 20250126223654.png]]



## Wildcards 
На Flux Amateurphoto
Нода Flux Prompt generator

## Redux 

## Удаление фона 

RMBG 2-0 не супер справляется по крайне мере с реализмом подрезает лапы лисе
![[Pasted image 20250120070729.png]]

c кривыми лучше уже режет лучше, но с ними перебор

[Выгрузка множества вариантов через текстовый файл](https://www.youtube.com/watch?v=YR68lAhCFxg)

Load from dir не ворк


IMP:
Load Images Загрузка

Проблема как это выгружать
Возможно нужно для каждого изображения латент имг вставлять в семплер
Круто то что можно конкатинэй делать (складывание 1:2:3
1+2+3)
CR text -> concatenate -> 
позволяет добавить частичку текста
вставляется в текст энкод
![[Pasted image 20250119065410.png]]



## Нахождение пайплайнов

Openart
ComfyUI

## Модели
![[Pasted image 20250117232905.png]]
Можно подать запрос на добавление какой-то модели
Получение

### Устранение проблем при внедрении пайплайнов с других сайтов

Get Set Заменить, и возможны проблемы при присоеденение клипов с Load


## Lora name 

![[Pasted image 20250118003204.png]]

## Изменение стиля 

Чтобы улучшить читаемость стиля можно загрузить сразу несколько изображений, иногда это помогает бывает так же что это идёт во вред в зависимости от референса. 

IP Adapter 
resemble
СЛОООЖНААА 
Clip Vision не понятно Load clip vision
Clip -> IpAdapter последовательно 
Style transfer precise => для лучшей подгонки стиля
Сильный если, не выявляется

### Face ID
если требуется лицо -> load подключается к IPAadapter

Лица можно использовать как вместе со стилем, так и без него в данном примере 
![[Pasted image 20250118011207.png]]
![[Pasted image 20250118010142.png]]
Глава 4.3 Подробнее можно изучить там(пот), но нужно чтобы разобраться в адаптации стиля 


## Увеличение


## ControlNet


![[Pasted image 20250118003819.png]]

Совместимость моделей с препроцессором 
![[Pasted image 20250118005145.png]]

### Использование мульти контролнета

Нужно банально суммировать их до суммы в 1 по весу
Изображение подключается к препроцессору параллельно, Apply последовательно



Рекомендуется ImageResize

![[Pasted image 20250117225133.png]]

В одном блоке:
Controlnet preproccessor увеличивает изображения 
С препроцессора можно взять превью 
Load control net model 
Apply controlnet Pos Neg -> Выгружается всё в семплер

ВАЖНО : Изображение нужно ресайзить за счет препроцессора

Не понял: convert_

Выгружается всё в семплер

WD tagger

## Узнавание промптов :

### Clip Interrogator 
Более детальный

### WD tagger

 больше показывает что на картинке находится

### LLM




Фичи support stealth mode settings
	базовое увеличение
	3.2 Image size Для увеличения изображений сводка 

[Обучение ComfyUi в виде игры](https://comfyanonymous.github.io/ComfyUI_tutorial_vn/)
[[Hotkeys]]

