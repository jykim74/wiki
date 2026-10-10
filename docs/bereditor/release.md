## Version 2.9.4
- Fixed LDAP import issues and several critical errors

## Version 2.9.2
- Removed debug console messages
- Added license notification check
- Added EST client functionality
- Added ACME Challenge test functionality
- Fixed client-related errors
- UI improvements and bug fixes

## Version 2.9.0
- Implemented separate PDF Signer module
- Added support for PDF DSS VRI DocTimeStamp
- Improved OCSP/TSP view
- Added support for setting verification time for CMS PKCS7 PDF Signer
- Added visual distinction for modeless window backgrounds
- Fixed multiple errors and improved stability

## Version 2.8.6
- Added support for converting BER data from Indefinite length to Definite length
- Added Binary view support
- Added Text view support

## Version 2.8.4
- Added BER comparison support
- Changed private key creation to a modeless window
- Added label support for PDF signing

## Version 2.8.2
- Added private key creation support

## Version 2.8.0
- Fixed PDF signature view errors
- Fixed PKCS7 errors

## Version 2.7.8
- Added support for issuing free licenses via the license window (email input required)

## Version 2.7.6
- Added BER node view support
- Fixed "Save As" errors
- Fixed PDF signature errors
- Added data input support for PKCS7 CMS Detached signatures

## Version 2.7.4
- Fixed CMS PKCS7 errors
- Added PDF signing functionality

## Version 2.7.2
- Added icon indicators for expired certificate CRLs
- Added icons for individual function windows

## Version 2.7.0
- Fixed crash occurring on right-click in the BER tree
- Stability improvements implemented following previous testing limitations. - Users of previous versions are encouraged to update.

## Version 2.6.8
- Added "Previous/Next" navigation for BER
- Fixed BER search errors and added support for keyword inclusion/exclusion searches
- Fixed errors occurring when expanding BER BITSTREAM
- Added "Previous/Next" navigation for TTLV
- Fixed TTLV search errors and added support for keyword inclusion/exclusion searches
- Separated settings for displaying selected areas in BER and TTLV
- Added options to read CertMan CA and CRL during certificate path validation

## Version 2.6.6
- Fixed BER editing errors (add/delete/modify) and improved UI
- Added support for 0x80 length (Indefinite mode) during BER editing
- Fixed TTLV editing errors (add/delete/modify) and improved UI

## Version 2.6.4
- Fixed SSS errors and added support for GF(256)
- Added support for configuring PKCS8/PKCS12 encryption methods
- Improved internal management efficiency

## Version 2.6.2
- Added support for ChaCha20 and ChaCha20_Poly1305 encryption/decryption

## Version 2.6.0
- Added option for automatic expansion of BITSTRING and OCTETSTRING in DER view
- Improved display of Init/Update/Final state information
- Added support for identical RDNs in CSR DN display

## Version 2.5.8
- Bug fixes and UI improvements

## Version 2.5.6
- Bug fixes and UI improvements

## Version 2.5.4
- Added Drag and Drop support for multiple function windows
- Bug fixes and UI improvements

## Version 2.5.2
- Removed BER header from BITSTRING display in certificate signature information
- UI improvements

## Version 2.5.0
- Added support for PQC algorithms ML-KEM, ML-DSA, and SLH (key generation, CSR, digital signature, certificate)
- Hash - Added support for SHAKE128, SHAKE256, and SHA3 algorithms
- Display KID in Certificate, Private Key, and CSR views
- Added KEM functionality to Key Management
- Added BER format validation
- Added MAC verification functionality
- Updated to OpenSSL 3.5.3 library
- UI improvements and bug fixes

## Version 2.4.4
- Added Doc Signer functionality
- Separated PKCS7 CMS and improved functionality
- UI improvements and bug fixes

## Version 2.4.2
- Fixed errors and improved Certificate Management
- Fixed error in certificate path validation trust list support
- Internal code improvements

