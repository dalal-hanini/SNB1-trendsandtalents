# SNB1-trendsandtalents
Een recente Python oefening voor het vak Scripting with Python.


personen = [
    'robert downey jr.', 'chris evans', 'chris hemsworth',
    'pedro pascal', 'paul rudd', 'anthony mackie',
    'florence pugh', 'vanessa kirby', 'ebon moss-bachrach',
    'wyatt russell', 'channing tatum', 'simu liu',
    'ian mckellen', 'tom hiddleston', 'james marsden',
    'patrick stewart', 'joseph quinn', 'sebastian stan',
    'david harbour', 'letitia wright'
]

for persoon in personen:
    naam = persoon.split(" ", 1)
    voornaam = naam[0].capitalize()
    achternaam = naam[1].upper()
    print(f"Voornaam: {voornaam}, Achternaam: {achternaam}")



