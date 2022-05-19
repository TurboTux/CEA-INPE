# CEA-INPE
CEA stands for "**C**hemical **E**quilibrium with **A**pplications" and NASA means (for those who don't already know) "**N**ational **A**eronautics and **S**pace **A**dministration".
## According to program's home page (*original text*):
"The NASA Computer program CEA calculates chemical equilibrium compositions and properties of complex mixtures. Applications include assigned thermodynamic states, theoretical rocket performance, Chapman-Jouguet detonations, and shock-tube parameters for incident and reflected shocks.
...
The program is written in ANSI standard FORTRAN by Bonnie J. McBride and Sanford Gordon..."

---
## Some history now (out of curiosity):
Original FORTRAN (or FORmula TRANslator) is a language created in 1954(!!!), and released commercially in 1957. The start of the CEA program took place when not even NASA was called NASA.

...

To make a long story short, many calculations were incorporated into the program, which was renamed CEA in 1994 (and remains to this day).

...

Fun fact: FORTRAN is the oldest commercial programming language. It has 11 revisions and improvements, and the lastest one was launched in 2018!!!

---
## Back to today
The current version of CEA uses a Java applet to create a graphical interface to use the FORTRAN code (which is a batch-program style) to run, but it has no restrictions and field validations, and with that need was born CEA-INPE.

CEA-INPE is a *brand-new* graphical user interface to use with CEA-NASA's core program.

Modest minimum system requirements are:
- Windows XP (SP3) compatible operating system - in this case mail me at ***ricardo.andrade@inpe.br*** for me to provide another way to install, since MSI package in Windows XP is big trouble.
- .Net Framework 4 <-> 4.8 (just to plot charts, the new option. <a href="https://c.tenor.com/dmUPx0eFh4AAAAAC/fuck-microsoft.gif"Thanks to Microsoft</a>, the chart control only exists in .Net 4).
- 4MB disk free space (less than your high-res photo on desktop wallpaper)
- 12MB free RAM (even the first iPhone has it)

***
![XP](https://user-images.githubusercontent.com/49453668/164008485-a6e0c33c-8dbf-43d6-9e5e-0e306838258e.jpg)

- [UPDATE] I am proud to announce that CEA-INPE **IS** compatible even with the non-Windows operating system: ***ReactOS***. It's an unimaginable programming breakthrough for me!
![ReactOS](https://user-images.githubusercontent.com/49453668/163242165-50209854-6bf5-4633-ac07-032cbdd17434.png)


Just install the package downloaded (virus-free! If your antivirus says it has, it's lying) and run with the shortcut created in Start Menu, or on Desktop.
Happy calculations!


***
### Version History

- 0.1 to 1.0 - making (and remaking) the user interface
- 1.1 to 1.2 - creating all field constraints to avoid any misplaced comma
- 1.3 - created first-ever installer
- 1.4 - created first-ever help file
- 1.5 - first public version
- 1.6 - help file adjusted
- 1.65 - forgot to update screenshots (damn!)
- 1.8 - typo revision
- 1.9 - second public version
- 1.99 - damn misplaced letters - checked all interface again!
- 2.0 - bug hunting
- 2.01 to 2.02 - bug smashing
- 2.03 to 2.13 - redesigned user-reactant window, with new constraints
- 2.14 - treats "," like "." to make calculations right
- 2.15 - first REALLY public version (forget all the past! Version history is merely informative)          <- we are here!
    (*The Three Stooges (Only, Omit and Insert tabs) still not working properly. Sorry.*)
- 2.16 - I hope it doesn't exist anytime soon...
- 2.4 - jumped minor versions because a new milestone achieved! New window plot the items selected in "Other -> Output" tab. And it has a new splash screen too!
