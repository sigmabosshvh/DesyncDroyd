# DesyncDroyd
Полноценный Shizuku Android-клиент для обхода фильтрации ТСПУ, использующий zapret2/nfqws2.

Основан на этом PoC: https://github.com/sigmabosshvh/android-testtap-egress

Занимает VPN-слот для ingress.
Не требует ручной настройки стратегий - используется автоподбор из zapret2.
Стратегии взяты из https://github.com/Flowseal/zapret-discord-youtube и переведены с синтаксиса zapret на zapret2.
Исключительно для поддержки Telegram добавлен https://github.com/Flowseal/tg-ws-proxy.

## Compatibility

См. раздел [протестированные устройства и совместимость](COMPATIBILITY.md).

Протестировали свое устройство? Пожалуйста, сообщите о результате в Telegram-форуме.

## To do
* IPv6
* Пользовательская настройка стратегий
