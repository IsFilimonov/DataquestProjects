The dataset came from [FiveThirtyEight](https://www.fivethirtyeight.com/), and can be found [here](https://github.com/fivethirtyeight/data/tree/master/thanksgiving-2015).

This dataset contains the data behind the story [Here’s What Your Part of America Eats On Thanksgiving](https://fivethirtyeight.com/features/heres-what-your-part-of-america-eats-on-thanksgiving/).

* `thanksgiving.csv` - it contains 1058 responses to an online survey about what Americans eat for Thanksgiving dinner.
This dataset will allow us to discover regional and income-based patterns in what Americans eat for Thanksgiving dinner.

The dataset has 65 columns, and 1058 rows. Most of the column names are questions, and most of the column values are string responses to the questions. Most of the columns are categorical, as a survey respondent had to select one of a few options.

Here are descriptions of some of the most important:

Header | Description
---|---------
`RespondentID` | a unique ID of the respondent to the survey
`Do you celebrate Thanksgiving?` | a Yes/No reponse to the question
`How would you describe where you live` | responses are Suburban, Urban, and Rural
`Age` | resposes are one of several categories, such as 18-29, and 30-44
`How much total combined money did all members of your HOUSEHOLD earn last year?` | one of several categories, such as $75,000 to $99,999

Here are some potential next steps:

* Figure out the most common dessert people eat.
* Figure out the most common complete meal people eat.
* Identify how many people work on Thanksgiving.
* Find regional patterns in the dinner menus.
* Find age, gender, and income based patterns in dinner menus.
