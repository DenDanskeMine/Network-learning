---
title: Velkommen til Network Learning
---

# Network Learning

Velkommen til **Network Learning** - din online ressource til at lære at konfigurere netværk og firewalls. Vores mål er at hjælpe dig med at forstå og mestre designet og implementeringen af sikre og effektive netværk.

![Network Learning Logo](assets/logo.png){ align=right }

## Introduktion

> "Netværk er nervesystemet i enhver organisation. Lær at mestre det, og du vil have kontrol over hele systemet." - [Martin Donath](https://squidfunk.github.io/mkdocs-material/)

## Funktioner

Vi tilbyder en bred vifte af ressourcer og funktioner for at hjælpe dig med din læring:

- 🚀 **Grundlæggende og avancerede tutorials**
- 🛠️ **Praktiske øvelser og kodeeksempler**
- 📚 **Detaljeret dokumentation og referencer**
- 🎓 **Certificeringsforberedelse**

## Kom godt i gang

=== "Begynder"

    Hvis du er ny til netværk, anbefaler vi at starte her:

    1. [Introduktion til netværk](docs/intro.md)
    2. [Grundlæggende netværkskonfiguration](docs/basic-configuration.md)

=== "Avanceret"

    For de mere erfarne brugere, dyk ned i avancerede emner:

    1. [Avanceret netværkssikkerhed](docs/advanced-security.md)
    2. [Firewalls og adgangskontrol](docs/firewalls.md)

## Eksempel på kode

Lad os se på et simpelt konfigurations eksempel for en router:

```yaml
interface GigabitEthernet0/0
 description Link to ISP
 ip address dhcp
 duplex auto
 speed auto
!
interface GigabitEthernet0/1
 description LAN
 ip address 192.168.1.1 255.255.255.0
 duplex auto
 speed auto
```

!!! info "test"
    dett eer en test

!!! tip "test"
    dette er en test    

???+ tip "test"
    dett eer en test      

??? tip "test"
    dett eer en test  
