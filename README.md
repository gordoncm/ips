classDiagram
    class Author {
        <<Entity>>
        + int ID
    }

    class Book {
        <<Entity>>
        + int ID
    }

    class AuthorBookRelation {
        <<Association>>
        + int AuthorID
        + int BookID
    }
