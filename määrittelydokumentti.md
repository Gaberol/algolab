# Algoritmiprojekti aiheesta kartan generointi
Toteutettava ohjelma luo dynaamisesti kolmiuloitteisia maastokarttoja. Käytetty kieli on Python ja voin arvioida muita tämän kurssin porjekteja sillä kielellä toteutettuina.

Maastojen luomista varten tullaan käyttämään *Marching cubes*-algoritmia yhdistettynä jonkinlaiseen satunnaiseen kohinaan, jotta ohjelma ei tarvitse käyttäjältä syötettä maaston muodon määrittämiseen. Ohjelman luomat kartat tuovat pääasiassa viihdearvoa, sillä niistä voidaan luoda esteettisesti miellyttäviä.

Koska algoritmi generoi karttaa reaaliajassa, tulee kartan kokoa rajoittaa tietylle alueelle katselijan ympärille, jotta ajan ja tilan käyttö pysyisi kohtuullisena.
