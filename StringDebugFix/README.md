patch the file in (if you don't have the patched version from epic) `./Engine/Extras/LLDBDataFormatters`

get sure that the import in ~/.lldbinit is set correct, double check if the file exists at the given path since old engine versions might have written an (now) invalid path to it before...

`command script import "~/UnrealEngine/5.2/Engine/Extras/LLDBDataFormatters/UEDataFormatters_2ByteChars.py"`
