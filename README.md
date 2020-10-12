# Osiris 

Cheat gratuito open-source para CS:GO.

## Perguntas Frequentes

### Como eu abro o menu?
Aperte <kbd>INSERT</kbd> quando estiver dentro do jogo.

### Onde fica a pasta de configs
As configs ficam salvas na pasta `Osiris` que fica na aba dos `Documentos` --> (`%USERPROFILE%\Documentos\Osiris`).

### What hooking methods Osiris uses?
Currently implemented hooking methods are:
- MinHook - trampoline hook
- VmtHook - hook a function directly in a vtable
- VmtSwap - create a copy of a vtable and swap the pointer on the class instance

Hooking implementation files are located in [Hooks](https://github.com/danielkrupinski/Osiris/tree/master/Osiris/Hooks) directory.

## Acknowledgments

* [ocornut](https://github.com/ocornut) and [contributors](https://github.com/ocornut/imgui/graphs/contributors) for creating and maintaining an amazing GUI library - [Dear imgui](https://github.com/ocornut/imgui).
* [Zer0Mem0ry](https://github.com/Zer0Mem0ry) - for great tutorials on reverse engineering and game hacking

## License

> Copyright (c) 2018-2020 Daniel Krupiński

This project is licensed under the [MIT License](https://opensource.org/licenses/mit-license.php) - see the [LICENSE](https://github.com/danielkrupinski/Osiris/blob/master/LICENSE) file for details.

## See also
- [Anubis](https://github.com/danielkrupinski/Anubis) - free and open source cheat for CS:GO with configuration compatible with Osiris
- [GOESP](https://github.com/danielkrupinski/GOESP) - free and open source cross-platform streamproof ESP hack for Counter-Strike: Global Offensive, written in modern C++
