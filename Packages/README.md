# Packages

## Overview

This directory contains the following packages:

- `quickimage`: allows to do simple figure with less LaTeX code. forget the long commands to do simple figure triks

Arguments between "[" and "]" are optional

## Package details

1. **quickimage**
   1. Commands
      - `\singleimage[image width ratio]{file source}{caption}[additional info]`
        The additional information could for instance contains `\label{fig:image1}`, you can also put the label inside the caption
      - `\doubleimage{file1 source}{caption1}[additional info 1]{file2 source}{caption 2}[additional info 2]`
      - `\doubleimagecaption{file1 source}[caption1]{file2 source}[caption 2]{caption for both images}[additional info for both images]`
      - `\doubleminipage[ratio left minipage][ratio right minipage]{left minipage content}{right minipage content}`
        If you decide to use ratio left or right argument, you have to use both of them.
        If you want the text in a minipage to be on top of it, you must replace the 'c' argument by 't' in the \minipage
      - `\imageleft[ratio left minpage][ration right minipage]{file source}{caption}[additional info]{right minipage content}`
        If you decide to use ratio left or right argument, you have to use both of them.
      - `\imageright[ratio left minpage][ration right minipage]{file source}{caption}[additional info]{leftminipage content}`
      - `\wrapfigure[ration textwidth]{l/r}{file source}{caption}[additional info]`
   2. Environements

