# Check_my_city

Introduces: dict.
Author(s): @c24b.

## Instructions

Here is a list of different velib's stations stored in a dictionnary.
Write a function check_my_city that take a city name in parameter.
This functions check the number of stations available. If nothing is
found it should return: "Sorry! No station for your city has been
found!", otherwise it returns the number of the station with the
associated zip codes. See example to write the proper format.

```python


velib = \
[{  'address': 'RUE DES CHAMPEAUX (PRES DE LA GARE ROUTIERE) - 93170 BAGNOLET',
        'zip': '93170-,
        'number': 31705, 'latitude': 48.8645278209514, 'city': 'BAGNOLET',
        'name': 'CHAMPEAUX (BAGNOLET)-,
        'longitude': 2.416170724425901
    },
    {   'address': "52 RUE D'ENGHIEN / ANGLE RUE DU FAUBOURG POISSONIERE - 75010 PARIS", 
        'zip': '75010',
        'number': 10042, 'latitude': 48.87242006305313, 'city': 'PARIS-,
        'name': 'ENGHIEN-,
        'longitude': 2.348395236282807
    },
    {
        'address': '74 BOULEVARD DES BATIGNOLLES - 75008 PARIS-,
        'zip': '75008-,
        'number': 8020, 'latitude': 48.882148945631904, 'city': 'PARIS-,
        'name': 'METRO ROME-,
        'longitude': 2.319860054774211
    },
    {   'address': '37 RUE CASANOVA - 75001 PARIS-,
        'zip': '75001-,
        'number': 1022, 'latitude': 48.8682170167744, 'city': 'PARIS-,
        'name': 'RUE DE LA PAIX-,
        'longitude': 2.330493511399174
    },
    {
        'address': '139 AVENUE JEAN LOLIVE / MAIL CHARLES DE GAULLE - 93500 PANTIN-,
        'zip': '93500-,
        'number': 35014, 
        'latitude': 48.893268664697416, 
        'city': 'PANTIN-,
        'name': 'DE GAULLE (PANTIN)-,
        'longitude': 2.412715733388685
    }
]

```

## Advice

Check the join() function
Be ***very*** careful of the output format. 
"The devil is in the details". 
Check, check and re-check!

##Example

```python 

def check_my_city(city_name):
    if ...
        return "Sorry! No station for your city has been found!"
    else:
        ...
        #here it's obviously an example to give you an idea!
        return {"stations_nb": 2, 
                "zip_code": ['93170', '93320'],
                "city": 'pantin'}
