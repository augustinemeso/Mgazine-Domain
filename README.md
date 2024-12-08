## Magazine Domain 

### Date: 2024/12/08

#### AUGUSTINE MESO

##### Instructions/Description
Welcome to the Magazine Domain project! In this assignment.The goal is to create a system where:

Authors can write articles.
Articles belong to a Magazine and are written by an Author.
You can perform various operations such as adding articles to magazines, setting constraints on article titles, and tracking the contributors to magazines.

#### Setup

Clone the repository:
Install dependencies 

pipenv install
pipenv shell

Run tests: You can run the tests using (python -m pytest)
This will run all the tests in the project

Testing output: To verify that your tests have run successfully, you should see an output similar to the following:


==================== test session starts =====================
platform linux -- Python 3.8.10, pytest-8.3.3, pluggy-1.5.0
rootdir: /home/augustine/Development/code/phase-3/Magazine-Domain
collected 9 items

tests/article_test.py ..                               [ 22%]
tests/author_test.py ...                               [ 55%]
tests/magazine_test.py ....                            [100%]

===================== 9 passed in 0.03s ======================
This output indicates that 9 tests were collected and executed, and all tests passed.

##### Core Deliverables

Author:
articles(): List all articles written.
magazines(): List unique magazines contributed to.

Magazine:
articles(): List all articles published.
contributors(): List unique authors for the magazine.
Bonus Methods
Author:

add_article(magazine, title): Creates and associates a new article with the author and magazine.
topic_areas(): List unique magazine categories the author has contributed to.
Magazine:

article_titles(): List titles of all articles.
contributing_authors(): List authors with more than two articles.
classmethod top_publisher(): Returns the magazine with the most articles.



###### Technologies Used

Python 3.8+
pipenv install
pipenv shell
python -m pytest (for testing)
Github

##### Expected Features

Magazine Class
Article Class
Author Class

#### Support and Contact Details

You can view my GitHub repository for this project here:
https://github.com/augustinemeso/Magazine-Domain
