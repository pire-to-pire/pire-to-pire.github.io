+++
author = "Pire-to-Pire"
title = "Ressources utiles pour des CTF"
date = "2024-04-17"
description = "Failles, sites d'entrainement, algos, ..."
tags = [
    "CTF",
    "ressources",
]
+++


## Sites d'entrainement
- [CryptoHack](https://cryptohack.org/) : Pour la crypto
- [Ozint](https://ozint.eu/) : Pour l'OSINT
- [RootMe](https://www.root-me.org/?lang=fr) : Généraliste

## Sites d'explication
- [CTF recipes](https://www.ctfrecipes.com/cryptography/reconnaissance)
- [The Hacker Recipes](https://www.thehacker.recipes/)
- [CryptoBook](https://cryptohack.gitbook.io/cryptobook) : En cours de construction

## Web
- [Injection Theory](https://owasp.org/www-community/Injection_Theory) : Injecter du code SQL dans une page Web
- [SSL Labs](https://www.ssllabs.com/ssl-pulse/) : Stats sur la sécurité des différentes versions du protocole SQL
- [TLS 1.3](https://tls13.xargs.org/) : Fonctionnement du protocole TLS 1.3
- [SSL Labs Test](https://www.ssllabs.com/ssltest/index.html) : Analyse de la configuration SSL d'un serveur
- [Firepwd](https://github.com/lclevy/firepwd) : Script Python pour cracker des mots de passe sur Mozilla

## RSA
- [Fonctionnement du RSA](https://leimao.github.io/article/RSA-Algorithm/)
- [Wiener's Attack](https://en.wikipedia.org/wiki/Wiener%27s_attack) : Trouver la clé privée lorsqu'elle est petite
- [Factor DB](http://factordb.com/) : Base de donnée de factorisation d'entiers. Disclaimer : Inutile pour progresser
- [Ron was wrong, Whit is right](https://eprint.iacr.org/2012/064.pdf) : Etude sur l'utilisation de certains nombres premiers plus fréquemment que d'autres pour le RSA
- [Twenty Years of Attacks on the RSA Cryptosystem](https://www.ams.org/notices/199902/boneh.pdf) : Récapitulatif des méthodes d'attaque contre le RSA
- [Cryptanalyse du RSA](https://repository.root-me.org/Cryptographie/FR%20-%20Cryptanalyse%20de%20RSA.pdf)

## Courbes elliptiques
- [Attacks on the Elliptic Curve Discrete Logarithm Problem](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=5f41de1a42882768c2511fee43b69f1ee5507882)
- [Cours de Stanford](https://web.archive.org/web/20220412170936/https://crypto.stanford.edu/pbc/notes/elliptic/)

## Encodage
- [Types d'encodage](https://repository.root-me.org/Cryptographie/EN%20-%20Encodings%20format.pdf) : Divers types d'encodage
- [Cyberchef](https://cyberchef.org/) : Convertir des chaines de caractère
- [Regex 101](https://regex101.com/) : Tester des Regex

## Hash
- [Hashcat](https://www.malekal.com/hashcat-cracker-des-hashs-empreintes-md5-sha1-sha256/)
- [Hashcat](https://hashcat.net/wiki/doku.php?id=example_hashes) : Exemple hashes
- Ma commande Hashcat : `hashcat64.exe --hwmon-temp-abort=100 --force -m $hashcode $hash -a 0 ./wordlists/rockyou.txt -o "result.txt"`
- [SecretsDump](https://medium.com/@benichmt1/secretsdump-demystified-bfd0f933dd9b) : Explication du fonctionnement de Secretsdump
- [The Hacker Recipes](https://www.thehacker.recipes/ad/movement/credentials/cracking) : Exemples et fonctionnement de Hashcat
- [WeakPass](https://weakpass.com/crack-js)

## Analyse d'image
- [Photo Forensics](https://29a.ch/photo-forensics/#forensic-magnifier)

## OSINT
- [Osint4All](https://start.me/p/L1rEYQ/osint4all?locale=fr) : Bibliothèque de ressources Osint
- [WhatsMyName](https://whatsmyname.app/) : Repère des usernames sur différents sites
- [BreachDirectory](https://breachdirectory.org/) : Trouve des leaks de données.