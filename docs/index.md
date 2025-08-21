# Doick's Union Workshop

**Doick's Union Workshop (DUW)** is a comprehensive suite of Union plugins designed to extend and enhance the functionality of Gothic games. This project provides new external functions and practical hooks, enabling modders to modify and expand game mechanics with ease. The documentation offers descriptions of available features, usage examples, and integration guidelines for your own projects.

All plugins were built using the new [Union API](https://gitlab.com/union-framework/union-api) and can be embedded either as a Union 1.0m plugin or as a completely standalone plugin for base Gothic with System Pack.

DUW aims to support the Gothic modding community by delivering reliable, flexible, and well-documented tools for mod development.

## Project structure

DUW is divided into three main modules:

- **[Externals](https://github.com/Doick-Union-Workshop/zDExternals)** – additional API functions for the Gothic engine, allowing modders to directly interact with game systems and extend their behavior.  
- **[Hooks](https://github.com/Doick-Union-Workshop/zDHooks)** – event-based extensions that let you override or expand vanilla mechanics by injecting custom logic at specific points in the engine.  
- **Dev Tools** – helper utilities designed for debugging, testing, and supporting development workflows during mod creation.

## Authors

The project began in 2023 and was intended to be not only a toolset, but also a way to learn and experiment with the C++ language and Union plugin development. The goals included simplifying usage, avoiding the need to rely on zParserExtender API injectable scripts in `Autorun`, and ensuring that externals and features work properly outside of that directory.

DUW is inspired by [AF Script Packet](https://github.com/Bad-Scientists/AF-Script-Packet) (AFSP) by [Auronen](https://github.com/auronen) and [Fawkes](https://github.com/Fawkes-dev) based on [Ikarus](https://github.com/Lehona/Ikarus) and [LeGo](https://github.com/Lehona/LeGo) libraries. The developers once mentioned that there were plans for a Union version, but it has not been created yet. This project continues that idea, based on the work of [Bad Scientists](https://github.com/Bad-Scientists) and exploring first the old and now the new Union APIs.

The project is maintained by [Doick](https://github.com/doick):

- Discord: [@doic](https://discordapp.com/users/219766962312577024)

![DUW contributors](https://contrib.nn.ci/api?repo=Doick-Union-Workshop/zDDocs)

## License

DUW plugins depends on [Union API](https://gitlab.com/union-framework/union-api) and [Gothic API](https://gitlab.com/union-framework/gothic-api) libraries, which are licensed under [BSD 3-Clause license](https://gitlab.com/union-framework/union-api/-/blob/main/LICENSE).

zDExternals uses [BetterDaedalusExternals](https://github.com/bogu9821/BetterDaedalusExternals), which is licensed under [MIT license](https://github.com/bogu9821/BetterDaedalusExternals/blob/main/LICENSE).

zDHooks uses [DaedalusCall](https://github.com/bogu9821/DaedalusCall), which is licensed under [MIT license](https://github.com/bogu9821/DaedalusCall/blob/main/LICENSE).
