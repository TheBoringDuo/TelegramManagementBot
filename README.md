
By ysanatomic.

(NOT UPLOADED YET) (SOME BASIC FILES ARE MISSING)

This is Managment bot for telegram. You can find him in telegram as @LoopedInfinity (Loop).

The configuration is easy. Just look at the basic __main.py__ file.

The modules are in .modules. You can add new modules if you want. After you code your next module you need to import the function and create handlers in __main__.py. You can do that that way:

```
# newmodule.py:

def NewFunction(bot, update):
  # your function
  
```

```
# __main__.py
from modules.newmodule import NewFunction
```

You can create the handler like the other ones in the file.

This bot is based on that api: https://python-telegram-bot.readthedocs.io/en/stable/
 
The configuration process is simplified as much as possible.

Open the YOUNEEDTHIS file and read about the config process
