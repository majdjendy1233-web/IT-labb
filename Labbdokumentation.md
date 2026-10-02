# Labbdokumentation

Namn: Majed Jindi
Datum: 2026-10-02
Kurs: Introduktion till yrkesrollen och grunderna i IT-infrastruktur

## Introduktion

I denna labb har jag skapat en virtuell labbmiljö med Ubuntu och Windows 10 i VirtualBox. Jag har testat nätverk, behörigheter, kommandorad och Git.

## Labbmiljö och nätverk

Jag skapade två virtuella datorer i VirtualBox, en Ubuntu och en Windows 10.

Ubuntu IP: 192.168.1.50/24
Windows IP: 192.168.1.51/24

Jag testade anslutningen mellan Ubuntu och Windows med ping. Först fungerade det inte på grund av Windows brandvägg. Efter att jag ändrade inställningen fungerade ping med 0% packet loss.

## Linux och behörigheter

I Ubuntu skapade jag mappen:

/var/systementor/konsultdata

Jag skapade också filen anteckningar.txt och gruppen konsulter.

Mappen fick behörighet 750 och filen fick 640. Jag lade också användaren majed i gruppen konsulter.

Jag kontrollerade allt med ls -la och groups.

## Windows

I Windows använde jag PowerShell och skapade mappen:

C:\Systementor\KonsultData

Jag kontrollerade behörigheter med Get-Acl. Jag använde också ipconfig och ping för att testa nätverket.

## Git

Jag installerade Git i Ubuntu och konfigurerade mitt namn och email. Sedan skapade jag ett Git repository för labben.

Jag använde git add, git commit och git status. Jag kopplade sedan projektet till GitHub och skickade upp filerna med git push.

## AI-logg

Jag använde ChatGPT som stöd under labben. Jag använde AI för att förstå vissa Linux och Git kommandon och för felsökning när ping och GitHub inte fungerade.

Jag gjorde kommandona själv i mina virtuella maskiner och kontrollerade resultatet.
