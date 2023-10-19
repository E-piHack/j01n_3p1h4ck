Log Lurker:

    Description: Un serveur web a récemment été victime d'une activité suspecte. Vous disposez d'un fichier de log de ce serveur. Analysez-le pour trouver l'adresse IP et l'action suspecte.
    Entrée suspecte dans le fichier de log : 192.168.1.23 - [10/Oct/2023:13:15:20 +0000] "GET /admin_backup.zip HTTP/1.1" 200 12345
    Flag basé sur cette entrée : EPI{SuspiciousDownload}