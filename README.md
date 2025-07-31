# Variant Breeding
Simple mod that enables variant breeding for all dinos (including Modded Dinos and Variants).

With this mod enabled, a Spino can now breed with a Aberrant Spino.  
The baby will have a 50/50 chance to be from either parent variants.

Now modded dinos can breed together directly.  
Works on existing and new dinos from all mods.

## Configuration
Configuration is optional.  
By default, all dinos with the same tag will be able to breed together.  
The following config options are available under the `[VariantBreeding]` section in your `GameUserSettings.ini`:

### Debug
This will enable debug logging for the mod.  
Usefully for troubleshooting.  
Default: `False`
```ini
[VariantBreeding]
Debug=True
```

### Use Tags
If `True` the mod will use the tags of the dino to determine if they can breed.  
This will cause all wyverns to breed together, as they all share a tag.  
If `False`, the mod will only check if the dino have a common parent variant.  
This will work for most dinos, but if a mod author has not set the parent variant correctly, it may not work as expected.  
Default: `True`
```ini
[VariantBreeding]
UseTags=True
```

### Exclude Dinos
Adding Dinos to this list will prevent variant breeding for them.
Separate multiple paths with a comma or semicolon.  
Default: ``
```ini
[VariantBreeding]
ExcludeDinos="Dino1_Character_BP_C,Dino2_Character_BP_C"
```

Discord: https://discord.com/invite/K4a4DvZak5
