# kaamelott-motd
Message Of The Day d'attente de Kaamelott le film.

## Installation : Debian et Ubuntu

Placer le script `99-kaamelot` dans le répertoire `/etc/update-motd.d` et le rendre exécutable :

    $ sudo wget /tmp https://raw.githubusercontent.com/berrydamien/kaamelott-motd/master/99-kaamelott -P /etc/update-motd.d
    $ sudo chmod +x /etc/update-motd.d/99-kaamelott

## Exemple

Lors de la prochaine connexion, le message : 

" Bientôt, Arthur sera de nouveau un héros ... XXX jours, XX heures, XX minutes, XX secondes. "

apparait dans votre Message Of The Day.

