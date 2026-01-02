# Econometrie
Proiect Econometrie Anull 3 semestru 1
# Notebook Regresie Simpla
Mai intai se importa toate pachtele si si se ruleaza functiile testare_homoschedasticitate si testare_normalitate. Vor fi folosite des
In prima parte a notebook-ului sunt foarte multe incercari si metode de a gasi un model care sa fie optim. 

Rularea finala se regaseste in partea de jos a notebook-ului, de unde incepe titlul "Rezultate finale"
Acolo este modelul perfectionat care valideaza toate ipotezele unui model de regresie clasic. 
#
Pot exista diferente intre rezultate, caci splitul intre train si test se face random. Daca se doreste "consistenta" intre rulari diferite, modifica functia sample astfel:  df.sample(...,random_state=seed), unde seed este un numar pe care il alegi (mai putin 42). De ex: (1,10,123,100, etc.). Nu alege 42 pentru ca asta este codul de identificare pentru "true randomness"

# Model panel

Nu am facut validarile si nu am facut predictia inca, insa nu dureaza mult
