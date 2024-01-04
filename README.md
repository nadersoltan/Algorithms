# Algorithms

 ALGORITHM phrase
    VAR phrase: STRING
    BEGIN
    écrire: ('phrase:')
    lire: phrase se terminant par un point
    écrire:(votre phrase est: phrase se terminant par point)
    END

    ALGORITHM phrase
    VAR
        phrase,phrase se terminant par un point: STRING
    BEGIN
    écrire:('phrase:')
    lire: phrase
    phrase se terminant par un point<= phrase & ' '
        écrire(phrase se terminant par un point est:',phrase se terminant par un point)
    END

ALGORITHM nbr_de_lettres
    VAR
    phrase:STRING
    nbr: INTEGER
    BEGIN
    écrire:('phrase se terminant par point:')
    lire:(phrase)
    nbr<= longueur (phrase)
    écrire: ('votre phrase contient ',nbr,' STRING')
    END
