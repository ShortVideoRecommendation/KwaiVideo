# KwaiVideo

Example dataset in this repository is a subset of the full dataset.
Full dataset: https://www.dropbox.com/s/roajzql3drdlttn/KwaiVideo.zip?dl=0

The format of dataset:
* train.txt
   - Train file.
   - Each line is a user with her/his positive interactions (effective view) with items: \[userID, a list of itemID, a list of is_like, a list of is_comment, a list of is_long_view\].

* test.txt
   - Test file.
   - Each line is a user with her/his positive interactions (effective view) with items: \[userID, a list of itemID, a list of is_like, a list of is_comment, a list of is_long_view\].
   - We treat all unobserved interactions as the negative instances when reporting performance.
