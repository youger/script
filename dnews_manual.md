copy this line to .profile
```
export PATH=$PATH:your_path/script/dnews
```

# SYNOPSIS
    dnews [-fv] [-i number] [pattern]

# EXAMPLES

    Display specific index of news

        $ dnews 12

    Reload hot news, display specific index of news with detail url.

        $ dnews -fv -i 12

    Top 10 news.

        $ dnews "^\d\."

    Top 20 news.
     
        $ dnews "^[1-2]\d\." 

    Filter news which contain specific keyword.

        $ dnews -v "台海"
