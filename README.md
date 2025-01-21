# 高仿Gboard同文输入法主题

### 效果预览
![](./Preview/IMG_20250119_133405.jpg)
![](./Preview/IMG_20250119_133415.jpg)
![](./Preview/IMG_20250119_133430.jpg)
![](./Preview/IMG_20250121_204013.jpg)
![](./Preview/IMG_20250121_204004.jpg)

### 附带我的快捷栏代码
```yaml
    switches:
  - name: transcription
    states: [ 简体 , 繁体 ]
    reset: 0
  - name: ascii_punct
    states: [ 中符 , 英符 ]
    reset: 0
  - options: [_key_VoidSymbol]
    states: ["           "]
  - options: [ _key_liquid_keyboard_emoji ]
    states: [ 😁️ ]
  - options: [ _key_liquid_keyboard_clipboard ]
    states: [ 📋 ]
  - options: [ _keyboard_numberb ]
    states: [ <I> ]
  - options: [_key_Hide]
    states: ["︾"]
```
