# language-tie
TIE grammar (for the RG-2016.3 release) package for Atom based off the [language-c package](https://github.com/atom/language-c).

Contributions made by [DamnedScholar](https://github.com/DamnedScholar) and [nixel2007](https://github.com/nixel2007).

Version history:  
0.1.0 - Initial commit with highlight definitions for datatypes and numbers.  
0.2.0 - Improved datatype and added comment and function highlighting.  
0.3.0 - Added support for highlighting #include, #import and extended the numeric and storage types.  
0.4.0 - Added support for highlighting embedded PERL code and extended the storage types.  
0.5.0 - Added string highlighting and all control keywords based on the documentation of the RG-2016.3 release. Updated highlighting of numeric types for binary, decimal and hexadecimal.  
0.6.0 - Added support for highlighting def, shared and use. Made two numeric types case-insensitive and removed #include and #import highlighting since it is not present in TIE.  
0.7.0 - Added support for highlighting octal numbers.  
0.8.0 - Added automatic indentation for curly brackets.  
1.0.0 - First release of the package. Also available for download from within Atom.  
1.1.0 - Added support for highlighting inline PERL variables and *.tppout input files. Embedded PERL background colour style now loads automatically when Atom starts.

TODO's:
- Clean up the code  
- Add banners for 'build passing', 'no dependencies' etc.  
- Add highlighting for # comments in *.tppout file.  
- Settings for styles.less such as PERL background color. See: https://discuss.atom.io/t/update-styles-less-upon-package-installation/35628/4
