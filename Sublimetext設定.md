> 更新日期: 20160720

# 目錄
<!-- MarkdownTOC -->

- [Sublime text 3](#sublime-text-3)
    - [中文輸入修正](#中文輸入修正)
    - [ConvertToUTF8](#converttoutf8)
    - [SideBarEnhancements](#sidebarenhancements)
    - [Theme - Kronuz](#theme---kronuz)
    - [BracketHighlighter](#brackethighlighter)
    - [Git](#git)
    - [GitGutter](#gitgutter)
    - [Alignment](#alignment)
    - [MarkdownEditor](#markdowneditor)
    - [MarkdownPreview](#markdownpreview)
    - [OmniMarkupPreviewer](#omnimarkuppreviewer)
    - [MarkdownDark](#markdowndark)
    - [Markmon](#markmon)

<!-- /MarkdownTOC -->


# Sublime text 3
直接在 Software Manager下載就好

## 中文輸入修正
修正方法: http://www.jianshu.com/p/9f2a11851b4e
修正完用右鍵開啟跟用內建的 new file 一樣會有無法輸入中文的問題

## ConvertToUTF8
安裝完後設定 sublime-settings 將 encoding_list 中 Chinese Traditional 移到第一個

## SideBarEnhancements

## Theme - Kronuz
啟用設定:
```json
{
    "theme": "Theme - Kronuz.sublime-theme",
    "color_scheme": "Packages/Theme - Kronuz/Kronuz.tmTheme"
}
```
## BracketHighlighter

## Git

## GitGutter

## Alignment

## MarkdownEditor
使用黑色主題, 在 user setting 內更改為:
```json
{
    "color_scheme": "Packages/MarkdownEditing/MarkdownEditor-Dark.tmTheme",
}
```

## MarkdownPreview
能夠開啟 browser 預覽 Markdown
安裝完後在 user keymap 中 加入key:
```json
{"keys":["alt+m"],"command":"markdown_preview","args":{"target":"browser"}}
```
無法即時更新但可以用連結

## OmniMarkupPreviewer
可以即時預覽的 previewer, 開啟mathjax公式:
```json
{
  "mathjax_enabled": true
} 
```
連結無法用但會即時更新

## MarkdownDark 
美化 Markdown 的好幫手

## Markmon
比較厲害的即時更新viewer.  
安裝比較複雜, 要另外有: markmon, pandoc  
Markmon:
```bash
npm install -g markmon
```
安裝pandoc:
```bash
sudo apt install pandoc
```