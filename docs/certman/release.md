## Version 2.3.4
- Fixed EDDSA-related bugs

## Version 2.3.2
- Added TSP, OCSP, CMP, ACME, EST, and SCEP services
- Removed debug console messages
- Added license notification check
- UI improvements and bug fixes

## Version 2.3.0
- Added support for issuing free licenses via the license window (email input required)

## Version 2.2.8
- Added icon indicators for certificate CRL expiration
- Added icons for individual function windows
- Note: Due to database changes regarding certificate expiration indicators, files created in previous versions are incompatible

## Version 2.2.6
- Fixed errors in SetPassword and ChangePassword functions
- Added support for duplicate RDN values ​​during CSR generation
- Added partial drag-and-drop support
- UI improvements and error fixes

## Version 2.2.4
- Fixed multiple errors and improved UI

## Version 2.2.2
- Removed BitString BER header from displayed certificate signature values
- Fixed multiple errors and improved UI

## Version 2.2.0
- Added support for issuing PQC algorithm (ML-DSA, SLH-DSA) key pairs, certificates, CSRs, and CRLs
- Updated to OpenSSL library version 3.5.3
- Added KID display in certificate, CSR, and private key views
- UI improvements and multiple error fixes

## Version 2.1.4
- Fixed CRL generation error

## Version 2.1.2
- Added right-click support for HsmMan
- Fixed error displaying PEM headers for private/public keys during export
- UI improvements

## Version 2.1.0
- Fixed time-handling error for dates beyond 2038
- Stability improvements and UI enhancements

## Version 2.0.8
- Updates regarding certificate CRLs Fixed time-handling error for dates beyond 2038

## Version 2.0.6
- Improved certificate and CRL profile views
- Restricted font selection to monospaced fonts
- Various UI improvements and stability enhancements

## Version 2.0.4
- Added feature to remember the last used path when selecting files
- Improved error messages

## Version 2.0.2
- Changed CRL DB schema (not backward compatible with previous versions)
- Removed UI activation logic for table headers
- Fixed various errors and improved UI

## Version 2.0.0
- Fixed CRL verification error
- Improved UI and program stability
