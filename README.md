# MRS-Tab-HideBases

An add on to table scripts which helps you hide bases, if needed.

It is a very rare request to hide all bases. It hides ALL bases, including the one at the top.

The code here iterates over all elements and hides all `base` elements with the exception if `base` is the only visible element within axis.

This was develped for Disney BES project.

## Usage ##

Edit TRun.mrs, and add<br />
`#include "T_Tables_HideBases_Functions.mrs"`<br />
next to<br />
`#include "Includes\Table\TableFunctions.mrs"`

And add<br />
`HideBasesIterateTables(tabledoc.tables)`<br />
after<br />
`#include "T_Tables.mrs"`
