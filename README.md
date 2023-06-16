<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

# ккАИ.арт

Део кода веб локације је отвореног кода, добродошли да помогнете у оптимизацији превода.

## фронт-енд код

* [фронт-енд код](https://github.com/xxai-art/web)
* [Језички пакети за сајт као целину](https://github.com/xxai-art/web/tree/main/i18n)
* [Језички пакети за модуле за пријаву](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Вишејезична документација веб странице](https://github.com/xxai-doc)

Фронт-енд програмски језик је [@в5/цоффее_плус](http://npmjs.com/@w5/coffee_plus) , који додаје неке функције засноване на кафескрипт синтакси, погледајте [./цоффее_плус.мд](./coffee_plus.md) .

## Интернационализација веб сајтова и докумената

Надоградите следећа 3 пројекта

* [@в5/мдт](https://www.npmjs.com/package/@w5/mdt)

  Суфикс је `.mdt` , можете користити синтаксу сличну `<+ ./coffee_plus/import.js>` за упућивање на спољне датотеке и генерисати маркдовн са суфиксом `.md` .

* [@в5/трмд](https://www.npmjs.com/package/@w5/trmd)

  Превод Маркдовн неће преводити кодове и везе, већ ће кеширати преведене реченице. Ако је превод измењен, али оригинални текст није измењен, његово поновно извршавање неће заменити измену превода.

* [@в5/и18н](https://www.npmjs.com/package/@w5/i18n)

  Језичке датотеке за превођење `yaml` генерисаних веб локација.
