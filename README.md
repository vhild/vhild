# Freelancer Viktor Hildebrand
## Persönliche Daten
   **Name:** Viktor Hildebrand  
   **Adresse:** Struthweg 16, 57578 Elkenroth  
   **Geburtsdatum:** 13.09.1984  
   **Tel:** +49 171 / 6015233  
   **E-Mail:** [viktor@hildebrand.software](mailto:viktor@hildebrand.software)  
   **Website:** [https://hildebrand.software](https://hildebrand.software)

## Fachliche Kenntnisse
* **Programmiersprachen:** `C` `MISRA-C:2012` `C++` `Python` `Java`
* **Mikrocontroller:** `Microchip` `Renesas` `NXP` `STM` `TI` `Infineon` `ARM`
* **Kommunikationsschnittstellen:** `CAN` `LIN` `USB` `UART` `SPI` `I²C` `1-Wire` `Ethernet` `Bluetooth`
* **Plattformen:** `Embedded-Systeme` `Maschinensteuerung` `Windows` `Linux`
* **Test:** `SonarQube` `VectorCAST` `PC-Lint` `CppCheck` `GoogleTest` `Python-Unittest` `PyTest`
* **Architektur:** `Rhapsody` `Cameo`
* **Versionskontrolle:** `Git` `SVN`
* **Verwaltung:** `Jira` `Polarion`
* **CI:** `GitLab` `CMake` `Conda`
* **Dokumentation:** `Doxygen` `MkDocs` `LaTeX`
* **Office:** `MS Office` `LibreOffice`

## Ausbildung
* **2004-09 - 2010-01:** Universität Siegen  
  Studiengang: Angewandte Informatik - Anwendungsfach Elektrotechnik  
  Diplomarbeit: Bulk-Transfer und Firmware-Update über PLC-Netze  
  Gesamtnote Hauptstudium (D II): 1,5

* **2001-08 - 2003-07:** Berufsbildende Schule Betzdorf/Kirchen  
  Höhere Berufsfachschule für Informatik  
  Schwerpunkt Technische Informatik und Automatisierungstechnik

## Werdegang
### Freiberuflicher Softwareentwickler (seit 2020)
* **2021-03 - 2025-12:** Miele & Cie. KG in Gütersloh
* **2022-12 - 2023-10:** Thomas Magnete GmbH in Herdorf
* **2020-10 - 2022-05:** ROTH + WEBER GmbH in Niederdreisbach
* **2020-01 - 2020-10:** Rohde & Schwarz SIT GmbH in Stuttgart

### Festanstellung
* **2016-08 - 2019-12:** Thomas Magnete GmbH in Herdorf als Softwareentwickler
* **2010-02 - 2016-07:** ROTH + WEBER GmbH in Niederdreisbach als Softwareentwickler

### Studium
* **2009-09 - 2009-11:** Renesas Technology Europe GmbH als Diplomant
* **2006-01 - 2010-01:** ROTH + WEBER GmbH in Niederdreisbach als Werkstudent

## Weiterbildungen
* **2019-11:** Willert UML Follow-Up Training
* **2019-09:** ISTQB Certified Tester Foundation Level
* **2019-09:** Jira Basic Training
* **2019-02:** Vector UDS Diagnose & Candela Studio
* **2018-08:** Willert UML Start-Up Training
* **2018-03:** VectorCAST C/C++ QuickStart Training
* **2017-08:** Polarion Basic Training
* **2016-09:** Functional Safety ISO26262 - System, Hardware & Software
* **2007-09:** Xilinx Professional VHDL

## Zulassungen
* **2020:** Ü2-Sicherheitsüberprüfung

## Sprachen
* **Deutsch:** Muttersprache
* **Englisch:** Verhandlungssicher

## Projekte

### 2025-06 - 2025-12 | Miele
Entwicklung von Embedded-Software für das Funktionsmuster eines Haushaltsgeräts.

#### Aufgaben:
* Neuentwicklung von Software-Komponenten in C++
* Implementierung einer REST-Schnittstelle zur Gerätekonfiguration
* Erstellung von Unit-Tests unter Verwendung von GoogleTest
* Kontinuierliche Überwachung der Softwarequalität mit SonarQube

#### Hardware:
* MCU: STM32U575 & Renesas RA6M3 mit EmbOS

#### Tools:
* IDE: Visual Studio Code
* Projektverwaltung: GitLab
* Statische Code-Analyse: SonarQube
* Test-Framework: GoogleTest & PyTest

---

### 2024-06 - 2025-05 | Miele
Entwicklung von Embedded-Software für ein Haushaltsgerät mit Cloud-Anbindung & App-Bedienung.

#### Aufgaben:
* Neuentwicklung von Software-Komponenten in C++
* Einbindung eines Kamera-Treibers für die Bildaufnahme des Innenraums
* Erweiterung der Cloud-Anbindung u.a. für Bild-Upload
* Erstellung von Unit-Tests unter Verwendung von GoogleTest
* Realisierung von Integrationstests mit PyTest
* Kontinuierliche Überwachung der Softwarequalität mit SonarQube

#### Hardware:
* MCU: STM32U575 mit EmbOS
* ARM Cortex-M7 mit Embedded Linux

#### Tools:
* IDE: Visual Studio
* Projektverwaltung: GitLab
* Statische Code-Analyse: SonarQube
* Test-Framework: GoogleTest & PyTest

---

### 2022-12 - 2023-10 | Thomas Magnete
Entwicklung von Embedded-Software für einen Ventilansteuerungs-Prototypen mit LIN-Interface.

#### Aufgaben:
* Ausbau der bestehenden Software-Architektur in Rhapsody
* Umsetzung der Ventilsteuerung als Zustandsautomat (State Machine) in Rhapsody
* Entwicklung eines LIN-Stacks zur Kommunikation mit der PLIN-LDF-Testumgebung
* Integration und Inbetriebnahme des Built-in-Bootstrap-Loaders

#### Hardware:
* MCU: Infineon TLE9867

#### Tools:
* IDE: Keil µVision5
* Projektverwaltung: GitLab
* Architektur: Rhapsody Architect
* CAN-Adapter: PEAK PLIN-USB

---

### 2022-09 - 2024-06 | Miele
Entwicklung von Embedded-Software für eine Bluetooth-Fernbedienung.

#### Aufgaben:
* Konzeption und Erstellung der Software-Architektur in Cameo
* Entwicklung von Software-Komponenten in C für die Kernfunktionen der Fernbedienung
* Realisierung der Bluetooth-Datenübertragung
* Anbindung und Test eines externen Bluetooth-Kommunikationsmoduls
* Sicherstellung der Code-Qualität durch Überwachung in SonarQube

#### Hardware:
* MCU: TI CC2651R3SIPA

#### Tools:
* IDE: Code Composer Studio
* Projektverwaltung: GitLab
* Architektur: Cameo Systems Modeler
* Statische Code-Analyse: SonarQube

---

### 2021-03 - 2024-06 | Miele
Entwicklung von Embedded-Software für ein Haushaltsgerät mit Cloud-Anbindung & App-Bedienung.

#### Aufgaben:
* Entwurf der Software-Architektur in Cameo
* Einbindung von Plattform-Software-Komponenten (u.a. EmbOS-Betriebssystem)
* Integration und Validierung eines externen Kommunikationsmoduls (WLAN & Bluetooth)
* Neuentwicklung von C++-Komponenten für die Steuerungs-Software
* Umsetzung der Cloud-Anbindung in C++
* Kontinuierliche Qualitätssicherung mittels SonarQube

#### Hardware:
* MCU: STM32L496 / STM32U575

#### Tools:
* IDE: Visual Studio
* Projektverwaltung: GitLab
* Architektur: Cameo Systems Modeler
* Statische Code-Analyse: SonarQube

---

### 2020-10 - 2022-05 | ROTH + WEBER
Entwicklung von Embedded-Software für ein Farbdruckersystem und Einführung einer Unit-Testumgebung für die Windows-Entwicklungsumgebung und CI-Build-Umgebung.

#### Aufgaben:
* Entwicklung von Software-Modulen in C für das Farbdruckersystem
* Aufbau einer Unit-Testumgebung auf Basis von CMake & GoogleTest
* Einbindung der automatisierten Tests in die GitLab-CI-Pipeline

#### Hardware:
* MCU: NXP LPC178x

#### Tools:
* IDE: LPCXpresso IDE
* Projektverwaltung: GitLab
* Test-Framework: GoogleTest

---

### 2020-01 - 2020-10 | Rohde & Schwarz SIT
Test einer Embedded-Kryptomodul-Software eines Funkgeräts auf Integrationsebene und Weiterentwicklung der vorhandenen Testumgebung.

#### Aufgaben:
* Spezifikation von Testfällen für Integrationstests in Python und XML
* Entwicklung eines Test-Adapters in C++ auf Basis von Apache Thrift
* Portierung und Einbindung einer C-Bibliothek in die Python-Testumgebung
* Automatisierte Erstellung von Testreports mittels LaTeX
* Integration der Testausführung in die GitLab-CI-Pipeline

#### Hardware:
* MCU: NXP i.MX8 ARM
* OS: Embedded Linux

#### Tools:
* IDE: Eclipse
* Projektverwaltung: GitLab & Jira
* Test-Framework: Python-Unittest
* Test-Report: LaTeX

---

### 2018-07 - 2019-12 | Thomas Magnete
Entwicklung von Embedded-Software mit CAN-Interface zur Ansteuerung eines Schrittmotors.

#### Aufgaben:
* Berücksichtigung der funktionalen Sicherheit nach ISO 26262
* Definition von Systemanforderungen und Erstellung von Testspezifikationen
* Anpassung der MCAL-Module (Microcontroller Abstraction Layer)
* Realisierung der Schrittmotoransteuerung (Stromregelung, Positionsregelung, Geschwindigkeitssteuerung) in MISRA-C:2012
* Umsetzung von sicherheitsrelevanten Funktionen
* Technische Betreuung eines externen Dienstleisters bei der Entwicklung eines 2-stufigen UDS-Bootloaders

#### Hardware:
* MCU: Microchip dsPIC33CH128MP505
* Treiber: TI DRV8703

#### Tools:
* IDE: MPLAB X + PICkit 3
* Anforderungsmanagement: Polarion ALM
* Test-Framework: VectorCAST
* Konfiguration: EB tresos
* Architektur: Rhapsody Architect
* UDS-Flasher: Vector vFlash
* CAN-Adapter: PEAK PCAN-USB & Vector VN1610

---

### 2017-02 - 2017-04 | Thomas Magnete
Entwicklung von Embedded-Software für ein UART-Multiplexer-System.

#### Aufgaben:
* Entwurf der Software-Architektur
* Entwicklung eines UART-Moduls zur Kommunikation mit einer SPS-Steuerung
* Implementierung eines SPI-Moduls zum Zugriff auf 5 externe MAX14830-ICs

#### Hardware:
* MCU: Atmel ATxmega32E5
* Peripherie: Maxim MAX14830

#### Tools:
* IDE: Atmel Studio + Atmel-ICE

---

### 2016-08 - 2018-06 | Thomas Magnete
Entwicklung einer universellen Build-Toolchain für Embedded-Software-Projekte in Python.

#### Funktionsumfang der Toolchain:
* Analyse der Code-Formatierung und Einhaltung von Namenskonventionen
* Durchführung von statischer Code-Analyse und MISRA-C:2012-Prüfungen
* Automatisierung der Unit-Test-Ausführung
* Automatische Generierung der Projektdokumentation aus dem Quellcode
* Steuerung des Kompilierungsprozesses der Embedded-Software
* Sicherstellung der Lauffähigkeit auf Build-Servern und Entwickler-PCs

#### Tools:
* Formatierung: LLVM Clang
* Statische Code-Analyse: PC-Lint & CppCheck
* Test-Framework: VectorCAST
* Projektdokumentation: Doxygen
* Standard-Compiler: MinGW
* Build-Umgebung: Jenkins

---

### 2016-08 - 2018-06 | Thomas Magnete
Entwicklung von Embedded-Software in MISRA-C:2012 mit LIN-Interface zur Ansteuerung eines BLDC-Motors. Zusätzliche Entwicklung für den Systemtest: Eine Testumgebung in Python für das Embedded-System mit zusätzlicher UART-Kommunikation für Event-Logging und u.a. Fault-Injection-Tests.

#### Aufgaben:
* Anwendung der funktionalen Sicherheit (ISO 26262) auf System- und Software-Ebene
* Erarbeitung von Anforderungen und Testspezifikationen
* Erstellung der Software-Architektur für die Motoransteuerung
* Umsetzung einer BLDC-Motoransteuerung mit Stromregelung und Geschwindigkeitssteuerung
* Realisierung einer Single-Shunt-Strommessung zur Stromregelung
* Entwicklung eines SPI-Moduls für den Zugriff auf EEPROM und Motortreiber
* Entwicklung eines LIN-Stacks zur Kommunikation mit der Python-Testumgebung
* Implementierung von diversen Sicherheitsfunktionen

#### Hardware:
* MCU: Microchip dsPIC33EV128GM004
* Treiber: TI DRV8305

#### Tools:
* IDE: MPLAB X + PICkit 3
* Test-Framework: VectorCAST
* LIN-Adapter: PEAK PCAN-USB Pro FD

---

### 2015 | ROTH + WEBER
Entwicklung von Embedded-Software für ein Faltmaschinensystem.

#### Aufgaben:
* Entwurf der Software-Architektur für das Gesamtsystem
* Entwicklung eines USB-Kommunikationsmoduls
* Integration bestehender Software-Module für diverse Bussysteme (CAN, I²C, etc.)
* Erweiterung des Bootloaders um eine USB-Update-Funktionalität
* Einbindung der Schrittmotoransteuerung
* Umsetzung der Faltablauf-Steuerung

#### Hardware:
* MCU: Renesas RX600

#### Tools:
* IDE: Renesas e²Studio + J-Link

---

### 2014 | ROTH + WEBER
Entwicklung einer Faltmaschinen-Simulationssoftware mit Benutzeroberfläche in Java.

#### Aufgaben:
* Entwicklung eines Lagenrechners für Längs- und Querfaltung inklusive Visualisierung
* Erstellung eines Rechners zur Berechnung und Visualisierung der Faltprozessdauer
 
---

### 2013 | ROTH + WEBER
Portierung der Embedded-Software eines Druckersystems auf eine neue Hardware-Plattform, Refaktorierung der Software-Architektur und Entwicklung neuer Software-Module.

#### Aufgaben:
* Neuentwurf der Software-Architektur
* Refactoring und Modularisierung wiederverwendbarer Software-Komponenten
* Entwicklung neuer Software-Module für die Kommunikation via CAN, I²C, UART & 1-Wire
* Integration des bestehenden Bootloaders in die neue Architektur
* Implementierung der Ansteuerung für den Schrittmotor
* Einbindung und Optimierung der Druckablaufsteuerung

#### Hardware:
* MCU: Renesas RX600

#### Tools:
* IDE: Renesas e²Studio + J-Link

---

### 2013 | ROTH + WEBER
Weiterentwicklung einer Software für die Generierung von Typenschildern für verschiedene Maschinentypen in Java.

#### Aufgaben:
* Funktionserweiterung der Software zur Unterstützung neuer Maschinentypen

---

### 2013 | ROTH + WEBER
Weiterentwicklung eines vorhandenen Scannersystems inklusive Portierung der Embedded-Software und Anpassung des Windows-USB-Treibers.

#### Aufgaben:
* Portierung der Embedded-Software auf die neue Hardware-Plattform
* Anpassung des Windows-USB-Treibers für die Kommunikation mit der neuen Firmware

#### Hardware:
* MCU: Cypress EZ-USB FX3

---

### 2012 | ROTH + WEBER
Entwicklung einer Client-Server-basierten Lizenzverwaltungssoftware in Python für verschiedene Maschinentypen.

#### Aufgaben:
* Entwicklung einer Schnittstelle für den Datenaustausch mit dem ERP-System
* Realisierung einer Funktionalität für zeitlich begrenzte Trial-Lizenzen

---

### 2011 | ROTH + WEBER
Entwicklung von Embedded-Software für ein neues Scannersystem.

#### Aufgaben:
* Konzeption der Software-Architektur
* Implementierung eines CAN-Stacks inklusive ISO-TP-Kommunikationsprotokoll
* Entwicklung eines Bootloaders mit Update-Funktion über das CAN-Interface
* Umsetzung der Ablaufsteuerung für den Scan-Vorgang

#### Hardware:
* MCU: Renesas M16C

---

### 2010 | ROTH + WEBER
Entwicklung eines User-Mode-Treibers für die Kommunikation eines Scannersystems mit einem Windows-PC via USB2.

#### Aufgaben:
* Anpassung der LibUSB-Bibliothek für die USB-Kommunikation
* Entwicklung performancerelevanter Software-Komponenten als C-DLL
* Realisierung eines socketbasierten Kommunikationsdienstes in Python (XML-RPC, ctypes) für den Treiberzugriff

#### Hardware:
* MCU: Cypress EZ-USB FX2

#### Tools:
* Compiler: MinGW

---

### 2010 | ROTH + WEBER
Entwicklung einer Java-Applikation mit Benutzeroberfläche für die Konfiguration und Verwaltung eines Scannersystems.

#### Aufgaben:
* Umsetzung einer Benutzer- und Rechteverwaltung
* Realisierung der Verwaltung von Konfigurationsparametern
* Entwicklung einer Funktion für Firmware-Updates über die Applikation
* Implementierung der XML-RPC-basierten Kommunikation mit dem Scannersystem

---

### 2010 | ROTH + WEBER
Betreuung und Weiterentwicklung von Embedded-Software für ein Faltmaschinensystem.

#### Aufgaben:
* Implementierung einer Prozedur für Endlosfaltungen
* Laufende Fehleranalyse und -behebung (Bugfixing)

#### Hardware:
* MCU: Philips 80C592
