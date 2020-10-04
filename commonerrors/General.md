In general, files must be deobfuscated in the reverse order in which obfuscators were applied. For example, if your file is obfuscated with Stringer and then Allatori, you would run the Allatori transformers, and then the Stringer ones. Also, if an obfuscator was applied multiple times (e.g. several layers of Allatori), you must run the transformers multiple times. The only exception with this rule is with flow obfuscation transformers, which typically do not need to be run multiple times.