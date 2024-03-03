# HenHacks
 class Person:
...     felon: bool
...     exonerated: bool
...     gun_permit: bool
...
>>> def can_purchase_gun(per: Person) -> bool:
...     if felon == True:
...             print("Criminally barred")
...             if exonerated == True:
...                     if gun_permit == True:
...                             print("Can purchase gun")
...             else:
...                     print("Not enough training")
...
>>> print(["Walmart", "Gun Store", "Dick's Sporting Goods"][1])
Gun Store
>>> class Serial_number:
...     number: bool
...
>>> def properly_purchased(ser: Serial_number) -> bool:
...     if Serial_number == True:
...             print("Properly purchased gun")
...     else:
...             print("Improperly purchased")
...
>>> print(["AK-47", "Pistol", "AR-15", "Assault Weapons"][1])
Pistol
>>> def number_of_guns(firearms: int) -> bool:
...     if firearms >= 200000000:
...             print("institute buyback program")
...
>>> class Gun_owner:
...     years_experience: int
...     safe_with_guns: bool
...
>>> def gun_safety(gun: Gun_owner) -> bool:
...     if years_experience > 5:
...             if safe_with_guns == True:
...                     print("Trusted with guns")
...             else:
...                     print("Experienced but not trustworthy")
...     else:
...             print("Not trustworthy and not experienced")
...
>>> from collections import Counter
>>> #Top ten states by gun violence
>>> A = "Mississippi"
>>> B = "Louisiana"
>>> C = "New Mexico"
>>> D = "Alabama"
>>> E = "Wyoming"
>>> F = "Alaska"
>>> G = "Montana"
>>> H = "Arkansas"
>>> I = "Missouri"
>>> J = "Tennessee"
>>> def gun_violence(state: str) -> int:
...     print(Counter(state[A, B, C, D, E, F, G, H, I, J]))
...
>>> message = "We need change!"
>>> print(message)
We need change!
>>>











