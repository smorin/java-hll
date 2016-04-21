v1.6.0 - Jul 29, 2014
---------------------
* Added support for registering schema versions.

v1.5.2 - Jul 16, 2014
---------------------
* Fixed #10: Long overflow bug in `TWO_TO_L` calculation when `regwidth = 6`.

v1.5.1 - Feb 26, 2014
---------------------
* Fixed serialization compabitility issue. `expthresh` was not being decoded properly.

v1.5.0 - Feb 21, 2014
---------------------
* Fixed #5: Added HLL#clone().

v1.4.0 - Feb 04, 2014
---------------------
* Fixed #4: lowered JDK requirement to 1.6 from 1.7.

v1.3.0 - Jan 31, 2014
---------------------
* Fixed #3: added new, simple HLL constructor.

v1.2.1 - Jan 31, 2014
---------------------
* Fixed #2: fix HLL when `log2m * regwidth` is small.

v1.2.0 - Jan 17, 2014
---------------------
* Reworked pom for Maven Central publishing, via Sonnatype.

v1.1.0 - Jan 10, 2014
---------------------
* Documentation fixes.
* Added parameter checking in HLL constructor.

v1.0.0 - Dec 22, 2013
---------------------
* Initial public release.