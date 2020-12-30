1. Vérifier que le filtre (raw, date, ...) ou la fonction (path(), asset(), ...) n'existe pas nativement en appelant la liste `php bin/console debug:twig`
2. Créer une nouvelle classe par exemple `FilterExtension` avec `php bin/console make:twig FilterExtension`. Elle hérite de `AbstractExtension` les méthodes `getFilters() : array` et `getFuctions() : array`
