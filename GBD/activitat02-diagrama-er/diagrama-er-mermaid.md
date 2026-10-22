# Diagrama mermaid

``` mermaid
erDiagram
    personatge }o--o{ item : equipa
    item }o--o{ mascota : carrega
    personatge |o--|| mascota : acompanya
    personatge }o--o{ enemic : enfrenta
    personatge }o--o{ habilitat : posseix
    habilitat }o--o{ enemic : enfrenta
    habilitat }o--o{ habilitat : combina_amb

    personatge {
        string dni PK
        string nom "NOT NULL"
        string cognom
        int vida
        int forca
        int agilitat
        int carisma
    }
    item {
        string codi PK
        string nom "NOT NULL"
        boolean equipable
        boolean comerciable "NOT NULL"
        string tipus "NOT NULL"
        float pes "NOT NULL"
        string qualitat "NOT NULL"
        float mesures-x
        float mesures-y
        float mesures-y
    }
    mascota {
        string num_chip PK
        string nom "NOT NULL"
        boolean motxilla
    }

    enemic {
        string codi PK
        string nom "NOT NULL"
        string tipus "NOT NULL"
        int nivell "NOT NULL"
        int vida
        int forca
        int agilitat
        int carisma
    }
    habilitat {
        string codi PK
        string nom "NOT NULL"
        int cost
        int dany
        float cooldown
        string tipus "NOT NULL"
    }
```
