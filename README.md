php-license-manager
===================

Open Source Software License Manager (PLM) for Propriatory Applications

The purpose of this project is to create a Licensing Manager to manage the licensing of your Propriatory Applications.

How this php script will work:
1) The php-license-manager will be based on PHP and mysql (LAMP).
2) It will be mainly for managing licenses for applications written for desktop users. The focus is not for use for licensing of server site scripts, allthough it may be possible.
3) Different Licensing models can be implemented, however we will start with implementing perpetial licensing with annual upgrade restrictions. In other words, users will need to renew their licenses annually to get access to upgrades.
4) No product keys or complicated license keys and codes will be required by the user to be entered.
5) The propriatory software will need to send the machine identifier (Or similar) to the licensing manager. The licensing manager will then generate the license using public and private key encryption and return the license, which is validated by the software.
6) The software will cache the license, and the license will be valid for a preset period of time. Once this period expires, the software will need to have access to the internet to renew the license and continue to operate. (This is to prevent installing multiple copies and taking it offline).
7) Each time a new license is issued, it will be logged in the database.
8) The propriatory software will communicate with PLM using an API. Shopping carts etc will also use its API.
9) PLM will not have a gui. GUI's can be developed as seperate projects using the API of the PLM

Enjoy Leonjvr 
