# Aleksandr Vavilov
## Contacts
* E-Mail : alvi.ua@gmail.com
* Telegram:  @alvi_brd https://t.me/alvi_brd
* Discord: 
* GitHub: alvi0avcc https://github.com/alvi0avcc
* LinkedIn: https://www.linkedin.com/in/aleksandr-vavilov-avcc/
## About
By main specialty I am a shipbuilding engineer.
Engaged in the development and support of shipbuilding projects. Subsequently, ship design was transformed into ship operation. And as a result, it grew into the provision of services for monitoring the execution of international contracts during transportation by sea.

But the main calling took over. I have always been interested in the IT direction.

Currently I am developing a personal project to determine/control the amount of bulk cargo.

https://avcc.sytes.net/

## Skills

### IT
* Delphi, C++
* JS, React
* HTML5, CSS3
* PHP
* Server administration - Windows, Linux, Unix
* Network administration

### CAD - systems
* AutoCad
* SOLIDWORKS
* Inventor
* UltiMaker Cura

## Code example

An example of a function for converting Cartesian coordinates to spherical coordinates.

function DecartToSphere ( x, y, z ){
    let r;
    if ( x == 0 & y == 0 & z == 0 ) { r = 0 }
    else { r = Math.sqrt( x*x + y*y+ z*z ); };
    let tetta;  
    let gamma;
    if ( x == 0 & y == 0 & z == 0 ) { tetta = 0; gamma = 0 }
    else {
        tetta = Math.acos( z / Math.sqrt( x*x + y*y + z*z ) );
        gamma = Math.atan( y / x );
    }
    return [ r, tetta, gamma ];
}

## Experience

### Bureau Veritas https://group.bureauveritas.com/
French inspection and certification company.

Provides services in the field of certification, industrial audit, technical inspection, technical supervision, inspection and verification of ships and cargo, checking compliance with standards in the field of quality, ecology, safety and labor protection.
* Position in the company - Ispection team leader

### Control Union https://www.controlunion.com/
Netherlands inspection and certification companies.

Control Union has been helping to build a better world for several decades. From our roots in agriculture, we have since grown to become a global trustworthy partner for testing, inspection and certification (TIC), providing a comprehensive range of quality services to clients in more than 80 countries.

* Position in the company - Regional Inspector/Manager>

### AVCC - Private project https://avcc.sytes.net/

This project is intended for calculating the volume of heaps of cargo. Primarily grains. The idea is based on keeping the required measurements to a minimum and maintaining acceptable accuracy.

* Position in the company - Owner. Developer.

## Education

* University:
  * Ukrainian State Maritime Technical University, ships and ocean engineering https://nuos.edu.ua/
    * Shipbuilding engineer (specialist).
* Courses:
  * Computer academy Step https://itstep.org/
    * C++
  * Tomsk State University https://tsu.ru/
    * HTML5, CSS3, JS.

## Languages
* Ukrainian - Native.
* Russian - Native.
* English - Special technical, not conversational.