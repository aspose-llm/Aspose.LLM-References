---
title: AsposeLLMApi.SavePresetToJson
second_title: Aspose.LLM for .NET API Reference
description: AsposeLLMApi method. Exports one builtin preset instance to one inline JSON document. The output uses the same contract as LoadPresetFromJson. By default it emits extends plus only the properties that differ from the selected builtin preset defaults. Set includeDefaults to true to export a full preset snapshot with all writable fields
type: docs
weight: 150
url: /net/aspose.llm/asposellmapi/savepresettojson/
---
## AsposeLLMApi.SavePresetToJson method

Exports one built-in preset instance to one inline JSON document. The output uses the same contract as [`LoadPresetFromJson`](../loadpresetfromjson/). By default it emits `extends` plus only the properties that differ from the selected built-in preset defaults. Set *includeDefaults* to `true` to export a full preset snapshot with all writable fields.

```csharp
public static string SavePresetToJson(PresetCoreBase preset, bool includeDefaults = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| preset | PresetCoreBase | Preset instance to export. |
| includeDefaults | Boolean | `true` to include all writable preset fields; `false` to export only overrides. |

### Return Value

Indented JSON preset definition.

### See Also

* class [AsposeLLMApi](../)
* namespace [Aspose.LLM](../../asposellmapi/)
* assembly [Aspose.LLM](../../../)


