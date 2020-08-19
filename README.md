# Fullstack Engineer Interview

## You’re tasked with building APIs and frontend to power this view:

### Topic Analysis

There are 4 panes in this view.

1.  Feedback Viewer: Each feedback has the following attributes:
    1. Text
    2. List of Topics + Themes
    3. Score (6,8,10,10) etc
    4. Date
2.  Net Sentiment Score: For the selected theme, calculate the net sentiment (pos sentiment - neg sentiment). Show the number of responses filtered as well.
3.  Theme Selector:
    1. Checkboxes to select different themes. Selecting a topic, selects all themes in it. This modifies the feedback viewer and net sentiment score panes.
    2. A search button to find topics/themes.
    3. A reset button to reset back to the theme with which the page was opened.
    4. Against each theme/topic show #mentions and sentiment bar.
4.  Pagination and sorting:
    1. Paginate across the feedbacks
    2. Sort by date, highest sentiment, lowest sentiment etc.

![alt text](images/topic_details.png "topic details")

### Evaluation Criteria

1.  Features implemented
2.  API design & Data modelling
3.  Robustness of code - patterns used/tests/comments etc

### Things to note

1. The intention is not to implement everything but to see if you can implement everything. If you leave something as a TODO, do give that feature some thought. We will discuss on the followup as to how you would go about solving it.
2. Push your code in this repo. Work like how you would work in a real life setting, breaking things into commits, adding tests, proper low level design etc.
3. We’ve intentionally left quite a few things vague and ambiguous to replicate the real environment.
4. We’d recommend using golang + react but it's your choice.
5. Put your code in the folder `src`.
6. Sample data is present in `data`. The API can work off of in-memory database. Do note: in the sample data, there is a 1:1 mapping between theme and topic. Please keep your implementation independent from this fact. A topic can have multiple themes in it.
7. This is more of a LLD assignment. On the call, we will go over HLD of this.
