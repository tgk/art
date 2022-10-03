# Open png

    eog file.png

# Automatically re-render

    while inotifywait -e close_write file.cfdg; do cfdg file.cfdg file.png; done

while inotifywait -e close_write wiki.cfdg; do cfdg wiki.cfdg wiki.png; done