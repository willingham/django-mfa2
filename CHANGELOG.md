# Change Log

## 2.0
  * Dropped support to djangp-1.8 and Python 2.7
  * Added: never-cache decorator
  * Fixes to Make Email Method More Robust 
  * Addresses several structure and style issues with TOTP and Email dialogs
  * Updated to fido2 0.8.1
    
Thanks to @swainn

## v1.9.1
   * Fixed: is_authenticated #13
   * Fixed: is_anonymous #6
    
    thanks to @d3cline,  

## v1.7
  * Better Error Management
  * Better Token recheck
## v 1.6.0
  * Fixed some issues for django>= 2.0
  * Added example app.

## v.1.5.0
  * Added id the key used to validate to the session dictionary as 'id'
## v1.4.0
  * Updated to FIDO == 0.7

## v1.3.0
  * Updated to FIDO2 == 0.6
  * Windows Hello is now supported.

## v1.2.0
 * Added:  MFA_HIDE_DISABLE setting option to disable users from deactivating their keys.
