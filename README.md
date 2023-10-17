# Rollladen Steuerung
Stueurung des Rolladen in Abhängigkeit von Sonnenaufgang und Sonnenuntergang.
Berücksichtung einer Urzeit, wann frühstens der Rollladen geöffnet werden darf.
Zusätzlich kann ein Fenster Sensor berücksichtig werden.
Wird das Fenster geöffnet oder ist bereits geöffnet, wenn der Rollladen planmässig
geschlossen werden soll, fährt der Rollladen in die vorgegebene Position (Lüftungs-Stellung).
  # Voraussetzungen:
  - Cover: Eine Cover Entität (Rollladen/Lalousie)
  - Fenster Sensor: Fenster-Kontakt (binary_sensor) - Optional
