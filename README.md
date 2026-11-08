# ИИ-редактор

Скилл для Claude, ChatGPT и других ИИ-агентов: пишет, редактирует, сокращает и вычитывает тексты на русском.

Скилл можно поставить в Claude, ChatGPT, Qoder и другие среды. Редактор подключается сам в любом чате, когда вы работаете с текстом.

## Установка

### Claude — веб и десктоп

1. Скачайте `ai-editor.zip` со страницы [Releases](https://github.com/vskrokha/ai-editor/releases/latest).
2. Откройте **Settings → Capabilities → Skills** и загрузите архив.

### Claude Code

```
/plugin marketplace add vskrokha/ai-editor
/plugin install ai-editor@vskrokha
```

Можно и вручную: скопировать папку `skills/ai-editor` в `~/.claude/skills/`.

### ChatGPT

1. Скачайте `ai-editor.zip` со страницы [Releases](https://github.com/vskrokha/ai-editor/releases/latest).
2. В боковой панели откройте **Plugins → Skills → Create → Upload from your computer** и загрузите архив.

## Структура репозитория

```
skills/ai-editor/SKILL.md   — сам скилл
plugin.json                 — манифест плагина для ChatGPT и Codex
.claude-plugin/             — манифест плагина и маркетплейса для Claude Code
```

## Автор

Влад Кроха, шеф-редактор в Сбере. Пишу про ИИ, тексты и продуктивность в канале [«Влад на удалёнке»](https://t.me/vkremote).

## Лицензия

[MIT](LICENSE)
