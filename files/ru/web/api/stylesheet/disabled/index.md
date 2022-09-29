---
title: StyleSheet.disabled
slug: Web/API/StyleSheet/disabled
tags:
  - Свойство
  - Стили
translation_of: Web/API/StyleSheet/disabled
---
{{APIRef("CSSOM")}}

Свойство **`disabled`** интерфейса {{domxref("StyleSheet")}} определяет будет ли таблица стилей защищена от применения в документе

Таблицу стилей можно отключить, установив для этого свойства значение `true`, или, если она неактивна, с помощью [альтернативной таблице стилей](/ru/docs/Web/CSS/Alternative_style_sheets). Заметьте, что `disabled == false` не гарантирует применение таблице стилей (она может быть удалена из документа, к примеру).

## Синтаксис

```
bool = stylesheet.disabled
```

## Пример

```js
// Если таблица стилей отключена...
if (stylesheet.disabled) {
  // ... применять стили в строке.
}
```

## Спецификация

{{Specifications}}

## Поддержка браузерами

{{Compat}}