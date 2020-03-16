# COVID-19

## EDA

In order to understand the scope of this Pandemic some EDA needs to be done to look at the spread of the COVID-19 Virus

The First Step in this process is to see how many countries are infected so I took all the unique values in the Country/Region column and took a quick look and count. This data set lists 161 countires that have been infected.

```python
countries = df["Country/Region"].unique().tolist()
print("{} countries have been affected by the virst".format(len(countries)))
print(countries)
```

But just a list of countries doesnt tell us much so the next step was to look at how many confirmed cases there are per country which shows the following break down

```
input table
```

I next wanted to look at these same values in a graphical format to understand the how the 10 most affected countries look next to eachother

```
input image
```