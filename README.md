# racing_legue
https://login.ibm.com/authsvc/mtfim/sps/authsvc?PolicyId=urn:ibm:security:authentication:asf:basicldapuser&Target=https%3A%2F%2Flogin.ibm.com%2Foidc%2Fendpoint%2Fdefault%2Fauthorize%3FqsId%3D07962797-94ae-4dc0-be80-f1dd1543f630%26client_id%3DZTY0MDc5OGUtOTE3OC00

Na dysku C po konfiguracji powinny znajdować się 3 foldery:
- torcs
- torcs-env
- RaceYourCode\gym_torcs
Wrzuciłam na repo jedynie torcs_jar.py, która została już trochę ulepszona.

Po wykonaniu wszystkich kroków, edytujemy plik torcs_jm_par.py. 

Instrukcja uruchomienia wyścigu:
- włączamy wtorcs.exe w /torcs
- wybieramy nowy wyścig, practise, sc_server1, corkscrew
- następnie otwieramy PowerShella na dysku C i wykonujemy następujące komendy:
  - C:\torcs-env\Scripts\activate
  - cd C:\RaceYourCode\gym_torcs
  - python3 torcs_jm_par.py

W gimpie można zedytować grafikę auta, osobna instrukcja na stronie.


