#new section

to add new section, add it to collection and then set defaults for all languages, for example for team.

```
collections:
    team:
    
defaults:
  - scope:
      path: _team/en
      type: team
    values:
      lang: en
  - scope:
      path: _team/de
      type: team
    values:
      lang: de
  - scope:
      path: _team/lt
      type: team
    values:
      lang: lt
```    
