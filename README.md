# vimium for zen-browser

### Custom key mappings
```shell
unmapAll

map f LinkHints.activateMode
map F LinkHints.activateModeToOpenInNewTab

map <m-j> nextTab
map <m-k> previousTab

map <a-s> Vomnibar.activateTabSelection
map j scrollDown
map k scrollUp
map h scrollLeft
map l scrollRight

map gg scrollToTop
map G scrollToBottom

map i enterInsertMode
map v enterVisualMode
map gi focusInput

map / enterFindMode
map n performFind
map N performBackwardsFind
```

### Custom search engines
```shell
w: https://www.wikipedia.org/w/index.php?title=Special:Search&search=%s Wikipedia

# More examples.
#
# (Vimium supports search completion Wikipedia, as
# above, and for these.)
#
# g: https://www.google.com/search?q=%s Google
# l: https://www.google.com/search?q=%s&btnI I'm feeling lucky...
# y: https://www.youtube.com/results?search_query=%s Youtube
# gm: https://www.google.com/maps?q=%s Google maps
# b: https://www.bing.com/search?q=%s Bing
# d: https://duckduckgo.com/?q=%s DuckDuckGo
# az: https://www.amazon.com/s/?field-keywords=%s
# qw: https://www.qwant.com/?q=%s Qwant
```
