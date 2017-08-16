# cnc-scripts


Sammlung von Scripten für cnc ta


# Show Off/Def
anzeige von Off/Def der Spieler

Mit Tunnel Info die Anzeige bauen https://greasyfork.org/de/scripts/1900-tiberium-alliances-tunnel-info/code

Irgend ein anderes (welches?) kann die off/deff der spieler raus finden. Dieses Nutzen


#TODO
  
[] Die Roten Kästen auf die Spieler basen verschieben
  [] Alle(wie viele?) Spieler Basen finden
  [] bei jeder gefundenen rendern oder danach alle
  [] Deren Coords finden (Wie Tunnel)
  
[] Off anzeigen
[] Def Anzeigen
[] Support Anzeigen
[] Sup anzeigen
[] Warnung falls VE zu niedrig


[] Vorgabe von Off/Def kann in optionen gemacht werden! (https://greasyfork.org/de/scripts/24720-hardliner-feindinfo-tool/code optionpage)



Schritte 
Script lesen // Komentare rein
zweites Script finden

Fragen: 
Das Tunnel Script kann alle Tunnel in verlegee Range sehen. Das off/def kann diese Außerhalb sehen. Wie findet letztere dieses raus? 


Das MHTool hat eine load Base function, diese speichert in this.Data
calcFriendlyInfo nutzt diese für die Infos für  ['Base:','Defence:','Offence:','Support:'];
