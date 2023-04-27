Ziel: Implementiere eine benutzerdefinierte iterable-Klasse, um eine Liste von Social-Media-Beiträgen basierend auf bestimmten Kriterien zu filtern und zu durchlaufen.

Beschreibung:

Du hast eine Liste von Social-Media-Beiträgen als Objekte erhalten. Jedes Post-Objekt enthält einen Benutzernamen, eine Nachricht und die Anzahl der Likes, die es erhalten hat. Deine Aufgabe besteht darin, eine benutzerdefinierte iterable-Klasse namens "FilteredPosts" zu erstellen, die die Liste der Beiträge basierend auf bestimmten Kriterien filtert und durchläuft.

Anleitung:
    Erstelle eine Klasse namens "Post" mit den folgenden Eigenschaften:
        String "username"
        String "message"
        int "likes"
    Implementiere die Klasse "FilteredPosts", die das "Iterable<Post>"-Interface implementiert.
        Die Klasse sollte einen Konstruktor haben, der eine Liste von "Post"-Objekten und eine Mindestanzahl von Likes als Parameter annimmt.
        Die Klasse sollte die "iterator()" Methode implementieren, die eine Instanz eines benutzerdefinierten Iterators zurückgibt.

    Implementiere eine benutzerdefinierte Iterator-Klasse namens "FilteredPostsIterator", die das "Iterator<Post>"-Interface implementiert.
        Die Klasse sollte einen Konstruktor haben, der eine Liste von "Post"-Objekten und eine Mindestanzahl von Likes als Parameter annimmt.
        Die Klasse sollte die Methoden "hasNext()" und "next()" implementieren.
        Die Methode "hasNext()" sollte "true" zurückgeben, wenn es weitere Beiträge mit der angegebenen Mindestanzahl von Likes in der Liste gibt, und "false" sonst.
        Die Methode "next()" sollte den nächsten Beitrag mit der angegebenen Mindestanzahl von Likes in der Liste zurückgeben

    Erstelle in der "main"-Methode eine Liste von Beispiel-Post-Objekten mit verschiedenen Benutzernamen, Nachrichten und Likes. 
    Erstelle dann eine Instanz der "FilteredPosts"-Klasse mit der Liste von Beiträgen und einer angegebenen Mindestanzahl von Likes. 
    Durchlaufe die gefilterten Beiträge mit einer for-each-Schleife und gib die Beiträge aus, die den Kriterien entsprechen.
