```
__________.__          ___________.__  .__       .__        
\______   \  |__ ______\_   _____/|  | |__|__  __|__|______ 
 |     ___/  |  \\____ \|    __)_ |  | |  \  \/  /  \_  __ \
 |    |   |   Y  \  |_> >        \|  |_|  |>    <|  ||  | \/
 |____|   |___|  /   __/_______  /|____/__/__/\_ \__||__|   
               \/|__|          \/               \/          
                                              Replace Module
```

Provides the ability to replace text in the specified files or folder.

### Replace

You can replace specific text in files or folder paths.

```yaml
replace:
    PATH_PUBLIC_ASSETS + /vendor/vendor_name/styles.css:
        - ../img
        - vendor/vendor_name
```
