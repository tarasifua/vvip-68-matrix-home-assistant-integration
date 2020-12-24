# Интеграция **[WiFi панели / гирлянды на esp8266 от vvip-68](https://github.com/vvip-68/GyverPanelWiFi) с Home Assistant**

Данная интеграция построена на наборе автоматизаций для Home Assistant и позволяет управлять матрицей а также настраивать большую часть параметров.

### Внешний вид
(https://github.com/tarasifua/vvip-68-matrix-home-assistant-integration/blob/main/screenshot/screenshot.png?raw=true)
### Установка

В свой файл `configuration.yaml` внести строки, которые есть в одноименном файле в репозитории. Если у вас уже есть подключенные файлы `input_boolean`, `input_number`,  `input_text`,  `input_select` или `script`, перенести содержимое этих файлов в свои.

Папку `matrix_automations` поместить в свою папку с автоматизациями.

Содержимое файла `ui-lovelace.yaml` также перенести в свой файл настроек Lovelace.

Также, для отображения карточек настройки параметров с кнопками `+` и `-` надо установить компонент [numberbox-card](https://github.com/htmltiger/numberbox-card), проще всего это сделать через [HACS](https://hacs.xyz/)