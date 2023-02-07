# Conjunto-e-subconjunto.py
Conjunto e subconjunto de elementos em python.



conjunto = {1,2,3,4,5}
conjunto2 = {5,6,7,8}
conjunto_uniao = conjunto.union(conjunto2)
print('união: {}' .format(conjunto_uniao))
conjunto_interseccao = conjunto.intersection(conjunto2)
print('intersecção: {}' .format(conjunto_interseccao))
conjunto_diferenca = conjunto.difference(conjunto2)
conjunto_diferenca2 = conjunto2.difference(conjunto)
print('diferencia entre 1 e 2: {}' .format(conjunto_diferenca))
print('diferencia entre 2 e 1: {}' .format(conjunto_diferenca2))
conjunto_diff_simetrica = conjunto.symmetric_difference(conjunto2)
print('Diferença simétrica: {}' .format(conjunto_diff_simetrica))


conjunto_a = {1, 2, 3}
conjunto_b = {1,2,3,4,5}
conjunto_subset = conjunto_a.issubset(conjunto_b)
print('A é subconjunto de B: {}' .format(conjunto_subset))
conjunto_superset = conjunto_b.issuperset(conjunto_a)
print('B é um suoerconjunto de A: {}' .format(conjunto_superset))

lista = ['cachorro', 'cachorro', 'gato', 'elefante']
conjunto_animais = set(lista)
print(conjunto_animais)
lista_animais = list(conjunto_animais)
print(lista_animais)


# conjunto = {1,2,3,4}
# conjunto.add(5)
# conjunto.discard(2)
# print(conjunto)
