# WorkFlow
## Zadání
* Entity (AuthorizationGQLModel, AuthorizationUserGQLMode, AuthorizationGroupGQLModel, AuthorizationRoleTypeGQLModel)
* Modely v databázi pomocí SQLAlchemy, API endpoint typu GraphQL s pomocí knihovny Strawberry.
* Přístup k databázi řešte důsledně přes AioDataloder, resp. (https://github.com/hrbolek/uoishelpers/blob/main/uoishelpers/dataloaders.py).
* Zabezpečte kompletní CRUD operace nad entitami ExternalIdModel, ExternalIdTypeModel, ExternalIdCategoryModel
* CUD operace jako návratový typ nejméně se třemi prvky id, msg a „entityresult“ (pojmenujte adekvátně podle dotčené entity), vhodné přidat možnost nadřízené entity, speciálně pro operaci D.
* Řešte autorizaci operací (permission classes).
* Kompletní CRUD dotazy na GQL v souboru externalids_queries.json (dictionary), jméno klíče nechť vhodně identifikuje operaci, hodnota je dictionary s klíči query (obsahuje parametrický dotaz) nebo mutation (obsahuje parametrické mutation) a variables (obsahuje dictionary jako testovací hodnoty).
* Kompletní popisy API v kódu (description u GQLModelů) a popisy DB vrstvy (comment u DBModelů).
* Zabezpečte více jak 90% code test coverage (standard pytest).
## Plán postupu
* 16.10. - příprava na 1. projektový den, vytvořený GitHub repository, zprovozněný Docker
* 23.10. - 26.11. - bližší seznámení s projektem, porozuměmní technikám, příprava na 2. projektový den, příprava RU operací
* 27.11. - prezentace postupu na 2. projektovém dnu
