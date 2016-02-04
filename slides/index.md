- title : Yr tabber < 2016
- description : tabber på Yr i det siste
- author : Bård Rolstad Henriksen
- theme : sky
- transition : default

***
- data-background : images/YR-flagg.svg
- data-background-repeat : no-repeat
- data-background-size : 100%

' rorbua

***

# Tabber på YR
### www.yr.no (aka mmx)
* litt om Arkitektur
* tail calls
* 30. april 2015
' to historier

***

## Arkitektur
![Monolitt](https://upload.wikimedia.org/wikipedia/commons/9/9c/Vigelansparken.JPG)
' fek. sql brukes til config og stedsnavn
' organisk vekst i 8 år (folk)
' ikke _så_ ille

***
## i 2013 en gang

Frontene kræsjer

* `StackOverflowException` (??)
* `InvalidProgramException` (???)
* `AldriSettFørException`
* `FinnesIkkePåSOException`
' stor deploy

***

### git commit
```
Slår av "Generate tail calls" i et desperat forsøk på å fikse:
  System.InvalidProgramException
  Common Language Runtime detected an invalid program
```

* En rotekopp hadde slått på generate tail calls i F#-prosjektet

' Oppgradering av F# prosjektfil
' blanding av feil brik av IDisposable + F#

***
## desperasjon
### git commit - 30. april
```
Revert "EntityFramework 6.1.3" TREGT?
Revert "net451"
```
' original deploy hadde 1 mnd gammel kode
' før en helg
' ikke nede, men tregt

***
### git commit - 4. mai
```
Revert Revert "net451"
Revert Revert "EntityFramework 6.1.3" TREGT?
```
' etter helga

***
### Hva skjer ???
* tregt
* Timeouts
* Sql timeouts


***
### gjettekonk
1. DynamiskConfig & snøskredsesong
2. Met's api er tregt
3. vmware tools oppgradering
4. generate tail calls

---
# vmware nettverkskort
  * i 2015
  * i verdens 6. rikeste land
  * ops var flinke (Victor / Marius)
' 1 måned gammel kode
' 1 måned gammel patch
' reboot av server triggea feil

***
### Hva har vi lært?
* ❤ CI CD
* ❤ (dev)ops
* Aldri nok test
* Ikke fikle med saker som funker

***
## Bonus
*
