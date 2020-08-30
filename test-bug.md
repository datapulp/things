DOCUMENT-TITLE: "HOW TO WASTE 20MINUTES AT HOME, BY YOURSELF"<br/><br/>The configuration of the plugin is editable, meaning that this bugerport is unnecessary... It does demo making a bugreport however, **so I'll keep it for that alone...**<br/><br/>This file demonstrates how there is an incosistency with newline.<br/>When successive characters are text are added to a newline, characters are also printed on a newline ***in the preview***  which I think is a mistake.<br/> This is because using GFM (github flavored markdown) 'markdown syntax'; text printed on a newline will simply continue the previous one.<br/>For demonstration purposes the rest of this file reenacts the scenario, in order to aid in providing context :).<br/><br/>Thank you for your time, my excellency.<br/><br/>
#### DEMO:labeling the file's row-numbering
row2
row3
row4
row5

#### DEMO-RAW:labeling the file's row-numbering
```
#### labeling the file's row-numbering
row2
row3
row4
row5
```

<br/><br/>

#### DEMO:Multiline using '\' & '  '
row20\
row21  
row22

row24

#### DEMO-RAW:Multiline using '\' & '  '
```
#### DEMO:Multiline using '\' & '  '
row20\
row21  
row22

row24
```
