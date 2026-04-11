# Max Enchanted Gear

**Version:** 1.0.0  
**Minecraft Version:** 1.21.11  
**Pack Format:** 94.1

## About

This is a simple, lightweight **vanilla data pack** that lets you instantly get fully maxed-out enchanted gear for **Iron**, **Diamond**, or **Netherite** sets in one command.

Each function gives you:
- Complete set of **max-enchanted armor** (Protection IV, Mending, Unbreaking III, Thorns III, etc.)
- All 5 **max-enchanted tools** (Sword, Pickaxe, Axe, Shovel, Hoe) with the best possible enchantments
- 64 Cooked Porkchops
- 64 Enchanted Golden Apples
- 64 Golden Apples

Perfect for testing, creative mode, speedruns, or quickly setting up a strong kit.

Uses the modern **item component syntax** (1.20.5+ / 1.21+ compatible).


## File Structure

```
max_enchanted_gear/
├── pack.mcmeta
└── data/
    └── max_ench/
        └── function/
            ├── get_max_iron.mcfunction
            ├── get_max_diamond.mcfunction
            └── get_max_netherite.mcfunction
```

## How to Install & Use

1. Download or copy the data pack folder.
2. Place the `max_enchanted_gear` folder into your world's `datapacks` folder.
3. Open your world or run `/reload`.
4. Enable the data pack (if not auto-enabled):
   ```
   /datapack enable "file/max_enchanted_gear"
   ```
5. Use one of the following commands:

   - **Iron Set:**
     ```
     /function max_ench:get_max_iron
     ```

   - **Diamond Set:**
     ```
     /function max_ench:get_max_diamond
     ```

   - **Netherite Set:**
     ```
     /function max_ench:get_max_netherite
     ```


## Credits

- **Created:** 2026-04-11  
- **Last Updated:** 2026-04-11  
- **Original Author:** pixelThreader

Made with ❤️ for the Minecraft community.


Feel free to modify the functions or expand the pack. If you add new features, consider updating the version and credits!

**Enjoy your god gear!** ⚔️🛡️