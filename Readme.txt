GO - Automation Tool
Revision History

Version	Date		Author
v0.1	1989,1990	Emanuel Mashian
- Original Coding - Pascal Sources.
v1.0	1991-04-19	Lloyd Tabb
v1.1	1991		Georges Rahbani
- Added support for aliased variables (placed in angle brackets).
v1.2	1991-05-24	Richard Rozsa
- Added support for 'home' directory.
- Added command line switch processing (to get help screen).
v1.3	1991-08-29	Richard Rozsa
- Cleaned up and commented code.
- Added support for leading white space before labels and aliases.
- Added include file support (filename prefixed by '!').
- (aliases currently not supported in include files.)
v2.0	1991-08-29	Richard Rozsa
- Added support for DOS variables in expansion list (%var%).
v3.0	1991-09-09	Richard Rozsa
- Converted source code from PASCAL to Borland C.
- Now allows go tables to have the read-only file attribute set.
v3.1	1991-09-09	Richard Rozsa
- Added support for novell style "..." directory references.
v3.2	1991-09-11	Richard Rozsa
- Localized some global variables.
- Reworked GO and HELP functions.
- General cleanup.
v3.3	1992-09-28	Richard Rozsa
- Added /m parameter: make any directory that's not found.
- Fixed bug that prevented a go to an <alias> value.
v3.4	1994-01-25	Richard Rozsa
- Fixed bug in GetQuotedString() where (char *) variable was used
  instead of (int) to calculate length of strncpy().
  This fix allows dos variables to be referrenced by aliases.
v3.5	1995-05-23	Richard Rozsa
- No longer upper case strings. Preserve typed or alias file case.
v4.0	2022-08-23	Richard Rozsa
- Conversion from C source to C#.
  Lots of intermediary versions were lost.  This is the latest snapshot.
