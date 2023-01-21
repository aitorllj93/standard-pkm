---
banner: "![[Banners_Idea.jpeg]]"
banner_y: 0.50667
---
# Graph Filters
#types/idea  #status/draft  #project/standard-pkm 


Here are some useful filters for the Graph View

### Remove system notes
To remove the system notes, the easiest way is to exclude the `Docs` and `Templates` folders from the path:

`-path:Templates -path:Docs`

If for some reason you want to store the Docs in your Notes folder you should filter them out using the `project/standard-pkm` tag instead. **Don't even try to have your notes in the same folder than your templates.**

`-tag:#project/standard-pkm`

### Remove journal entries
If you also want to remove journal entries you might want to skip the `Journal` folder as well

`-path:Journal`

If you storing everything in your Notes folder you might need to use the `types/daily` tag instead:

`-tag:#types/daily`

### Remove bibliographical references
Same as above, you can remove the bibliographical references by excluding the `Bibliography` path

`-path:Bibliography`

If you storing references in Notes folder you might need to use the `types/reference` adn `types/extract` tag instead:

`-tag:#types/reference -tag:#types/extract`