## Version 2.4.0
- Added support for viewing TSP messages in CMS view
- Prompt to save file on exit only if the path exists
- Added support for user authentication requests in TSP client
- Bug fixes and UI improvements

## Version 2.3.8
- Added right-click context menu support for CertMan, KeyPairMan, and KeyList
- Fixed CRL view error in X.509 comparison
- Added KeyPairMan support for public key encryption/decryption (signing/verification)
- Added binary file writing support in Data Converter
- Fixed PEM header error for private keys
- Bug fixes and UI improvements

## Version 2.3.6
- Added ACME client functionality
- Fixed time handling error for dates beyond 2038
- Stability improvements and bug fixes

## Version 2.3.4
- Fixed time handling error for dates beyond 2038 in Certificate CRLs

## Version 2.3.2
- Added support for importing/exporting DH parameters in Key Agreement
- Added X.509 (Certificate, CRL, CSR) comparison functionality
- Added timer display for BigNum calculations
- Font updates - Restricted settings to use monospace fonts
- Implemented DockWidget handling for SSL info tree and log windows
- Added OCSP Client and CA CRL BER retrieval functions to the certificate info window
- Added support for Nonce input and response CertID viewing in OCSP Client
- Completely revamped KMIP Encoder UI
- Various UI improvements and bug fixes

## Version 2.3.0
- Reads the most recent path when selecting files
- Improved CMS UI

## Version 2.2.8
- Fixed errors and improved stability for Shamir Secret Sharing
- Removed active state handling for table header UI
- UI improvements

## Version 2.2.6
- Improved Number Converter UI
- Added some explanatory UI messages
- Bug fixes and stability improvements

## Version 2.2.4
- Fixed error occurring with single-digit BigNum calculations
- Improved UI messages
- Fixed miscellaneous errors

## Version 2.2.2
- Added SCrypt support to Key Management
- Fixed error displaying trusted certificates during SSL checks
- UI improvements

## Version 2.2.0
- Added SM2 algorithm support
- Bug fixes and stability improvements

## Version 2.1.8
- Added "Restore Defaults" option in settings
- Updated English messages for toolbars, menus, etc.
- Bug fixes and UI improvements

## Version 2.1.6
- Fixed license recognition errors
- UI improvements and bug fixes

## Version 2.1.4
- Added key list management function
- Added line numbering and improved views for XML, JSON, and Text
- Added line numbering for info views
- Stability and UI improvements
- Bug fixes (Critical bug fixed; please update)

## Version 2.1.2
- Added BER TTLV search function
- UI improvements

## Version 2.1.0
- Added toolbar icon selection support
- Added JSON view support - Added links to PKI standard documents
- Improved export UI

## Version 2.0.8
- Added support for viewing CMS (PKCS7) messages
- Improved CMS functionality
- Added key editing settings for key pair management
- UI improvements and bug fixes

## Version 2.0.6
- Added partial support for ACVP basic algorithms (limited to basic options)
- Added integration for sign/verify and public key encryption/decryption in certificate and key pair management
- Added support for Hash MCT alternate
- Added IV input support for GMAC
- Added support for DRBG without a nonce
- Fixed CCM encryption/decryption error (error occurred when AAD was missing)
- Fixed Seed MCT error

## Version 2.0.4
- Added support for HKDF and ANSX963 KDF in key management
- Fixed errors in CMP, OCSP, TSP, and SCEP clients
- Fixed CAVP MCT test errors
- Fixed CertMan errors
- Stability improvements and UI enhancements

## Version 2.0.2
- Improved BN calculator UI
- Added support for full and partial views for JSON and Text
* Supports both BER and TTLV
* Highlights selected areas in full view
* Removed SyntaxHighlighter (to eliminate lag)
- Fixed EdDSA sign/verify errors
- Other performance improvements and stability fixes

## Version 2.0.0
- Stability improvements and bug fixes
- Significant UI interface improvements
- Please update, as many critical errors have been fixed.
