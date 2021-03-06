# Базовые битриксовые компоненты

Сборка базовых битриксовых компонетов (ББК) ускоряет разработку, предоставляя, при этом, дополнительные, не присущие 
ни одному штатному компоненту «1С-Битрикса», возможности.

Используя ББК, вы сконцентрируетесь на основной логике компонента. Проверку и привидение параметров, установку 
заголовков, тегов, постраничной навигации, обработку аякс-запросов, перехват ошибок — обо всём этом и многом другом 
позаботится ББК.

## Требования

* PHP >= 5.4.0
* Bitrix CMS >= 15.0.2

## Зависимости

Данный репозиторий содержит в себе примеры компонентов. Бизнес-логика же ББК реализована в модуле 
[bex.bbc](https://github.com/bitrix-expert/bbc-module), который автоматически установится в качестве зависимости 
«Композера». 

## [Документация](http://bbc.bitrix.expert)