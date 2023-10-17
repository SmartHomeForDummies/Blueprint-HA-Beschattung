# Rollladen Steuerung
Stueurung des Rolladen in Abhängigkeit von Sonnenaufgang und Sonnenuntergang.
Berücksichtung einer Urzeit, wann frühstens der Rollladen geöffnet werden darf.
Zusätzlich kann ein Fenster Sensor berücksichtig werden.
Wird das Fenster geöffnet oder ist bereits geöffnet, wenn der Rollladen planmässig
geschlossen werden soll, fährt der Rollladen in die vorgegebene Position (Lüftungs-Stellung).
  # Voraussetzungen:
  - Cover: Eine Cover Entität (Rollladen/Lalousie)
  - Fenster Sensor: Fenster-Kontakt (binary_sensor) - Optional

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FSmartHomeForDummies%2FBlueprint-HA-Beschattung%2Fblob%2Fmain%2FRollladen_Steuerung.yaml)

-------
