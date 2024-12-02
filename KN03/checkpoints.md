
1. **Was ist `sudo` und wofür wird es verwendet?**  
   `sudo` erlaubt die Ausführung von Befehlen mit Administratorrechten.

2. **Wie installiert man Pakete mit `apt`?**  
   Mit dem Befehl `sudo apt install <paketname>`.

3. **Welche Pakete installieren `apache2`, `php` und `mariadb-server`, und was machen sie?**
    - `apache2`: Webserver, um Webseiten bereitzustellen.
    - `php`: Skriptsprache für dynamische Webseiten.
    - `mariadb-server`: Datenbank-Server für die Speicherung von Daten.

4. **Warum werden `libapache2-mod-php` und `php-mysqli` benötigt?**
    - `libapache2-mod-php`: Bindet PHP in Apache ein, damit PHP-Skripte ausgeführt werden können.
    - `php-mysqli`: Ermöglicht PHP, mit MySQL/MariaDB zu kommunizieren.

5. **Was sind Sicherheitsgruppen und wie können sie geändert werden?**  
   Sicherheitsgruppen definieren Netzwerkrichtlinien. Regeln können geändert werden, um Ports zu öffnen oder Zugriffe einzuschränken.

6. **Was ist ein Port und wie macht man ihn öffentlich zugänglich?**  
   Ein Port ist ein Kommunikationskanal. Man öffnet ihn durch Regeln in der Sicherheitsgruppe, z. B. für HTTP (Port 80).

7. **Wie benutzt man die MySQL-Konsole?**  
   Mit `mysql -u <user> -p` kann man sich einloggen und SQL-Befehle ausführen.

8. **Wie verwaltet man Dienste mit `systemctl`?**  
   Mit Befehlen wie `systemctl start/stop/restart/status <service>`.

9. **Wie kopiert man Dateien oder Ordner mit `cp`?**  
   Mit `cp <quelle> <ziel>`; für Ordner mit `cp -r <quelle> <ziel>`.
