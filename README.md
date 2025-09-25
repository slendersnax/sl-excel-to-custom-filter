# excel-to-custom-filter

a sublime package for converting an Excel column of unique ids into a Decipher Custom Filter search query

## installation

Code > Download ZIP. Then install to your Sublime Text Packages folder (same instructions as [this package](https://github.com/slendersnax/decipher-sublimetext-clips))

## how to use

1. copy the excel column (which should look as follows, with the first row containing the id name)

![example](example.png?)

2. select all the text that you just copied
3. look for *"Excel to Custom Filter"* in the Command Palette
4. ??? (press enter)
5. profit

it's going to look something like this: 

```python
uuid in ['12314415', 'eifnsing', 'rneognon']
```