# Diagrama mermaid

## Entitat personatge
L'entitat personatge bblaklkajdlkjfadlkfjdas
adsflkajdsflakdsjfalkdsj
adfalksdjfadslkfjdsa

``` mermaid
erDiagram
    PERSONATGE{
            string DNI PK
            string Nom "NOT NULL"
            string Cognom
            int Vida
            int Força
            int Agilitat
            int Carisma
        }
```
faslfdasñlfkadsñlfjasdlkfjadsadsflkajsdfdl
lkasdjfadñslkfjasdlkf
laksdjfañsldkfjasdñlkfjasdñlfkajsdflkñaj

## Diagrama sencer

``` mermaid
erDiagram
    PERSONATGE{
        string DNI PK
        string Nom "NOT NULL"
        string Cognom
        int Vida
        int Força
        int Agilitat
        int Carisma
    }

    MASCOTA{
        string NumChip PK
        string Nom "NOT NULL"
        int Motxilla
    }

    PERSONATGE || -- || MASCOTA : acompanya
```
