Foodsoft - Web based software to manage a non-profit food coop
==============================================================

`Foodsoft`_ is web-based software for managing non-profit food coops
(product catalog, ordering, accounting, job scheduling).

A food cooperative is a group of people that buy food from suppliers of their
own choosing. A collective do-it-yourself supermarket. Members order their
products online and collect them on a specified day. And all put in a bit of
work to make that possible. Foodsoft facilitates the process.

The Foodsoft appliance includes all the standard features in `TurnKey
Core`_, and on top of that:

- Foodsoft
- Two versions: standard and foodcoop-adam (choose on first boot).
- SSL support out of the box.
- Includes Phusion Passenger for Apache web server (mod_rails).
- Uses Ruby Enterprise (performance).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, Webshell, SSH, MySQL: username **root**
-  Foodsoft: username **admin**


.. _Foodsoft: https://github.com/foodcoops/foodsoft
.. _TurnKey Core: http://www.turnkeylinux.org/core
