# UFO

## Purpose

The purpose of the project is to create table that can be filtered to allow users to interact with the data on a deeper and more visceral level. The end result will by a fully dynamic table that can react to user input and present the data in an easy to view HTML format.

## Results

Upon entering the site, users are immediately able to determine it's purpose and intuitively understand how to utilize it thanks to the simplistic design. The hook within the jumbotron header is perfect to incite further curiosity of potential users.

#### The Truth is Out There
![jumbotron](https://github.com/jdfiel/UFO/blob/main/Resources/default_filter.png)

The fact that the data table loads upon entering the site in combination with the filter placeholders gives users visibility of the form of the data that they would require to best utilize the filters. 

#### Default Filter and Data Table
![default_filter](https://github.com/jdfiel/UFO/blob/main/Resources/filter_ex.png)

To filter the data, users need to simply look at the preloaded data table and decide which of the designated variables they want to use to streamline their information search. The layout and input event listener make the entire filtering process seamless. Once entered, the data is provided in a neat and digestable format for users to view.

#### Filtered Search in Action
![example_search](https://github.com/jdfiel/UFO/blob/main/Resources/the_truth_is_out_there.png)

## Summary

One major drawback of this design is the fact that users will be required to know the abbreviations for states, which is further compounded by the fact that the data table is not visible when a filter input is entered incorrectly.

One way to improve upon this drawback would be to either create a dropdown menu of the states or create an additional dictionary that can be used to reference the name of a state to its abbreviation and then to the raw json data file.

Another way to streamline the experience would be to create a 'Clear Filter' button. This would remove the need for users to manually delete each entry every time that want to search for new data.
