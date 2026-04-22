## Alterações feitas

- views.py: adicionados imports em falta (Dia, Concerto, get_object_or_404), completada concerto_view, adicionada palcos_view
- urls.py: adicionado path para dias/ que faltava
- dias.html: criado template em falta
- palcos.html: corrigido link dos concertos de href vazio para {% url %}
- index.html: corrigido posicionamento do {% load static %}
