
Date of creation: Jul 09, 2015. Last update: Jul 16, 2015.

# What is this?

A phpBB extension: TABLEK BBCode, which is to facilitate table creation in posts.

Tested on phpBB 3.1.9.

# Syntax

## Full syntax

`[tablek html attributes | css attributes]
{first row html attributes | css atributes }
|first row first col html attributes [ css attributes } first row first col
first row first col second line
|first row second col html attributes [ css attributes } first row second col
{second row html attributes | css atributes }
|second row first col html attributes [ css attributes } second row first col
|second row second col html attributes [ css attributes } second row second col
second row second col second line
[/tablek]`

HTML equivalence:

`<table  html attributes  style=" css attributes"><tr first row html attributes  style=" css atributes "><td first row first col html attributes  style=" css attributes "> first row first col<br />first row first col second line<br /></td><td first row second col html attributes  style=" css attributes "> first row second col<br /></td></tr><tr second row html attributes  style=" css atributes "><td second row first col html attributes  style=" css attributes "> second row first col<br /></td><td second row second col html attributes  style=" css attributes "> second row second col<br />second row second col second line<br /></td></tr></table>`

## Most minimum syntax

`[tablek]
{}
|first row first col |first row second col
{}
|second row first col |second row second col
[/tablek]`

HTML equivalence:

`<table><tr  style=""><td>first row first col </td><td>first row second col<br /></td></tr><tr  style=""><td>second row first col </td><td>second row second col<br /></td></tr></table>`

You can mix those two for your best convenience.

No nested tablek bbcode allowed. You cannot put a tablek inside bbcode tablek, it does not cause any bug, the tablek bbcode just does not work out the way you want.
