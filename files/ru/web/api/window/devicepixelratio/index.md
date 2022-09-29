---
title: Window.devicePixelRatio
slug: Web/API/Window/devicePixelRatio
translation_of: Web/API/Window/devicePixelRatio
---
{{APIRef}}

## Сводка

**devicePixelRatio** - свойство глобального объекта [window](/ru/docs/Web/API/Window/window) (доступно только для чтения). Оно содержит отношение разрешения дисплея текущего устройства _в физических пикселях_ к _разрешению_ в _логических (CSS) пикселях_. Также это значение можно интерпретировать как отношение размера одного _физического пикселя_ к размеру одного _логического_ (_CSS) пикселя_.

Не существует событий или поддержки колбэков при изменении этого свойства (например, когда пользователь перетащил окно с одного дисплея на другой, имеющих различную плотность пикселей).

## Синтаксис

```
value = window.devicePixelRatio;
```

## Полифил

Свойство не поддерживается в IE ниже 11, однако в IE10 можно получить значение в виде отношения:

```
window.screen.deviceXDPI / window.screen.logicalXDPI
```

## Спецификация

{{Specifications}}

## Поддержка браузерами

{{Compat}}