from random import randint

def évolution_points_vie(points_vie, défense, val_min_attaque, val_max_attaque, nb_combats):
    assert isinstance(points_vie, int) and points_vie > 0
    assert isinstance(défense, int) and défense > 0
    assert isinstance(val_min_attaque, int) and val_min_attaque > 0
    assert isinstance(val_max_attaque, int) and val_max_attaque > 0
    assert val_min_attaque < val_max_attaque
    assert isinstance(nb_combats, int) and nb_combats > 0
    liste_points_vie = [points_vie]
    for i in range():
        attaque = randint(val_min_attaque , val_max_attaque)
        if attaque > défense:
            points_vie  -= attaque-défense
        else:
            points_vie += attque // 2 
        liste_points_vie.append(points_vie)
        if points_vie <= 0 :
            return liste_points_v
    return liste_points_v
